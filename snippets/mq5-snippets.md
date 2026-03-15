# mq5-snippets

### highestArrayMT5
MT5: Finds the highest value in the array.

```mql5
int highestIndex = ArrayMaximum(array, start, count);
double highest = array[highestIndex];
```

---

### lowestArrayMT5
MT5: Finds the lowest value in the array.

```mql5
int lowestIndex = ArrayMinimum(array, start, count);
double lowest = array[lowestIndex];
```

---

### iMACDMT5
MT5: iMACD.

```mql5
iMACD(_Symbol, _Period, fast_ema_period, slow_ema_period, signal_period, ${6|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### iStochasticMT5
MT5: iStochastic.

```mql5
iStochastic(_Symbol, _Period, Kperiod, Dperiod, slowing, |MODE_SMA,MODE_EMA,MODE_SMMA,MODE_LWMA|, ${7|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### iMAMT5
MT5: iMA.

```mql5
iMA(_Symbol, _Period, ma_period, ma_shift, ${5|MODE_SMA,MODE_EMA,MODE_SMMA,MODE_LWMA|}, ${6|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### iEnvelopesMT5
MT5: iEnvelopes.

```mql5
iEnvelopes(_Symbol, _Period, ma_period, ma_shift, ${5|MODE_SMA,MODE_EMA,MODE_SMMA,MODE_LWMA|}, ${6|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|}, deviation);
```

---

### IndicatorRelease
MT5: Releases indicator handler

```mql5
IndicatorRelease(indicator_handle);
```

---

### maOnArrayMT5
MT5: switch statement for a price

```mql5
#include <MovingAverages.mqh>
void MAOnArray(const int rates_total, const int prev_calculated, int sourceFirst, ENUM_MA_METHOD method, int period, double& in[], double& out[])
{
   if (period == 1)
   {
      for (int pos = sourceFirst; pos < rates_total; ++pos)
      {
         out[pos] = in[pos];
      }
      return;
   }
   int weightsum;
   switch (method)
   {
      case MODE_SMA:
         SimpleMAOnBuffer(rates_total, prev_calculated, sourceFirst, period, in, out);
         break;
      case MODE_EMA:
         ExponentialMAOnBuffer(rates_total, prev_calculated, sourceFirst, period, in, out);
         break;
      case MODE_SMMA:
         SmoothedMAOnBuffer(rates_total, prev_calculated, sourceFirst, period, in, out);
         break;
      case MODE_LWMA:
         LinearWeightedMAOnBuffer(rates_total, prev_calculated, sourceFirst, period, in, out, weightsum);
         break;
   }
}
```

---

### switchPriceMT5
MT5: switch statement for a price

```mql5
switch (priceType)
{
   case PRICE_CLOSE:
      break;
   case PRICE_OPEN:
      break;
   case PRICE_HIGH:
      break;
   case PRICE_LOW:
      break;
   case PRICE_MEDIAN:
      break;
   case PRICE_TYPICAL:
      break;
   case PRICE_WEIGHTED:
      break;
}
```

---

### propStreamMT5
MT5: Stream properties

```mql5
#property indicator_type1  ${2|DRAW_NONE,DRAW_LINE,DRAW_SECTION,DRAW_HISTOGRAM,DRAW_HISTOGRAM2,DRAW_ARROW,DRAW_ZIGZAG,DRAW_FILLING,DRAW_BARS,DRAW_CANDLES,DRAW_COLOR_LINE,DRAW_COLOR_SECTION,DRAW_COLOR_HISTOGRAM,DRAW_COLOR_HISTOGRAM2,DRAW_COLOR_ARROW,DRAW_COLOR_ZIGZAG,DRAW_COLOR_BARS,DRAW_COLOR_CANDLES|}
#property indicator_color1 RoyalBlue
#property indicator_width1 1
#property indicator_style1 ${5|STYLE_SOLID,STYLE_DASH,STYLE_DOT,STYLE_DASHDOT,STYLE_DASHDOTDOT|}
#property indicator_label1 "Name"
```

---

### inputPriceMT5
MT5: Input of a price

```mql5
input ENUM_APPLIED_PRICE price = ${2|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|}; // Price type
```

---

### OrderGetStringMT5
MT5: OrderGetString()

```mql5
OrderGetString(${1|ORDER_SYMBOL,ORDER_COMMENT,ORDER_EXTERNAL_ID|})
```

---

### AccountInfoDoubleMT5
MT5: AccountInfoDouble()

```mql5
AccountInfoDouble(${1|ACCOUNT_BALANCE,ACCOUNT_CREDIT,ACCOUNT_PROFIT,ACCOUNT_EQUITY,ACCOUNT_MARGIN,ACCOUNT_MARGIN_FREE,ACCOUNT_MARGIN_LEVEL.ACCOUNT_MARGIN_SO_CALL,ACCOUNT_MARGIN_SO_SO,ACCOUNT_MARGIN_INITIAL,ACCOUNT_MARGIN_MAINTENANCE,ACCOUNT_ASSETS,ACCOUNT_LIABILITIES,ACCOUNT_COMMISSION_BLOCKED|})
```

---

### AccountInfoStringMT5
MT5: AccountInfoString()

```mql5
AccountInfoString(${1|ACCOUNT_NAME,ACCOUNT_SERVER,ACCOUNT_CURRENCY,ACCOUNT_COMPANY|})
```

---

### AccountCompanyMT5
MT5: AccountCompany()

```mql5
AccountInfoString(ACCOUNT_COMPANY)
```

---

### AccountServerMT5
MT5: AccountServer()

```mql5
AccountInfoString(ACCOUNT_SERVER)
```

---

### AccountNameMT5
MT5: AccountName()

```mql5
AccountInfoString(ACCOUNT_NAME)
```

---

### AccountNumberMT5
MT5: AccountNumber()

```mql5
AccountInfoInteger(ACCOUNT_LOGIN)
```

---

### AccountLeverageMT5
MT5: AccountLeverage()

```mql5
AccountInfoInteger(ACCOUNT_LEVERAGE)
```

---

### AccountInfoIntegerMT5
MT5: AccountInfoInteger()

```mql5
AccountInfoInteger(${1|ACCOUNT_LOGIN,ACCOUNT_TRADE_MODE,ACCOUNT_LEVERAGE,ACCOUNT_LIMIT_ORDERS,ACCOUNT_MARGIN_SO_MODE,ACCOUNT_TRADE_ALLOWED,ACCOUNT_TRADE_EXPERT,ACCOUNT_MARGIN_MODE,ACCOUNT_CURRENCY_DIGITS,ACCOUNT_FIFO_CLOSE|})
```

---

### SymbolInfoDoubleMT5
MT5: SymbolInfoDouble()

```mql5
SymbolInfoDouble(Symbol(), ${2|SYMBOL_BID,SYMBOL_BIDHIGH,SYMBOL_BIDLOW,SYMBOL_ASK,SYMBOL_ASKHIGH,SYMBOL_ASKLOW,SYMBOL_LAST,SYMBOL_LASTHIGH,SYMBOL_LASTLOW,SYMBOL_VOLUME_REAL,SYMBOL_VOLUMEHIGH_REAL,SYMBOL_VOLUMELOW_REAL,SYMBOL_OPTION_STRIKE,SYMBOL_POINT,SYMBOL_TRADE_TICK_VALUE,SYMBOL_TRADE_TICK_VALUE_PROFIT,SYMBOL_TRADE_TICK_VALUE_LOSS,SYMBOL_TRADE_TICK_SIZE,SYMBOL_TRADE_CONTRACT_SIZE,SYMBOL_TRADE_ACCRUED_INTEREST,SYMBOL_TRADE_FACE_VALUE,SYMBOL_TRADE_LIQUIDITY_RATE,SYMBOL_VOLUME_MIN,SYMBOL_VOLUME_MAX,SYMBOL_VOLUME_STEP,SYMBOL_VOLUME_LIMIT,SYMBOL_SWAP_LONG,SYMBOL_SWAP_SHORT,SYMBOL_MARGIN_INITIAL,SYMBOL_MARGIN_MAINTENANCE,SYMBOL_SESSION_VOLUME,SYMBOL_SESSION_TURNOVER,SYMBOL_SESSION_INTEREST,SYMBOL_SESSION_BUY_ORDERS_VOLUME,SYMBOL_SESSION_SELL_ORDERS_VOLUME,SYMBOL_SESSION_OPEN,SYMBOL_SESSION_CLOSE,SYMBOL_SESSION_AW,SYMBOL_SESSION_PRICE_SETTLEMENT,SYMBOL_SESSION_PRICE_LIMIT_MIN,SYMBOL_SESSION_PRICE_LIMIT_MAX,SYMBOL_MARGIN_HEDGED,SYMBOL_PRICE_CHANGE,SYMBOL_PRICE_VOLATILITY,SYMBOL_PRICE_THEORETICAL,SYMBOL_PRICE_DELTA,SYMBOL_PRICE_THETA,SYMBOL_PRICE_GAMMA,SYMBOL_PRICE_VEGA,SYMBOL_PRICE_RHO,SYMBOL_PRICE_OMEGA,SYMBOL_PRICE_SENSITIVITY|})
```

---

### SymbolInfoIntegerMT5
MT5: SymbolInfoInteger()

```mql5
SymbolInfoInteger(Symbol(), ${2|SYMBOL_SECTOR,SYMBOL_INDUSTRY,SYMBOL_CUSTOM,SYMBOL_BACKGROUND_COLOR,SYMBOL_CHART_MODE,SYMBOL_EXIST,SYMBOL_SELECT,SYMBOL_VISIBLE,SYMBOL_SESSION_DEALS,SYMBOL_SESSION_BUY_ORDERS,SYMBOL_SESSION_SELL_ORDERS,SYMBOL_VOLUME,SYMBOL_VOLUMEHIGH,SYMBOL_VOLUMELOW,SYMBOL_TIME,SYMBOL_TIME_MSC,SYMBOL_DIGITS,SYMBOL_SPREAD_FLOAT,SYMBOL_SPREAD,SYMBOL_TICKS_BOOKDEPTH,SYMBOL_TRADE_CALC_MODE,SYMBOL_TRADE_MODE,SYMBOL_EXPIRATION_TIME,SYMBOL_TRADE_STOPS_LEVEL,SYMBOL_TRADE_FREEZE_LEVEL,SYMBOL_TRADE_EXEMODE,SYMBOL_SWAP_MODE,SYMBOL_SWAP_ROLLOVER3DAYS,SYMBOL_MARGIN_HEDGED_USE_LEG,SYMBOL_EXPIRATION_MODE,SYMBOL_FILLING_MODE,SYMBOL_ORDER_MODE,SYMBOL_ORDER_GTC_MODE,SYMBOL_OPTION_MODE,SYMBOL_OPTION_RIGHT|})
```

---

### OrderGetDoubleMT5
MT5: OrderGetDouble()

```mql5
OrderGetDouble(${1|ORDER_VOLUME_INITIAL,ORDER_VOLUME_CURRENT,ORDER_PRICE_OPEN,ORDER_SL,ORDER_TP,ORDER_PRICE_CURRENT,ORDER_PRICE_STOPLIMIT|})
```

---

### HistoryDealGetStringMT5
MT5: HistoryDealGetString()

```mql5
HistoryDealGetString(ticketId, ${2|DEAL_SYMBOL,DEAL_COMMENT,DEAL_EXTERNAL_ID|})
```

---

### HistoryDealGetIntegerMT5
MT5: HistoryDealGetInteger()

```mql5
HistoryDealGetInteger(ticketId, ${2|DEAL_TICKET,DEAL_ORDER,DEAL_TIME,DEAL_TIME_MSC,DEAL_TYPE,DEAL_ENTRY,DEAL_MAGIC,DEAL_REASON,DEAL_POSITION_ID|})
```

---

### HistoryDealGetDoubleMT5
MT5: HistoryDealGetDouble()

```mql5
HistoryDealGetDouble(ticketId, ${2|DEAL_VOLUME,DEAL_PRICE,DEAL_COMMISSION,DEAL_SWAP,DEAL_PROFIT,DEAL_FEE|})
```

---

### OrderGetIntegerMT5
MT5: OrderGetInteger()

```mql5
OrderGetInteger(${1|ORDER_TICKET,ORDER_TIME_SETUP,ORDER_TYPE,ORDER_STATE,ORDER_TIME_EXPIRATION,ORDER_TIME_DONE,ORDER_TIME_SETUP_MSC,ORDER_TIME_DONE_MSC,ORDER_TYPE_FILLING,ORDER_TYPE_TIME,ORDER_MAGIC,ORDER_REASON,ORDER_POSITION_ID,ORDER_POSITION_BY_ID|})
```

---

### PositionGetStringMT5
MT5: PositionGetString()

```mql5
PositionGetString(${1|POSITION_SYMBOL,POSITION_COMMENT,POSITION_EXTERNAL_ID|})
```

---

### PositionGetDoubleMT5
MT5: PositionGetDouble()

```mql5
PositionGetDouble(${1|POSITION_VOLUME,POSITION_PRICE_OPEN,POSITION_SL,POSITION_TP,POSITION_PRICE_CURRENT,POSITION_SWAP,POSITION_PROFIT|})
```

---

### PositionGetIntegerMT5
MT5: PositionGetInteger()

```mql5
PositionGetInteger(${1|POSITION_TICKET,POSITION_TIME,POSITION_TIME_MSC,POSITION_TIME_UPDATE,POSITION_TIME_UPDATE_MSC,POSITION_TYPE,POSITION_MAGIC,POSITION_IDENTIFIER,POSITION_REASON|})
```

---

### IndicatorReleaseClipboard
MT5: Releases indicator handler

```mql5
IndicatorRelease(${CLIPBOARD:indicator_handle});
```

---

### pipSizeMT5
MT5: Get pip size

```mql5
double point = SymbolInfoDouble(_Symbol, SYMBOL_POINT);
int digit = (int)SymbolInfoInteger(_Symbol, SYMBOL_DIGITS);
int mult = digit == 3 || digit == 5 ? 10 : 1;
double pipSize = point * mult;
```

---

### CustomIndicatorMT5
MT5: Create custom indicator

```mql5
handle = iCustom(_Symbol, _Period, "::Indicators\\\\indicatorName", params);
```

---

### stochasticMT5
MT5: Create stochastic indicator

```mql5
handle = iStochastic(_Symbol, _Period, stoch_k, stoch_d, stoch_slowing, ${7|MODE_SMA,MODE_EMA,MODE_SMMA,MODE_LWMA|}, ${8|STO_LOWHIGH,STO_CLOSECLOSE|});
```

---

### adxMT5
MT5: iADX

```mql5
handle = iADX(_Symbol, _Period, adx_period);
```

---

### demarkerMT5
MT5: iDeMarker

```mql5
handle = iDeMarker(_Symbol, _Period, demarker_period);
```

---

### adMT5
MT5: iAD

```mql5
handle = iAD(_Symbol, _Period, ${4|VOLUME_TICK,VOLUME_REAL|});
```

---

### rsiMT5
MT5: iRSI

```mql5
handle = iRSI(_Symbol, _Period, rsi_period, ${5|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### ichimokuMT5
MT5: iIchimoku

```mql5
handle = iIchimoku(_Symbol, _Period, tenkan_sen, kijun_sen, senkou_span_b);
```

---

### bandsMT5
MT5: iBands

```mql5
handle = iBands(_Symbol, _Period, bb_period, bb_shift, bb_deviation, ${7|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### macdMT5
MT5: iMACD

```mql5
handle = iMACD(_Symbol, _Period, fast_ema_period, slow_ema_period, signal_period, ${7|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### momentumMT5
MT5: iMomentum

```mql5
handle = iMomentum(_Symbol, _Period, mom_period, ${5|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### cciMT5
MT5: iCCI

```mql5
handle = iCCI(_Symbol, _Period, ma_period, ${5|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### averagesMT5
MT5: Value of averages indicator

```mql5
hande = iMA(_Symbol, _Period, ma_period, ma_shift, ${6|MODE_SMA,MODE_EMA,MODE_SMMA,MODE_LWMA|}, ${7|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### stdevMT5
MT5: StDev function

```mql5
double StDev(double& data[], int period, int pos)
{
   return MathSqrt(Variance(data, period, pos));
}
double Variance(double& data[], int period, int pos)
{
   double sum = 0;
   double ssum = 0;
   for (int i = 0; i < period; i++)
   {
      sum += data[pos - i];
      ssum += MathPow(data[pos - i], 2);
   }
   return (ssum * period - sum * sum) / (period * (period - 1));
}
```

---

### atrMT5
MT5: Create ATR indicator

```mql5
handle = iATR(_Symbol, _Period, length);
```

---

### sarMT5
MT5: Create PSAR indicator

```mql5
handle = iSAR(_Symbol, _Period, step, maximum);
```

---

### wprMT5
MT5: Create WPR indicator

```mql5
handle = iWPR(_Symbol, _Period, calc_period);
```

---

### osmaMT5
MT5: Create OsMA indicator

```mql5
handle = iOsMA(_Symbol, _Period, fast_ema_period, slow_ema_period, signal_period, ${7|PRICE_CLOSE,PRICE_OPEN,PRICE_HIGH,PRICE_LOW,PRICE_MEDIAN,PRICE_TYPICAL,PRICE_WEIGHTED|});
```

---

### StochasticOutput
MT5:Stochastic output lookup

```mql5
${1|MAIN_LINE,SIGNAL_LINE|}
```

---

### CopyBuffer
MT5: Copy indicator's buffer

```mql5
double buffer[count];
if (CopyBuffer(indicator_handle, buffer_num, rates_total - 1 - pos, count, buffer) ${6|==,!=|} count)
{
}
```

---

### OnCalculateMT5
MT5: OnCalculate function

```mql5
int OnCalculate(const int rates_total,       // size of input time series
                const int prev_calculated,   // number of handled bars at the previous call
                const datetime& time[],      // Time array
                const double& open[],        // Open array
                const double& high[],        // High array
                const double& low[],         // Low array
                const double& close[],       // Close array
                const long& tick_volume[],   // Tick Volume array
                const long& volume[],        // Real Volume array
                const int& spread[]          // Spread array
)
{
   if (prev_calculated <= 0 || prev_calculated > rates_total)
   {
      //ArrayInitialize(out, EMPTY_VALUE);
   }
   int first = 0;
   for (int pos = MathMax(first, prev_calculated - 1); pos < rates_total; ++pos)
   {
      int oldPos = rates_total - pos - 1;
   }
   return rates_total;
}
```

---

### OnInitMT5
MT5: OnInit function

```mql5
string IndicatorObjPrefix;
bool NamesCollision(const string name)
{
   for (int k = ObjectsTotal(0); k >= 0; k--)
   {
      if (StringFind(ObjectName(0, k), name) == 0)
      {
         return true;
      }
   }
   return false;
}
string GenerateIndicatorPrefix(const string target)
{
   for (int i = 0; i < 1000; ++i)
   {
      string prefix = target + "_" + IntegerToString(i);
      if (!NamesCollision(prefix))
      {
         return prefix;
      }
   }
   return target;
}
int OnInit(void)
{
   IndicatorObjPrefix = GenerateIndicatorPrefix("id");
   IndicatorSetString(INDICATOR_SHORTNAME, "name");
   IndicatorSetInteger(INDICATOR_DIGITS, Digits());
}
```

---

### OnDeinitMT5
MT5: OnDeinit function

```mql5
void OnDeinit(const int reason)
{
   ObjectsDeleteAll(0, IndicatorObjPrefix);
}
```

---

### OnTickMT5
MT5: OnTick function

```mql5
void OnTick()
{
}
```

---

### ObjectSetTextMT5
MT5: ObjectSetText function similar to MT4

```mql5
void ObjectSetText(string id, string text, int fontSize, string font, color clr)
{
   ObjectSetString(0, id, OBJPROP_TEXT, text);
   ObjectSetString(0, id, OBJPROP_FONT, font);
   ObjectSetInteger(0, id, OBJPROP_FONTSIZE, fontSize);
   ObjectSetInteger(0, id, OBJPROP_COLOR, clr);
}
```

---

### PlotIndexSetInteger
MT5: PlotIndexSetInteger

```mql5
PlotIndexSetInteger(id, ${2|PLOT_ARROW,PLOT_ARROW_SHIFT,PLOT_DRAW_BEGIN,PLOT_DRAW_TYPE,PLOT_SHOW_DATA,PLOT_SHIFT,PLOT_LINE_STYLE,PLOT_LINE_WIDTH,PLOT_COLOR_INDEXES,PLOT_LINE_COLOR|}, value);
```

---

### GetSpreadMT5
MT5: GetSpread

```mql5
double spread = SymbolInfoInteger(_Symbol, SYMBOL_SPREAD);
```

---

### enumDrawType
MT5: Lookup PLOT_DRAW_TYPE value

```mql5
${1|DRAW_NONE,DRAW_LINE,DRAW_SECTION,DRAW_HISTOGRAM,DRAW_HISTOGRAM2,DRAW_ARROW,DRAW_ZIGZAG,DRAW_FILLING,DRAW_BARS,DRAW_CANDLES,DRAW_COLOR_LINE,DRAW_COLOR_SECTION,DRAW_COLOR_HISTOGRAM,DRAW_COLOR_HISTOGRAM2,DRAW_COLOR_ARROW,DRAW_COLOR_ZIGZAG,DRAW_COLOR_BARS,DRAW_COLOR_CANDLES|}
```

---

### createTextObjectMT5
MT5: Create OBJ_TEXT

```mql5
string id = IndicatorObjPrefix + "textId";
if (ObjectFind(chart_ID, id) == -1)
{
   if (ObjectCreate(chart_ID, id, OBJ_TEXT, sub_window, time, price))
   {
      ObjectSetString(chart_ID, id, OBJPROP_FONT, font);
      ObjectSetInteger(chart_ID, id, OBJPROP_FONTSIZE, font_size);
      ObjectSetInteger(chart_ID, id, OBJPROP_COLOR, clr);
      ObjectSetDouble(chart_ID, id, OBJPROP_ANGLE, angle);
      ObjectSetInteger(chart_ID, id, OBJPROP_ANCHOR, ${12|ANCHOR_LEFT_UPPER,ANCHOR_LEFT,ANCHOR_LEFT_LOWER,ANCHOR_LOWER,ANCHOR_RIGHT_LOWER,ANCHOR_RIGHT,ANCHOR_RIGHT_UPPER,ANCHOR_UPPER,ANCHOR_CENTER|});
      ObjectSetInteger(chart_ID, id, OBJPROP_BACK, back);
      ObjectSetInteger(chart_ID, id, OBJPROP_SELECTABLE, selection);
      ObjectSetInteger(chart_ID, id, OBJPROP_SELECTED, selection);
      ObjectSetInteger(chart_ID, id, OBJPROP_HIDDEN, hidden);
      ObjectSetInteger(chart_ID, id, OBJPROP_ZORDER, z_order);
   }
}
ObjectSetString(chart_ID, id, OBJPROP_TEXT, text);
```

---

### createRectangleObjectMT5
MT5: Create OBJ_RECTANGLE

```mql5
string id = IndicatorObjPrefix + "textId";
if (ObjectFind(chart_ID, id) == -1)
{
   if (ObjectCreate(chart_ID, id, OBJ_RECTANGLE, sub_window, time1, price1, time2, price2))
   {
      ObjectSetInteger(chart_ID, id, OBJPROP_COLOR, clr);
      ObjectSetInteger(chart_ID, id, OBJPROP_STYLE, style);
      ObjectSetInteger(chart_ID, id, OBJPROP_WIDTH, width);
      ObjectSetInteger(chart_ID, id, OBJPROP_FILL, fill);
      ObjectSetInteger(chart_ID, id, OBJPROP_BACK, back);
      ObjectSetInteger(chart_ID, id, OBJPROP_SELECTABLE, selection);
      ObjectSetInteger(chart_ID, id, OBJPROP_SELECTED, selection);
      ObjectSetInteger(chart_ID, id, OBJPROP_HIDDEN, hidden);
      ObjectSetInteger(chart_ID, id, OBJPROP_ZORDER, z_order);
   }
}
ObjectSetInteger(chart_ID, id, OBJPROP_TIME, 0, time1);
ObjectSetDouble(chart_ID, id, OBJPROP_PRICE, 0, price1);
ObjectSetInteger(chart_ID, id, OBJPROP_TIME, 1, time2);
ObjectSetDouble(chart_ID, id, OBJPROP_PRICE, 1, price2);
```

---

### createRectangleLabelMT5
MT5: Create OBJ_RECTANGLE_LABEL

```mql5
string id = IndicatorObjPrefix + "textId";
if (ObjectFind(chart_ID, id) == -1)
{
   if (ObjectCreate(chart_ID, id, OBJ_RECTANGLE_LABEL, sub_window, 0, 0))
   {
         ObjectSetInteger(chart_ID, id, OBJPROP_BGCOLOR, back_clr);
         ObjectSetInteger(chart_ID, id, OBJPROP_BORDER_TYPE, border);
         ObjectSetInteger(chart_ID, id, OBJPROP_CORNER, corner);
         ObjectSetInteger(chart_ID, id, OBJPROP_COLOR, clr);
         ObjectSetInteger(chart_ID, id, OBJPROP_STYLE, style);
         ObjectSetInteger(chart_ID, id, OBJPROP_WIDTH, line_width);
         ObjectSetInteger(chart_ID, id, OBJPROP_BACK, back);
         ObjectSetInteger(chart_ID, id, OBJPROP_SELECTABLE, selection);
         ObjectSetInteger(chart_ID, id, OBJPROP_SELECTED, selection);
         ObjectSetInteger(chart_ID, id, OBJPROP_HIDDEN, hidden);
         ObjectSetInteger(chart_ID, id, OBJPROP_ZORDER, z_order);
   }
}
ObjectSetInteger(chart_ID, id, OBJPROP_XDISTANCE, x);
ObjectSetInteger(chart_ID, id, OBJPROP_YDISTANCE, y);
ObjectSetInteger(chart_ID, id, OBJPROP_XSIZE, width);
ObjectSetInteger(chart_ID, id, OBJPROP_YSIZE, height);
```

---

### createTrendObjectMT5
MT5: Create OBJ_TREND

```mql5
string id = IndicatorObjPrefix + "textId";
if (ObjectFind(chart_ID, id) == -1)
{
   if (ObjectCreate(chart_ID, id, OBJ_TREND, sub_window, time1, price1, time2, price2))
   {
      ObjectSetInteger(chart_ID, id, OBJPROP_COLOR, clr);
      ObjectSetInteger(chart_ID, id, OBJPROP_STYLE, style);
      ObjectSetInteger(chart_ID, id, OBJPROP_WIDTH, width);
      ObjectSetInteger(chart_ID, id, OBJPROP_BACK, back);
      ObjectSetInteger(chart_ID, id, OBJPROP_SELECTABLE, selection);
      ObjectSetInteger(chart_ID, id, OBJPROP_SELECTED, selection);
      ObjectSetInteger(chart_ID, id, OBJPROP_RAY_LEFT, ray_left);
      ObjectSetInteger(chart_ID, id, OBJPROP_RAY_RIGHT, ray_right);
      ObjectSetInteger(chart_ID, id, OBJPROP_HIDDEN, hidden);
      ObjectSetInteger(chart_ID, id, OBJPROP_ZORDER, z_order);
   }
}
ObjectSetInteger(chart_ID, id, OBJPROP_TIME, 0, time1);
ObjectSetDouble(chart_ID, id, OBJPROP_PRICE, 0, price1);
ObjectSetInteger(chart_ID, id, OBJPROP_TIME, 1, time2);
ObjectSetDouble(chart_ID, id, OBJPROP_PRICE, 1, price2);
```

---

### createStreamMT5
MT5: Create output stream

```mql5
SetIndexBuffer(id, stream, INDICATOR_DATA);
PlotIndexSetInteger(id, PLOT_DRAW_TYPE, ${3|DRAW_NONE,DRAW_LINE,DRAW_SECTION,DRAW_HISTOGRAM,DRAW_HISTOGRAM2,DRAW_ARROW,DRAW_ZIGZAG,DRAW_FILLING,DRAW_BARS,DRAW_CANDLES,DRAW_COLOR_LINE,DRAW_COLOR_SECTION,DRAW_COLOR_HISTOGRAM,DRAW_COLOR_HISTOGRAM2,DRAW_COLOR_ARROW,DRAW_COLOR_ZIGZAG,DRAW_COLOR_BARS,DRAW_COLOR_CANDLES|});
PlotIndexSetInteger(id, PLOT_LINE_COLOR, clr);
PlotIndexSetString(id, PLOT_LABEL, name);
```

---

### createColorStreamMT5
MT5: Create color stream

```mql5
SetIndexBuffer(id, stream, INDICATOR_COLOR_INDEX);
```

---

### createInternalStreamMT5
MT5: Create internal stream

```mql5
SetIndexBuffer(id, stream, INDICATOR_CALCULATIONS);
```

---

### createArrowStreamMT5
MT5: Create arrow stream

```mql5
SetIndexBuffer(id, buffer, INDICATOR_DATA);
PlotIndexSetInteger(id, PLOT_DRAW_TYPE, DRAW_ARROW);
PlotIndexSetInteger(id, PLOT_ARROW, code);
PlotIndexSetInteger(id, PLOT_ARROW_SHIFT, 5);
```

---

### bidMT5
MT5: Get bid price

```mql5
SymbolInfoDouble(Symbol(), SYMBOL_BID)
```

---

### askMT5
MT5: Get ask price

```mql5
SymbolInfoDouble(Symbol(), SYMBOL_ASK)
```

---

### trialMT5
MT5: Trial check

```mql5
if (TimeCurrent() >= D'2022.01.01')
{
   Comment("You run out of trial period. Please contact your@email.com");
   return 0;
}
```

---

### ObjectSetIntegerMT5
MT5: Set int property for an onject

```mql5
ObjectSetInteger(chart_id, name, ${3|OBJPROP_COLOR,OBJPROP_STYLE,OBJPROP_WIDTH,OBJPROP_BACK,OBJPROP_ZORDER,OBJPROP_FILL,OBJPROP_HIDDEN,OBJPROP_SELECTED,OBJPROP_READONLY,OBJPROP_TYPE,OBJPROP_TIME,OBJPROP_SELECTABLE,OBJPROP_CREATETIME,OBJPROP_LEVELS,OBJPROP_LEVELCOLOR,OBJPROP_LEVELSTYLE,OBJPROP_LEVELWIDTH,OBJPROP_ALIGN,OBJPROP_FONTSIZE,OBJPROP_RAY_LEFT,OBJPROP_RAY_RIGHT,OBJPROP_RAY,OBJPROP_ELLIPSE,OBJPROP_ARROWCODE,OBJPROP_TIMEFRAMES,OBJPROP_ANCHOR,OBJPROP_XDISTANCE,OBJPROP_YDISTANCE,OBJPROP_DIRECTION,OBJPROP_DEGREE,OBJPROP_DRAWLINES,OBJPROP_STATE,OBJPROP_CHART_ID,OBJPROP_XSIZE,OBJPROP_YSIZE,OBJPROP_XOFFSET,OBJPROP_YOFFSET,OBJPROP_PERIOD,OBJPROP_DATE_SCALE,OBJPROP_PRICE_SCALE,OBJPROP_CHART_SCALE,OBJPROP_BGCOLOR,OBJPROP_CORNER,OBJPROP_BORDER_TYPE,OBJPROP_BORDER_COLOR|}, prop_value)
```

---

### ObjectSetDoubleMT5
MT5: Set double property for an onject

```mql5
ObjectSetInteger(chart_id, name, ${3|OBJPROP_PRICE,OBJPROP_LEVELVALUE,OBJPROP_SCALE,OBJPROP_ANGLE,OBJPROP_DEVIATION|}, prop_value)
```

---

