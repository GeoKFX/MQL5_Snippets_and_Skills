# Custom Useful MQL5 Snippets

Collection of advanced algorithmic solutions for MQL5.

### Calculate Broker GMT Offset
```mql5
//+-----------------------------------------------------------------
 -+
 //| Calculate Broker's GMT Offset                                    |
 //| Returns the difference in hours between broker time and GMT.     |
 //+-----------------------------------------------------------------
 -+
 int CalculateGMTOffset() {
   // Get the current broker server time
   datetime serverTime = TimeCurrent();
   // Get the current GMT/UTC time
   datetime gmtTime = TimeGMT();
   // Calculate the difference in seconds
   // Type casting to int is important here
   int offsetSeconds = (int)(serverTime - gmtTime);
   // Convert the offset from seconds to hours
   // Integer division automatically handles whole hours
   int offsetHours = offsetSeconds / 3600;
   // WARNING: This offset might change if the broker's server
 observes Daylight Saving Time (DST).
   // This function calculates the *current* offset only.
   Print(__LINE__, ", AutoGMT: ServerTime=",
 TimeToString(serverTime), ", GMTTime=", TimeToString(gmtTime), ",
 OffsetSeconds=", offsetSeconds, ", OffsetHours=", offsetHours);
   return(offsetHours);
 }
```

---

### Lot Size Calculation (Margin per Micro Lot)
// Input variable required: input double MarginRequiredPerMicroLot =  
 200.0;

```mql5
//+-----------------------------------------------------------------
 -+
 //| Calculate Lot Size based on User Input Margin Parameter          |
 //+-----------------------------------------------------------------
 -+
 double CalculateLots() {
   // Ensure effective margin setting is valid (assuming
 g_effectiveMarginPerMicroLot is set from input)
   if(g_effectiveMarginPerMicroLot <= 0) {
      Print(__LINE__, ", Error: Effective MarginPerMicroLot is zero or
 negative (", g_effectiveMarginPerMicroLot, "). Cannot calculate
 lots.");
      return(0.0);
   }
   // Get account and symbol information
   double freeMargin = AccountFreeMargin();
   double minLot = MarketInfo(Symbol(), MODE_MINLOT);
   double maxLot = MarketInfo(Symbol(), MODE_MAXLOT);
   double lotStep = MarketInfo(Symbol(), MODE_LOTSTEP);
   // Validate symbol information
   if(minLot <= 0 || maxLot <= 0 || lotStep <= 0) {
      Print(__LINE__,", Error: Could not retrieve valid Symbol Lot Info
 (Min/Max/Step) for ", Symbol(), ". Min=", minLot, ", Max=", maxLot, ",
 Step=", lotStep);
      return(0.0);
   }
   if(freeMargin <= 0) {
      Print(__LINE__, ", Error: AccountFreeMargin is zero or negative (",
 freeMargin, "). Cannot calculate lots.");
      return(0.0);
   }
   // Calculate maximum possible lots based purely on free margin
 and the required margin per micro lot
   double calculatedLots = (freeMargin /
 g_effectiveMarginPerMicroLot) * 0.01;
   // Check if calculation resulted in a valid number
   if(calculatedLots <= 0) {
     Print(__LINE__, ", Initial lot calculation resulted in zero or negative
 lots (", calculatedLots, ") based on FreeMargin=", freeMargin, " and
 MarginPerMicro=", g_effectiveMarginPerMicroLot, ". Cannot trade.");
     return 0.0;
   }
   // Adjust for Lot Step (normalize down to the nearest valid step)
   calculatedLots = MathFloor(calculatedLots / lotStep) * lotStep;
   // Clamp between MinLot and MaxLot
   calculatedLots = MathMin(calculatedLots, maxLot); // Ensure not
 exceeding MaxLot
   calculatedLots = MathMax(calculatedLots, minLot); // Ensure not
 below MinLot
   // Final check: Does the adjusted lot size *still* fit within free
 margin?
   double marginRequired = (calculatedLots / 0.01) *
 g_effectiveMarginPerMicroLot;
   Print(__LINE__, ", Lot Calc: Initial Calc=",
 DoubleToString((freeMargin / g_effectiveMarginPerMicroLot) * 0.01,
 4), ", Stepped=", DoubleToString(MathFloor(calculatedLots / lotStep)
 * lotStep, 2), ", Clamped=", DoubleToString(calculatedLots, 2), ", Est.
 Margin Req=", DoubleToString(marginRequired, 2), ", Free Margin=",
 DoubleToString(freeMargin, 2));
   // Add a small buffer (e.g., 0.01 currency units) for safety margin
 check
   if(marginRequired > freeMargin + 0.01) {
     Print(__LINE__, ", Insufficient free margin (",
 DoubleToString(freeMargin,2), ") for final calculated lot size (",
 DoubleToString(calculatedLots,2), "). Estimated Required: ~",
 DoubleToString(marginRequired,2));
      // Try stepping down one more time if possible
      if(calculatedLots > minLot && calculatedLots >= lotStep * 2) { //
 Check if we can step down
        calculatedLots = MathFloor((calculatedLots - lotStep) / lotStep)
 * lotStep;
        calculatedLots = MathMax(calculatedLots, minLot); // Ensure
 still >= minLot
        marginRequired = (calculatedLots / 0.01) *
 g_effectiveMarginPerMicroLot;
        // Check margin again after stepping down
        if(marginRequired > freeMargin + 0.01) {
           Print(__LINE__, ", Still insufficient free margin even after
 stepping down to lots: ", calculatedLots);
           return(0.0); // Cannot trade
        } else {
           Print(__LINE__, ", Stepped down lot size due to margin
 constraints to: ", calculatedLots);
        }
      } else {
        // Cannot step down further (already at minLot or close to it)
        return(0.0); // Cannot trade
      }
   }
   // Return the final, validated lot size, normalized to 2 decimal places
 (standard for lots)
   return NormalizeDouble(calculatedLots, 2);
 }
```

