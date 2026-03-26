
```markdown
# Reference: Pine to MQL5 Snippets Library

This document provides technical implementations for the rules defined in the [Master Guide](../Pine_to_MQL5_Master_Guide.md).

---

## ## [CORE_EXECUTION_STATE]

### 1.1 var vs varip (Persistence)
```cpp
// [RULE 1.1a] var (Historical Persistence)
// Equivalent to Pine: var float myVar = 0.0
static double m_historicalVar;
if(prev_calculated == 0) {
    m_historicalVar = 0.0; // Hard reset on history reload
}

// [RULE 1.1b] varip (Intrabar Persistence)
// Equivalent to Pine: varip float tickAccumulator = 0.0
static datetime lastBarTime = 0;
static double m_tickAccumulator = 0;

if(time[0] != lastBarTime) {
    m_tickAccumulator = 0.0; // Reset logic at bar start
    lastBarTime = time[0];
}
m_tickAccumulator += 1.0; // Updates every tick
```

### 1.2 Incremental Looping
```cpp
// [RULE 1.2] Pattern to avoid O(N^2) complexity
int OnCalculate(...) {
    // start from prev_calculated - 1 to re-evaluate the currently forming candle
    int start = (prev_calculated > 0) ? prev_calculated - 1 : 0;

    for(int i = start; i < rates_total; i++) {
        // Recursive and non-recursive logic stays safe here
    }
    return(rates_total);
}
```

### 1.3 Indexing Direction
```cpp
// [RULE 1.3] Mandatory Series Alignment
void InitSeries(double &buffer[]) {
    ArraySetAsSeries(buffer, true); // Now buffer[0] is the current bar
}
```

---

## ## [DATA_STRUCTURE_MAPPING]

### 2.1 User Defined Types (UDTs)
```cpp
// [RULE 2.1] Pine 'type' to MQL5 'class'
class CPineUDT {
public:
    double price;
    string label;
    CPineUDT(double p, string l) : price(p), label(l) {}
    
    // Pine-style method
    double GetOffset(double current) { return MathAbs(price - current); }
};
```

### 2.2 Advanced Collections
```cpp
// [RULE 2.2a] Pine Map -> CHashMap
#include <Generic\HashMap.mqh>
CHashMap<string, double> m_map;

// [RULE 2.2b] Pine Matrix -> Flattened 1D Array
#define MAT_IDX(r, c, cols) ((r) * (cols) + (c))
double m_matrix[]; // Use ArrayResize(m_matrix, rows * cols)
```

---

## ## [MTF_SECURITY_ALIGNMENT]

### 3.1 Non-Repainting Security
```cpp
// [RULE 3.1] The Shift + 1 Rule
double GetSecureHTF(string sym, ENUM_TIMEFRAMES tf, datetime ltf_time) {
    int htf_shift = iBarShift(sym, tf, ltf_time, false);
    if(htf_shift == -1) return EMPTY_VALUE;
    
    // index + 1 ensures the HTF bar is fully CLOSED
    return iClose(sym, tf, htf_shift + 1); 
}
```

### 3.2 Data Synchronization Guard
```cpp
// [RULE 3.2] Validation before access
int shift = iBarShift(_Symbol, PERIOD_H4, time[i], false);
if(shift == -1) {
    // Handle missing history data gracefully
    buffer[i] = EMPTY_VALUE;
    return; 
}
```

---

## ## [STRATEGY_EA_PARITY]

### 4.1 Execution Gating (New Bar)
```cpp
// [RULE 4.1] Mimicking Pine's Bar-Close evaluation
bool IsNewBar() {
    static datetime lastTime = 0;
    datetime curTime = iTime(_Symbol, _Period, 0);
    if(curTime != lastTime) {
        lastTime = curTime;
        return true;
    }
    return false;
}
```

### 4.2 ECN-Compatible Trading
```cpp
// [RULE 4.2] Entry -> Position Selection -> Modify
#include <Trade\Trade.mqh>
CTrade trade;

void ExecuteEntry(double sl, double tp) {
    if(trade.Buy(0.1, _Symbol)) {
        // Many ECN brokers require SL/TP in a separate modification call
        trade.PositionModify(_Symbol, sl, tp);
    }
}
```

### 4.3 Pyramiding Logic
```cpp
// [RULE 4.3] Manual Position Counting
int GetPyramidingCount(long magic) {
    int count = 0;
    for(int i = PositionsTotal() - 1; i >= 0; i--) {
        ulong ticket = PositionGetTicket(i);
        if(PositionSelectByTicket(ticket)) {
            if(PositionGetInteger(POSITION_MAGIC) == magic && PositionGetString(POSITION_SYMBOL) == _Symbol) 
                count++;
        }
    }
    return count;
}
```

---

## ## [SILENT_TRAPS_CHECKLIST]

### TRAP_1: Floating Point Drift
```cpp
// Solution: Always normalize before trade requests
double sl_price = NormalizeDouble(Bid - 100 * _Point, _Digits);
```

### TRAP_2: Recursive Drift
```cpp
// Solution: Use incremental updates for EMA/RMA
static double prevEMA = 0;
if(prev_calculated == 0) prevEMA = close[i];
double currentEMA = (close[i] - prevEMA) * alpha + prevEMA;
prevEMA = currentEMA;
```

### TRAP_3: Implicit NaN
```cpp
// Solution: Guard against 'na' equivalent math corruption
double val = iRSI(_Symbol, _Period, 14, 0);
if(!MathIsValidNumber(val)) val = 0.0; //nz() equivalent
```

### TRAP_4: Array Direction Consistency Guard
```cpp
// Solution: Explicitly verify indexing mode to avoid signal inversion
if(!ArrayGetAsSeries(myBuffer)) {
    ArraySetAsSeries(myBuffer, true);
}
```

### TRAP_5: Explicit Division
```cpp
// Solution: Force double casting to prevent integer truncation
double ratio = (double)current_index / total_count; // Pine: current_index / total_count
```
```