---

### Trading Hours Filter
// Input variables required:  
 input bool EnableTradingHoursFilter = true; // Enable/disable the  
 trading hours filter  
 input int  TradingStartHour = 0;   // Trading start hour (0-23, Broker  
 Server Time)  
 input int  TradingEndHour   = 16;  // Trading end hour (0-23, Broker  
 Server Time) e.g. 16 allows up to 16:59  
 input bool AllowSundayTrading    = false; // Allow trading on Sunday  
 input bool AllowMondayTrading    = true;  // Allow trading on Monday  
 input bool AllowTuesdayTrading   = true;  // Allow trading on Tuesday  
 input bool AllowWednesdayTrading = true;  // Allow trading on  
 Wednesday  
 input bool AllowThursdayTrading  = true;  // Allow trading on  
 Thursday  
 input bool AllowFridayTrading    = true;  // Allow trading on Friday  
 input bool AllowSaturdayTrading  = false; // Allow trading on Saturday

```mql5
//+-----------------------------------------------------------------
 -+
 //| Check if current time is within allowed trading hours and days   |
 //+-----------------------------------------------------------------
 -+
 bool IsTradingHoursAllowed() {
   // --- Check if filter is enabled ---
   if (!EnableTradingHoursFilter) {
     return(true); // Filter disabled, always allow
   }
   // --- Get current time components (Broker Server Time) ---
   datetime serverTime = TimeCurrent();
   int currentHour = TimeHour(serverTime);
   int currentDayOfWeek = TimeDayOfWeek(serverTime); //
 0=Sunday, 1=Monday, ..., 6=Saturday
   // --- Check Day of Week ---
   bool dayAllowed = false;
   switch(currentDayOfWeek) {
     case 0: dayAllowed = AllowSundayTrading;    break;
     case 1: dayAllowed = AllowMondayTrading;    break;
     case 2: dayAllowed = AllowTuesdayTrading;   break;
     case 3: dayAllowed = AllowWednesdayTrading; break;
     case 4: dayAllowed = AllowThursdayTrading;  break;
     case 5: dayAllowed = AllowFridayTrading;    break;
     case 6: dayAllowed = AllowSaturdayTrading;  break;
   }
   if (!dayAllowed) {
     // Print(__LINE__, ", Trading Hours Check: DISALLOWED (Day ",
 currentDayOfWeek, ")"); // Optional debug
     return(false); // Trading not allowed on this day
   }
   // --- Check Hour of Day ---
   // Validate input hours (basic check)
   int startHour = MathMax(0, MathMin(23, TradingStartHour));
   int endHour   = MathMax(0, MathMin(23, TradingEndHour));
   bool hourAllowed = false;
   if (startHour == endHour) {
      // If start and end are the same, assume 24-hour trading is
 intended for allowed days
      hourAllowed = true;
   } else if (startHour < endHour) {
      // Normal case: Start hour is before end hour (e.g., 9 to 16
 includes hours 9 through 16)
      if (currentHour >= startHour && currentHour <= endHour) {
        hourAllowed = true;
      }
   } else { // startHour > endHour
      // Overnight case: Start hour is after end hour (e.g., 22 to 5
 includes 22, 23, 0, 1, 2, 3, 4, 5)
      if (currentHour >= startHour || currentHour <= endHour) {
        hourAllowed = true;
      }
   }
   // --- Optional Debug Print ---
   /*
   if (hourAllowed && dayAllowed) {
      Print(__LINE__, ", Trading Hours Check: Allowed. Day=",
 currentDayOfWeek, " Hour=", currentHour, ", Start=", startHour, ",
 End=", endHour);
   } else {
      Print(__LINE__, ", Trading Hours Check: DISALLOWED. Day=",
 currentDayOfWeek, " Hour=", currentHour, ", Start=", startHour, ",
 End=", endHour);
   }
   */
   return(hourAllowed); // Return true only if the hour is allowed (day
 was already checked)
 }
 (Note: The specific logic for the Friday close / Rollover avoidance
 mentioned previously would require enhancing the
 IsTradingHoursAllowed function or adding separate checks in
 OnTick.)
```

---

### Basic Candlestick Pattern Functions (Example: M1
Timeframe)

```mql5
//+-----------------------------------------------------------------
 -+
 //| Candlestick Pattern Functions (Example: PERIOD_M1)               |
 //+-----------------------------------------------------------------
 -+
 bool IsBullishEngulfing(int shift) {
   if(shift + 1 >= Bars(Symbol(), PERIOD_M1)) return false;
   double open_s = iOpen(Symbol(), PERIOD_M1, shift);
   double close_s = iClose(Symbol(), PERIOD_M1, shift);
   double open_s1 = iOpen(Symbol(), PERIOD_M1, shift+1);
   double close_s1 = iClose(Symbol(), PERIOD_M1, shift+1);
   // Current bar is bullish, prior is bearish, current body engulfs prior
 body
   if(close_s > open_s && close_s1 < open_s1 && close_s > open_s1
 && open_s < close_s1) { return true; }
   return false;
 }
 bool IsBearishEngulfing(int shift) {
   if(shift + 1 >= Bars(Symbol(), PERIOD_M1)) return false;
   double open_s = iOpen(Symbol(), PERIOD_M1, shift);
   double close_s = iClose(Symbol(), PERIOD_M1, shift);
   double open_s1 = iOpen(Symbol(), PERIOD_M1, shift+1);
   double close_s1 = iClose(Symbol(), PERIOD_M1, shift+1);
   // Current bar is bearish, prior is bullish, current body engulfs prior
 body
   if(close_s < open_s && close_s1 > open_s1 && close_s < open_s1
 && open_s > close_s1) { return true; }
   return false;
 }
 bool IsHarami(int shift) {
   if(shift + 1 >= Bars(Symbol(), PERIOD_M1)) return false;
   double high_s = iHigh(Symbol(), PERIOD_M1, shift);
   double low_s = iLow(Symbol(), PERIOD_M1, shift);
   double high_s1 = iHigh(Symbol(), PERIOD_M1, shift+1);
   double low_s1 = iLow(Symbol(), PERIOD_M1, shift+1);
   // Current bar's high/low is contained within prior bar's high/low
   if(high_s < high_s1 && low_s > low_s1) { return true; }
   return false;
 }
 bool IsHammer(int shift) {
   if(shift >= Bars(Symbol(), PERIOD_M1)) return false;
   double open_s = iOpen(Symbol(), PERIOD_M1, shift);
   double close_s = iClose(Symbol(), PERIOD_M1, shift);
   double high_s = iHigh(Symbol(), PERIOD_M1, shift);
   double low_s = iLow(Symbol(), PERIOD_M1, shift);
   double bodySize = MathAbs(open_s - close_s);
   double lowerWick = MathMin(open_s, close_s) - low_s;
   double upperWick = high_s - MathMax(open_s, close_s);
   double candleRange = high_s - low_s;
   // Small body, long lower wick, short upper wick, bullish close (can
 relax this)
   if(candleRange > Point * 2 && bodySize > Point && bodySize <
 candleRange * 0.34 && lowerWick > bodySize * 2.0 && upperWick <
 bodySize * 0.7 /*&& (close_s > open_s)*/) { return true; }
   return false;
 }
 bool IsShootingStar(int shift) {
   if(shift >= Bars(Symbol(), PERIOD_M1)) return false;
   double open_s = iOpen(Symbol(), PERIOD_M1, shift);
   double close_s = iClose(Symbol(), PERIOD_M1, shift);
   double high_s = iHigh(Symbol(), PERIOD_M1, shift);
   double low_s = iLow(Symbol(), PERIOD_M1, shift);
   double bodySize = MathAbs(open_s - close_s);
   double lowerWick = MathMin(open_s, close_s) - low_s;
   double upperWick = high_s - MathMax(open_s, close_s);
   double candleRange = high_s - low_s;
   // Small body, long upper wick, short lower wick, bearish close (can
 relax this)
   if(candleRange > Point * 2 && bodySize > Point && bodySize <
 candleRange * 0.34 && upperWick > bodySize * 2.0 && lowerWick <
 bodySize * 0.7 /*&& (close_s < open_s)*/) { return true; }
   return false;
 }
```

---

### Slow Down Strategy Tester
// Input variables required:  
 extern int InTradeVisualSpeed = 10000000; // Adjust default as  
 needed  
 extern int OutOfTradeTesterThrottleSpeed = 10000000; // Adjust  
 default as needed  
 // Global variable required: extern int TicketNumber = -1; (or however  
 you track open trades)

```mql5
//+-----------------------------------------------------------------
 -+
 //| Slows down visual backtesting by busy-waiting.                   |
 //+-----------------------------------------------------------------
 -+
 void SlowDownStrategyTester() {
   if(IsVisualMode() && !IsOptimization()) {
      int i = 0;
      // Check if a trade is open (using your EA's method, TicketNumber
 > 0 is assumed here)
      if(TicketNumber > 0) {
        // Use in-trade speed setting
         if(InTradeVisualSpeed > 0) {
            for(i = InTradeVisualSpeed; i > 0; i--) {} // Empty loop to waste
 time
         }
       } else {
         // Use out-of-trade speed setting
         if(OutOfTradeTesterThrottleSpeed > 0) {
            for(i = OutOfTradeTesterThrottleSpeed; i > 0; i--) {} // Empty
 loop to waste time
         }
       }
    }
 }
```

---

### Example Magic Number Generator:
```mql5
//+-----------------------------------------------------------------
 -+
 //| Provides unique EA identifier to the trades          |
 //+-----------------------------------------------------------------
 -+ 
 /*
 int GenerateMagicNumber(int baseNumber) {
   string symbol = Symbol();
   int symbolValue = 0;
   for(int i = 0; i < StringLen(symbol); i++) {
      symbolValue += StringGetChar(symbol, i);
   }
   long magicNumberLong = (long)baseNumber * 10007 +  symbolValue;
   int magicNumber = (int)(MathAbs(magicNumberLong) %  2147483647);
   if(magicNumber == 0) {
      magicNumber = 1234; // Avoid 0 as magic number
   }
   return(magicNumber);
 }
 */
```

---

