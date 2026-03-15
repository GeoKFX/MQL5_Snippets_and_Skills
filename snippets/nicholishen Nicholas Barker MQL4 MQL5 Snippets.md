# MQL4/MQL5 Codebase: -nicholishen Nicholas Barker MQL4 MQL5 Snippets (7)

### datetime
```mql5
datetime
```

---

### color
```mql5
color
```

---

### ulong
```mql5
ulong
```

---

### ushort
```mql5
ushort
```

---

### uchar
```mql5
uchar
```

---

### uint
```mql5
uint
```

---

### string
```mql5
string
```

---

### NULL
```mql5
NULL
```

---

### include
*preprocessor include directive*

```mql5
#include <file_name.mqh>
```

---

### dynamic_cast
*Dynamic typecasting is performed using dynamic_cast operator that can be applied only to pointers to classes. Type validation is performed at runtime. This means that the compiler does not check the data type applied for typecasting when dynamic_cast operator is used. If a pointer is converted to a data type which is not the actual type of an object, the result is NULL.*

```mql5
dynamic_cast<type-id>(expression)
```

---

### ENUM_TIMEFRAMES
*Timeframe enum*

```mql5
ENUM_TIMEFRAMES
```

---

### PERIOD_M1
```mql5
PERIOD_M1
```

---

### PERIOD_M5
```mql5
PERIOD_M5
```

---

### PERIOD_M15
```mql5
PERIOD_M15
```

---

### PERIOD_M30
```mql5
PERIOD_M30
```

---

### PERIOD_H1
```mql5
PERIOD_H1
```

---

### PERIOD_H4
```mql5
PERIOD_H4
```

---

### PERIOD_D1
```mql5
PERIOD_D1
```

---

### PERIOD_W1
```mql5
PERIOD_W1
```

---

### PERIOD_MN1
```mql5
PERIOD_MN1
```

---

### OP_BUY
```mql5
OP_BUY
```

---

### OP_BUYLIMIT
```mql5
OP_BUYLIMIT
```

---

### OP_BUYSTOP
```mql5
OP_BUYSTOP
```

---

### OP_SELL
```mql5
OP_SELL
```

---

### OP_SELLLIMIT
```mql5
OP_SELLLIMIT
```

---

### OP_SELLSTOP
```mql5
OP_SELLSTOP
```

---

### ENUM_MA_METHOD
*Timeframe enum*

```mql5
ENUM_TIMEFRAMES
```

---

### MODE_SMA
*Simple averaging*

```mql5
MODE_SMA
```

---

### MODE_EMA
*Exponential averaging*

```mql5
MODE_EMA
```

---

### MODE_SMMA
*Smoothed averaging*

```mql5
MODE_SMMA
```

---

### MODE_LWMA
*Linear-weighted averaging*

```mql5
MODE_LWMA
```

---

### ENUM_APPLIED_PRICE
*Applied price enum*

```mql5
ENUM_APPLIED_PRICE
```

---

### PRICE_CLOSE
```mql5
PRICE_CLOSE
```

---

### PRICE_OPEN
```mql5
PRICE_OPEN
```

---

### PRICE_HIGH
```mql5
PRICE_HIGH
```

---

### PRICE_LOW
```mql5
PRICE_LOW
```

---

### PRICE_MEDIAN
```mql5
PRICE_MEDIAN
```

---

### PRICE_TYPICAL
```mql5
PRICE_TYPICAL
```

---

### PRICE_WEIGHTED
```mql5
PRICE_WEIGHTED
```

---

### MqlDateTime
*<struct> structure contains eight fields of the int type*

```mql5
MqlDateTime 
```

---

### MqlParam
*<struct> The MqlParam structure has been specially designed to provide input parameters when creating the handle of a technical indicator using the IndicatorCreate() function.*

```mql5
MqlParam 
```

---

### MqlRates
*<struct> structure stores information about the prices, volumes and spread.*

```mql5
MqlRates 
```

---

### MqlBookInfo
*<struct> provides information about the market depth data*

```mql5
MqlBookInfo 
```

---

### MqlTradeRequest
*<struct> Interaction between the client terminal and a trade server for executing the order placing operation is performed by using trade requests. *

```mql5
MqlTradeRequest 
```

---

### MqlTradeCheckResult
*<struct> Before sending a request for a trade operation to a trade server, it is recommended to check it. The check is performed using the OrderCheck() function, to which the checked request and a variable of the MqlTradeCheckResult structure type are passed. The check result will be written to this variable.*

```mql5
MqlTradeCheckResult 
```

---

### MqlTradeResult
*<struct> As result of a trade request, a trade server returns data about the trade request processing result as a special predefined structure of MqlTradeResult type.*

```mql5
MqlTradeResult 
```

---

### MqlTick
*<struct> This is a structure for storing the latest prices of the symbol. It is designed for fast retrieval of the most requested information about current prices.*

```mql5
MqlTick 
```

---

### _Symbol
*<string> Returns the string value of the current symbol.*

```mql5
_Symbol
```

---

### _Digits
*<int> Number of decimal places*

```mql5
_Digits
```

---

### _Point
*<double> Size of the current symbol point in the quote currency*

```mql5
_Point
```

---

### _LastError
*<int> last error code*

```mql5
_LastError
```

---

### _Period
*<ENUM_TIMEFRAMES> value of the timeframe of the current chart.*

```mql5
_Period
```

---

### _RandomSeed
*<int> Variable for storing the current state when generating pseudo-random integers*

```mql5
_RandomSeed
```

---

### _StopFlag
*<bool> contains the flag of the mql5-program stop*

```mql5
_StopFlag
```

---

### _UninitReason
*<int> contains the code of the program uninitialization reason.*

```mql5
_UninitReason
```

---

### Bid
*<double> bid*

```mql5
Bid
```

---

### Ask
*<double> ask*

```mql5
Ask
```

---

### Open[]
*<double> Series array that contains open prices of each bar of the current chart*

```mql5
Open[i]
```

---

### High[]
*<double> Series array that contains high prices of each bar of the current chart*

```mql5
High[i]
```

---

### Low[]
*<double> Series array that contains low prices of each bar of the current chart*

```mql5
Low[i]
```

---

### Close[]
*<double> Series array that contains close prices of each bar of the current chart*

```mql5
Close[i]
```

---

### Time[]
*<datetime> Series array that contains time of each bar of the current chart*

```mql5
Time[i]
```

---

### Volume[]
*<long> Series array that contains volume of each bar of the current chart*

```mql5
Volume[i]
```

---

### Alert
*<void> Displays a message in a separate window.*

```mql5
Alert(argument, ...)
```

---

### Check Pointer
*<ENUM_POINTER_TYPE> The function returns the type of the object pointer.*

```mql5
CheckPointer(object* anytype)
```

---

### Comment
*<void> outputs a comment defined by a user in the top left corner of a chart.*

```mql5
Comment(argument, ...)
```

---

### DebugBreak
*<void> sets a debug break point*

```mql5
DebugBreak()
```

---

### ExpertRemove
*<void> stops an Expert Advisor and unloads it from a chart.*

```mql5
ExpertRemove()
```

---

### GetPointer
*<void*> returns the object pointer.*

```mql5
GetPointer(object anytype)
```

---

### GetTickCount
*<uint> returns the number of milliseconds that elapsed since the system start*

```mql5
GetTickCount()
```

---

### GetMicrosecondCount
*<ulong> returns the number of microseconds that have elapsed since the start of MQL5-program.*

```mql5
GetMicrosecondCount()
```

---

### MessageBox
*<int> creates and shows a message box and manages it..*

```mql5
MessageBox(string  text, caption=NULL, int flags)
```

---

### PeriodSeconds
*<int> number of seconds in a period.*

```mql5
PeriodSeconds(ENUM_TIMEFRAMES=PERIOD_CURRENT)
```

---

### PlaySound
*<bool> plays a sound file.*

```mql5
PlaySound(string  filename)
```

---

### Print
*<void> enters a message in the Expert Advisor log. Parameters can be of any type.*

```mql5
Print(argument, ...)
```

---

### PrintFormat
*<void> formats and enters sets of symbols and values in the Expert Advisor log in accordance with a preset format.*

```mql5
PrintFormat(string format_string,  ...)
```

---

### ResetLastError
*<void> Sets the value of the predefined variable _LastError into zero.*

```mql5
ResetLastError()
```

---

### SendNotification
*<bool> Sends push notifications to the mobile terminals, whose MetaQuotes IDs are specified in the \*

```mql5
SendNotification(string text)
```

---

### SendMail
*<bool> Sends an email at the address specified in the settings window of the Email tab.*

```mql5
SendMail(string subject, string text)
```

---

### Sleep
*<void> The function suspends execution of the current Expert Advisor or script within a specified interval.*

```mql5
Sleep(int milliseconds)
```

---

### TranslateKey
*<short> Returns a Unicode character by a virtual key code considering the current input language and the status of control keys.*

```mql5
TranslateKey(int key_code)
```

---

### WebRequest
*<int> sends an HTTP request to a specified server. The function has two versions:*

```mql5
WebRequest(see docs)
```

---

### ZeroMemory
*<void> resets a variable passed to it by reference.*

```mql5
ZeroMemory(void &variable)
```

---

### ArraySize
*<int> The function returns the number of elements of a selected array..*

```mql5
ArraySize(const void& array[])
```

---

### ArrayGetAsSeries
*<bool> It checks direction of an array index..*

```mql5
ArrayGetAsSeries(const void& array[])
```

---

### ArraySetAsSeries
*<bool> The function sets the AS_SERIES flag to a selected object of a dynamic array, and elements will be indexed like in timeseries.*

```mql5
ArraySetAsSeries(const void& array[], ${bool flag})
```

---

### ArrayResize
*<int> The function sets a new size for the first dimension*

```mql5
ArrayResize(void& array[], int new_size,reserved_size=0)
```

---

### ArrayInitialize
*<int> initializes a numeric array by a preset value.*

```mql5
ArrayInitialize(T array[], T value)
```

---

### CharToString
*<tostring> Converting a symbol code into a one-character string.*

```mql5
CharToString(uchar char_code)
```

---

### CharArrayToString
*<string> It copies and converts part of array of uchar type into a returned string..*

```mql5
CharArrayToString(uchar array[], int start, int count=1, uint code_page=CP_ACP)
```

---

### ColorToString
*<string> It converts color value into string of R,G,B form.*

```mql5
ColorToString(color color, bool show_color_name)
```

---

### DoubleToString
*<string> Converting numeric value into text string.*

```mql5
DoubleToString(double value, int digits=8)
```

---

### EnumToString
*<string> Converting an enumeration value of any type to a text form.*

```mql5
EnumToString(any_enum value)
```

---

### TimeToString
*<string> Converting a value containing time in seconds elapsed since 01.01.1970 into a string of yyyy.mm.dd hh:mi format.*

```mql5
TimeToString(datetime value, int mode=TIME_DATE|TIME_MINUTES)
```

---

### NormalizeDouble
*<double> Rounding floating point number to a specified accuracy.*

```mql5
NormalizeDouble(double value, int digits)
```

---

### StringToCharArray
*<int> Symbol-wise copies a string converted from Unicode to ANSI, to a selected place of array of uchar type. It returns the number of copied elements.*

```mql5
StringToCharArray(string text_string, uchar& array[], int start=0, int count=-1, uint codepage=CP_ACP)
```

---

### StringToTime
*<datetime> converts a string containing time or date in yyyy.mm.dd [hh:mi] format into datetime type.*

```mql5
StringToTime(string value)
```

---

### StringFormat
*<string> The function formats obtained parameters and returns a string.*

```mql5
StringFormat(string format, params...)
```

---

### MathAbs
*<double> The function returns the absolute value (modulus) of the specified numeric value.*

```mql5
fabs(double value)
```

---

### MathPow
*<double> The function returns the absolute value (modulus) of the specified numeric value.*

```mql5
pow(double base, double exponent)
```

---

### MathArcsin
*<double> returns the arc sine of x within the range of -π/2 to π/2 radians.*

```mql5
asin(double value)
```

---

### MathArccos
*<double> returns the arccosine of x within the range 0 to π in radians.*

```mql5
acos(double value)
```

---

### MathCeil
*<double> returns integer numeric value closest from above.*

```mql5
ceil(double value)
```

---

### MathFloor
*<double> returns integer numeric value closest from below.*

```mql5
floor(double value)
```

---

### MathLog
*<double> returns a natural logarithm.*

```mql5
log(double value)
```

---

### MathLog10
*<double> Returns the logarithm of a number by base 10.*

```mql5
log10(double value)
```

---

### MathMax
* <double> returns the maximal value of two values.*

```mql5
fmax(double value1, double value2)
```

---

### MathMin
*<double> returns the minimal value of two values.*

```mql5
fmin(double value1, double value2)
```

---

### MathRand
*<int> Returns a pseudorandom integer within the range of 0 to 32767.*

```mql5
rand()
```

---

### MathSrand
*<void> Sets the starting point for generating a series of pseudorandom integers.*

```mql5
srand(${int seed})
```

---

### MathRound
*<double> returns a value rounded off to the nearest integer of the specified numeric value.*

```mql5
round(double value)
```

---

### MathIsValidNumber
*<bool> checks the correctness of a real number*

```mql5
MathIsValidNumber(double value)
```

---

### MathSqrt
*<double> Returns the square root of a number.*

```mql5
sqrt(double value)
```

---

### TimeCurrentStruct
*<datetime> MqlDateTime structure type variable has been passed as a parameter, it is filled accordingly*

```mql5
TimeCurrent(MqlDateTime struct)
```

---

### TimeCurrent
*<datetime> Returns the last known server time*

```mql5
TimeCurrent()
```

---

### TimeTradeServer
*<datetime> Returns the calculated current time of the trade server*

```mql5
TimeTradeServer()
```

---

### TimeLocal
*<datetime> Returns the local time of a computer*

```mql5
TimeLocal()
```

---

### TimeLocal Struct
*<datetime> Returns the local time of a computer; fills struct*

```mql5
TimeLocal(MqlDateTime &struct)
```

---

### TimeGMT
*<datetime> Returns the GMT, which is calculated taking into account the DST switch by the local time on the computer where the client terminal is running.*

```mql5
TimeGMT()
```

---

### TimeGMT Struct
*<datetime> Returns the GMT, which is calculated taking into account the DST switch by the local time on the computer where the client terminal is running.*

```mql5
TimeGMT(MqlDateTime &struct)
```

---

### TimeDaylightSavings
*<datetime> Returns correction for daylight saving time in seconds, if the switch to summer time has been made.*

```mql5
TimeDaylightSavings()
```

---

### TimeGMTOffset
*<datetime> Returns the current difference between GMT time and the local computer time in seconds*

```mql5
TimeGMTOffset()
```

---

### TimeToStruct
*<bool> Converts a value of datetime type (number of seconds since 01.01.1970) into a structure variable MqlDateTime.*

```mql5
TimeToStruct(datetime dt, MqlDateTime &struct)
```

---

### StructToTime
*<datetime> Converts a structure variable MqlDateTime into a value of datetime type and returns the resulting value.*

```mql5
StructToTime(MqlDateTime &struct)
```

---

### StringAdd
*<bool> adds a substring to the end of a string.*

```mql5
StringAdd(string& str_var, string add_substring)
```

---

### StringBufferLen
*<int> returns the size of buffer allocated for the string.*

```mql5
StringBufferLen(string string_var)
```

---

### StringCompare
*<int> compares two strings and returns the comparison result in form of an integer.Case sensitivity mode selection. If it is true, then A>a. If it is false, then A=a.*

```mql5
StringCompare(string str1, string str2,${bool case_sensitive=true})
```

---

### StringFill
*<bool> It fills out a selected string by specified symbols*

```mql5
StringFill(string& str_var, ushort character)
```

---

### StringFind
*<int> Search for a substring in a string.*

```mql5
StringFind(string value, string match_substring,int start_pos=0)
```

---

### StringGetCharacter
*<ushort> returns value of a symbol, located in the specified position of a string.*

```mql5
StringGetCharacter(string str_var, int pos)
```

---

### StringLen
*<int> Returns the number of symbols in a string*

```mql5
StringLen(string str_var)
```

---

### StringReplace
*<int> replaces all the found substrings of a string by a set sequence of symbols. The function returns the number of replacements in case of success, otherwise -1. To get an error code call the GetLastError() function.*

```mql5
StringReplace(string& str, string find, string replace)
```

---

### StringSplit
*<int> Gets substrings by a specified separator from the specified string, returns the number of substrings obtained.*

```mql5
StringSplit(string str, ushort separator, string &result[])
```

---

### StringSubstr
*<string> Extracts a substring from a text string starting from the specified position.*

```mql5
StringSubstr(string str, int start_pos, ${3:int length=-1)
```

---

### StringToLower
*<bool> Transforms all symbols of a selected string into lowercase.*

```mql5
StringToLower(string& str)
```

---

### StringToUpper
*<bool> Transforms all symbols of a selected string into capitals.*

```mql5
StringToUpper(string& str)
```

---

### StringTrimRight
*<int> The function cuts line feed characters, spaces and tabs in the right part of the string after the last meaningful symbol. The string is modified at place.*

```mql5
StringTrimRight(string& str)
```

---

### StringTrimLeft
*<int> The function cuts line feed characters, spaces and tabs in the left part of the string till the first meaningful symbol. The string is modified at place.*

```mql5
StringTrimLeft(string& str)
```

---

### AccountInfoDouble
*<double> Returns the value of the corresponding account property.*

```mql5
AccountInfoDouble(ENUM_ACOUNT_INFO_DOUBLE property_id)
```

---

### AccountInfoInteger
*<long> Returns the value of the corresponding account property.*

```mql5
AccountInfoInteger(ENUM_ACOUNT_INFO_INTEGER  property_id)
```

---

### AccountInfoString
*<string> Returns the value of the corresponding account property.*

```mql5
AccountInfoString(ENUM_ACOUNT_INFO_STRING  property_id)
```

---

### AccountBalance
*<double> Returns balance value of the current account.*

```mql5
AccountBalance()
```

---

### AccountCredit
*<double> Returns credit value of the current account.*

```mql5
AccountCredit()
```

---

### AccountCompany
*<string> Returns the brokerage company name where the current account was registered.*

```mql5
AccountCompany()
```

---

### AccountCurrency
*<string> Returns currency name of the current account.*

```mql5
AccountCurrency()
```

---

### AccountEquity
*<double> Returns equity value of the current account.*

```mql5
AccountEquity()
```

---

### AccountFreeMargin
*<double> Returns free margin value of the current account.*

```mql5
AccountFreeMargin()
```

---

### AccountFreeMarginCheck
*<double> Returns free margin that remains after the specified order has been opened at the current price on the current account.*

```mql5
AccountFreeMarginCheck(string symbol, int trade_operation, double volume)
```

---

### AccountFreeMarginMode
*<double> Returns the calculation mode of free margin allowed to open orders on the current account. The calculation mode can take the following values 0 - floating profit/loss is not used for calculation 1 - both floating profit and loss on opened orders on the current account are used for free margin calculation 2 - only profit value is used for calculation, the current loss on opened orders is not considered 3 - only loss value is used for calculation, the current floating profit on opened orders is not considered.*

```mql5
AccountFreeMarginMode()
```

---

### AccountLeverage
*<int> Returns leverage of the current account.*

```mql5
AccountLeverage()
```

---

### AccountMargin
*<double> Returns margin value of the current account.*

```mql5
AccountMargin()
```

---

### AccountName
*<string> Returns the current account name.*

```mql5
AccountName()
```

---

### AccountNumber
*<int> Returns the current account number.*

```mql5
AccountNumber()
```

---

### AccountProfit
*<double> Returns profit value of the current account.*

```mql5
AccountProfit()
```

---

### AccountServer
*<string> Returns the connected server name.*

```mql5
AccountServer()
```

---

### AccountStopoutLevel
*<int> Returns the value of the Stop Out level.*

```mql5
AccountStopoutLevel()
```

---

### AccountStopoutMode
*<int> Returns the calculation mode for the Stop Out level. Calculation mode can take the following values: 0 - calculation of percentage ratio between margin and equity; 1 - comparison of the free margin level to the absolute value.*

```mql5
AccountStopoutMode()
```

---

### ACCOUNT_LOGIN
*<long> Account number*

```mql5
ACCOUNT_LOGIN
```

---

### ACCOUNT_TRADE_MODE
*<ENUM_ACCOUNT_TRADE_MODE> Account trade mode*

```mql5
ACCOUNT_TRADE_MODE
```

---

### ACCOUNT_LEVERAGE
*<long> Account leverage*

```mql5
ACCOUNT_LEVERAGE
```

---

### ACCOUNT_LIMIT_ORDERS
*<int> Maximum allowed number of active pending orders*

```mql5
ACCOUNT_LIMIT_ORDERS
```

---

### ACCOUNT_MARGIN_SO_MODE
*<ENUM_ACCOUNT_STOPOUT_MODE> Mode for setting the minimal allowed margin*

```mql5
ACCOUNT_MARGIN_SO_MODE
```

---

### ACCOUNT_TRADE_ALLOWED
*<bool> Allowed trade for the current account*

```mql5
ACCOUNT_TRADE_ALLOWED
```

---

### ACCOUNT_TRADE_EXPERT
*<bool> Allowed trade for an Expert Advisor*

```mql5
ACCOUNT_TRADE_EXPERT
```

---

### ACCOUNT_MARGIN_MODE
*<ENUM_ACCOUNT_MARGIN_MODE> Margin calculation mode*

```mql5
ACCOUNT_MARGIN_MODE
```

---

### GetLastError
*<int> Returns the contents of the system variable _LastError*

```mql5
GetLastError()
```

---

### IsStopped
*<bool> Checks the forced shutdown of an mql5 program*

```mql5
IsStopped()
```

---

### UninitializeReason
*<int> Returns the code of a reason for deinitialization.*

```mql5
UninitializeReason()
```

---

### TerminalInfoInteger
*<long> Returns the value of a corresponding property of the mql5 program environment*

```mql5
TerminalInfoInteger(int property_id)
```

---

### TerminalInfoDouble
*<double> Returns the value of a corresponding property of the mql5 program environment*

```mql5
TerminalInfoDouble(int property_id)
```

---

### TerminalInfoString
*<string> Returns the value of a corresponding property of the mql5 program environment*

```mql5
TerminalInfoString(int property_id)
```

---

### MQLInfoInteger
*<int> Returns the value of a corresponding property of a running mql5 program.*

```mql5
MQLInfoInteger(int property_id)
```

---

### MQLInfoString
*<string> Returns the value of a corresponding property of a running mql5 program.*

```mql5
MQLInfoString(int property_id)
```

---

### SymbolsTotal
*<int> Returns the number of available (selected in Market Watch or all) symbols.*

```mql5
SymbolsTotal(bool selected)
```

---

### SymbolName
*<string> returns the name of the symbol from the marketwatch window.*

```mql5
SymbolName(int pos, bool selected)
```

---

### SymbolSelect
*<bool> Selects a symbol in the Market Watch window or removes a symbol from the window.*

```mql5
SymbolSelect(string name, bool select)
```

---

### SymbolIsSynchronized
*<bool> The function checks whether data of a selected symbol in the terminal are synchronized with data on the trade server.*

```mql5
SymbolIsSynchronized(string name)
```

---

### SymbolInfoTick
*<bool> returns current prices of a specified symbol in a variable of the MqlTick type.*

```mql5
SymbolInfoTick(string name, MqlTick& tick)
```

---

### MarketBookAdd
*<bool> Provides opening of Depth of Market for a selected symbol, and subscribes for receiving notifications of the DOM changes.*

```mql5
MarketBookAdd(string name)
```

---

### MarketBookRelease
*<bool> Provides closing of Depth of Market for a selected symbol, and cancels the subscription for receiving notifications of the DOM changes.*

```mql5
MarketBookRelease(string name)
```

---

### MarketBookGet
*<bool> Returns a structure array MqlBookInfo containing records of the Depth of Market of a specified symbol.*

```mql5
MarketBookGet(string name, MqlBookInfo&  book[])
```

---

### SymbolInfoInteger
*<long> Returns the corresponding property of a specified symbol.*

```mql5
SymbolInfoInteger(string name, ENUM_SYMBOL_INFO_STRING prop_id)
```

---

### SymbolInfoString
*<string> Returns the corresponding property of a specified symbol.*

```mql5
SymbolInfoString(string name, ENUM_SYMBOL_INFO_INTEGER prop_id)
```

---

### SymbolInfoDouble
*<double> Returns the corresponding property of a specified symbol.*

```mql5
SymbolInfoDouble(string name, ENUM_SYMBOL_INFO_DOUBLE prop_id)
```

---

### SYMBOL_BID
*<double> Bid*

```mql5
SYMBOL_BID
```

---

### SYMBOL_ASK
*<double> Ask*

```mql5
SYMBOL_ASK
```

---

### SYMBOL_POINT
*<double> Symbol point value.*

```mql5
SYMBOL_POINT
```

---

### SYMBOL_TRADE_TICK_VALUE
*<double> Value of one tick*

```mql5
SYMBOL_TRADE_TICK_VALUE
```

---

### SYMBOL_TRADE_TICK_SIZE
*<double> Minimal price change*

```mql5
SYMBOL_TRADE_TICK_SIZE
```

---

### SYMBOL_VOLUME_MIN
*<double> Minimal volume for a deal*

```mql5
SYMBOL_VOLUME_MIN
```

---

### SYMBOL_VOLUME_MAX
*<double> Maximum volume for a deal.*

```mql5
SYMBOL_VOLUME_MAX
```

---

### SYMBOL_VOLUME_STEP
*<double> Minimal volume change step for deal execution*

```mql5
SYMBOL_VOLUME_STEP
```

---

### SYMBOL_MARGIN_INITIAL
*<double> Initial margin means the amount in the margin currency required for opening an order with the volume of one lot. It is used for checking a client's assets when he or she enters the market.*

```mql5
SYMBOL_MARGIN_INITIAL
```

---

### SYMBOL_CURRENCY_BASE
*<string> Basic currency of a symbol.*

```mql5
SYMBOL_CURRENCY_BASE
```

---

### SYMBOL_CURRENCY_PROFIT
*<string> Profit/counter currency of a symbol.*

```mql5
SYMBOL_CURRENCY_PROFIT
```

---

### SYMBOL_CURRENCY_MARGIN
*<string> Margin Currency*

```mql5
SYMBOL_CURRENCY_MARGIN
```

---

### SYMBOL_DESCRIPTION
*<string> Symbol Description.*

```mql5
SYMBOL_DESCRIPTION
```

---

### SYMBOL_SELECT
*<bool> Symbol is selected in Market Watch. Some symbols can be hidden in Market Watch, but still they are considered as selected.*

```mql5
SYMBOL_SELECT
```

---

### SYMBOL_DIGITS
*<int> Number of decimal places in the symbol quote.*

```mql5
SYMBOL_DIGITS
```

---

### SYMBOL_TIME
*<datetime> Time of the last quote.*

```mql5
SYMBOL_TIME
```

---

### SeriesInfoInteger
*<long> Returns information about the state of historical data.*

```mql5
SeriesInfoInteger(string name, ENUM_TIMEFRAMES timeframe, ENUM_SERIES_INFO_INTEGER prop_id)
```

---

### SERIES_BARS_COUNT
*<long> Bars count for the symbol-period for the current moment*

```mql5
SERIES_BARS_COUNT
```

---

### SERIES_FIRSTDATE
*<datetime> The very first date for the symbol-period for the current moment*

```mql5
SERIES_FIRSTDATE
```

---

### SERIES_LASTBAR_DATE
*<datetime> Open time of the last bar of the symbol-period*

```mql5
SERIES_LASTBAR_DATE
```

---

### SERIES_SERVER_FIRSTDATE
*<datetime> The very first date in the history of the symbol on the server regardless of the timeframe*

```mql5
SERIES_SERVER_FIRSTDATE
```

---

### Bars_From_To
*<int> Returns the number of bars count in the history for a specified symbol and period.*

```mql5
Bars(string name, ENUM_TIMEFRAMES timeframe, datetime start_time, datetime stop_time)
```

---

### Bars
*<int> Returns the number of bars count in the history for a specified symbol and period.*

```mql5
Bars(string name, ENUM_TIMEFRAMES timeframe)
```

---

### BarsCalculated
*<int> Returns the number of calculated data for the specified indicator*

```mql5
BarsCalculated(int ind_handle)
```

---

### IndicatorRelease
*<bool> removes an indicator handle and releases the calculation block of the indicator, if it's not used by anyone else.*

```mql5
IndicatorRelease(int ind_handle)
```

---

### CopyTicks
*<int> receives ticks in the MqlTick format into ticks_array.*

```mql5
CopyTicks(string symbol, MqlTick& tickarray[], uint flags=COPY_TICKS_ALL, ulong from=0, uint count=0)
```

---

### CopyBuffer
*<int> Gets data of a specified buffer of a certain indicator in the necessary quantity.*

```mql5
CopyBuffer(int handle, int buffer_number, int start_pos|datetime start_time, int count|datetime stop_time, double buffer[])
```

---

### CopyRates
*<int> Gets history data of MqlRates structure of a specified symbol-period in specified quantity into the rates_array array. The elements ordering of the copied data is from present to the past, i.e., starting position of 0 means the current bar.*

```mql5
CopyRates(string symbol, ENUM_TIMEFRAMES timeframe, int start_pos|datetime start_time, int count|datetime stop_time, MqlRates rates_array[])
```

---

### EventSetMillisecondTimer
*<bool> indicates to the client terminal that timer events should be generated at intervals less than one second for this Expert Advisor or indicator.*

```mql5
EventSetMillisecondTimer(int milliseconds)
```

---

### EventSetTimer
*<bool> indicates to the client terminal, that for this indicator or Expert Advisor, events from the timer must be generated with the specified periodicity.*

```mql5
EventSetTimer(int seconds)
```

---

### EventKillTimer
*<bool> Specifies the client terminal that is necessary to stop the generation of events from Timer.*

```mql5
EventKillTimer()
```

---

### EventChartCustom
*<bool> The function generates a custom event for the specified chart.*

```mql5
EventChartCustom()
```

---

### OrderClose
*<bool> Closes opened order.*

```mql5
OrderClose(int ticket, double lots, double price, int slippage, color arrow_color=clrNone)
```

---

### OrderCloseBy
*<bool> Closes an opened order by another opposite opened order.*

```mql5
OrderCloseBy(int ticket, int opposite, color arrow_color=clrNone)
```

---

### OrderClosePrice
*<double> Returns close price of the currently selected order. If the order is live this will return the price of which it is to be closed.*

```mql5
OrderClosePrice()
```

---

### OrderCloseTime
*<datetime> Returns close time of the currently selected order.*

```mql5
OrderCloseTime(int ticket, double lots, double price, int slippage, color arrow_color)
```

---

### OrderComment
*<string> Returns comment of the currently selected order.*

```mql5
OrderComment()
```

---

### OrderCommission
*<double> Returns calculated commission of the currently selected order.*

```mql5
OrderCommission()
```

---

### OrderDelete
*<bool> Deletes previously opened pending order.*

```mql5
OrderDelete(int ticket, color arrow_color=clrNone)
```

---

### OrderExpiration
*<datetime> Returns expiration date of the selected pending order.*

```mql5
OrderExpiration()
```

---

### OrderLots
*<double> Returns amount of lots of the selected order.*

```mql5
OrderLots()
```

---

### OrderMagicNumber
*<int> Returns an identifying (magic) number of the currently selected order.*

```mql5
OrderMagicNumber()
```

---

### OrderModify
*<bool> Modification of characteristics of the previously opened or pending orders.*

```mql5
OrderModify(int ticket, double price, double stoploss, double takeprofit, datetime expiration, color arrow_color=clrNone)
```

---

### OrderOpenPrice
*<double> Returns open price of the currently selected order.*

```mql5
OrderOpenPrice()
```

---

### OrderOpenTime
*<datetime> Returns open time of the currently selected order.*

```mql5
OrderOpenTime()
```

---

### OrderPrint
*<void> Prints information about the selected order in the log.*

```mql5
OrderPrint()
```

---

### OrderProfit
*<double> Returns profit of the currently selected order.*

```mql5
OrderProfit()
```

---

### OrderSelect
*<bool> The function selects an order for further processing.*

```mql5
OrderSelect(int position|int ticket, SELECT_BY_POS|SELECT_BY_TICKET, int pool=MODE_TRADES|MODE_HISTORY)
```

---

### OrderSend
*<int> The main function used to open market or place a pending order. Returns number of the ticket assigned to the order by the trade server or -1 if it fails.*

```mql5
OrderSend(string symbol, int cmd, double volume, double price, int slippage, double stoploss, double takeprofit, string comment=NULL, int magic=0, datetime expiration=0, color arrow_color=clrNONE)
```

---

### OrdersHistoryTotal
*<int> Returns the number of closed orders in the account history loaded into the terminal. *

```mql5
OrdersHistoryTotal)
```

---

### OrderStopLoss
*<double> Returns stoploss of the currently selected order.*

```mql5
OrderStopLoss(int ticket, double lots, double price, int slippage, color arrow_color)
```

---

### OrdersTotal
*<int> Returns the number of market and pending orders.*

```mql5
OrdersTotal()
```

---

### OrderSwap
*<double> Returns swap value of the currently selected order.*

```mql5
OrderSwap()
```

---

### OrderTakeProfit
*<datetime> Returns take profit value of the currently selected order.*

```mql5
OrderTakeProfit()
```

---

### OrderSymbol
*<string> Returns symbol of the currently selected order.*

```mql5
OrderSymbol()
```

---

### OrderTicket
*<int> Returns order ticket number of the currently selected order.*

```mql5
OrderTicket()
```

---

### OrderType
*<int> Returns order operation type of the currently selected order. OP_BUY=buy-order, OP_SELL=sell-order, OP_BUYLIMIT=buy-limit, OP_BUYSTOP=buy-stop, OP_SELLLIMIT=sell-limit, OP_SELLSTOP=sell-stop.*

```mql5
OrderType()
```

---

### iATR
*<double> Calculates the Average True Range indicator and returns its value*

```mql5
iATR(string symbol, int timeframe, int period, int shift)
```

---

### iADX
*<double> Calculates the Average Directional Movement Index indicator and returns its value.*

```mql5
iADX(string symbol, int timeframe, int period, int applied_price, int mode, int shift)
```

---

### iBands
*<double> Calculates the Bollinger Bands® indicator and returns its value.*

```mql5
iBands(string symbol, int timeframe, int period, double deviation, int bands_shift, int applied_price, int mode, int shift)
```

---

### iCustom
*<double> Calculates the specified custom indicator and returns its value. The custom indicator must be compiled (*.EX4 file) and be in the terminal_directory\\MQL4\\Indicators\\ directory.*

```mql5
iCustom(string symbol, int timeframe, string name,  ... , int buffer_index, int shift)
```

---

### iMA
*<double> Calculates the Moving Average indicator and returns its value. eg. iMA(NULL,0,13,8,MODE_SMMA,PRICE_MEDIAN,i);*

```mql5
iMA(string symbol, int timeframe, int ma_period, int ma_shift, int ma_method, int applied_price, int shift)
```

---

### iRSI
*<double> Calculates the RSI indicator and returns its value.*

```mql5
iRSI(string symbol, int timeframe, int period, int applied_price, int shift)
```

---

### iStochastic
*<double> Calculates the Moving Average indicator and returns its value. eg. iMA(NULL,0,13,8,MODE_SMMA,PRICE_MEDIAN,i);*

```mql5
iStochastic(string symbol, int timeframe, int Kperiod, int Dperiod, int slowing, int method, int price_field, int mode, int shift)
```

---

### ENUM_CHART_EVENT
*There are 9 types of events that can be processed using the predefined function OnChartEvent(). *

```mql5
ENUM_CHART_EVENT
```

---

### CHARTEVENT_KEYDOWN
*Keystrokes*

```mql5
CHARTEVENT_KEYDOWN
```

---

### CHARTEVENT_MOUSE_MOVE
*Mouse move, mouse clicks (if CHART_EVENT_MOUSE_MOVE=true is set for the chart)*

```mql5
CHARTEVENT_MOUSE_MOVE
```

---

### CHARTEVENT_OBJECT_CREATE
*Graphical object created (if CHART_EVENT_OBJECT_CREATE=true is set for the chart)*

```mql5
CHARTEVENT_OBJECT_CREATE
```

---

### CHARTEVENT_OBJECT_DELETE
*Graphical object deleted (if CHART_EVENT_OBJECT_DELETE=true is set for the chart)*

```mql5
CHARTEVENT_OBJECT_DELETE
```

---

### CHARTEVENT_OBJECT_CHANGE
*Graphical object property changed via the properties dialog*

```mql5
CHARTEVENT_OBJECT_CHANGE
```

---

### CHARTEVENT_CLICK
*Clicking on a graphical object*

```mql5
CHARTEVENT_CLICK
```

---

### CHARTEVENT_OBJECT_DRAG
*Drag and drop of a graphical object*

```mql5
CHARTEVENT_OBJECT_DRAG
```

---

### CHARTEVENT_OBJECT_ENDEDIT
*End of text editing in the graphical object Edit*

```mql5
CHARTEVENT_OBJECT_ENDEDIT
```

---

### CHARTEVENT_CHART_CHANGE
*Change of the chart size or modification of chart properties through the Properties dialog*

```mql5
CHARTEVENT_CHART_CHANGE
```

---

### CHARTEVENT_CUSTOM
*Initial number of an event from a range of custom events*

```mql5
CHARTEVENT_CUSTOM
```

---

### CHARTEVENT_CUSTOM_LAST
*The final number of an event from a range of custom events*

```mql5
CHARTEVENT_CUSTOM_LAST
```

---

### for forward
*mql4 orderselect loop*

```mql5
for(int i=0;i < int max_iter;i++)
{
   
}
```

---

### for backward
*mql4 orderselect loop*

```mql5
for(int i=int max_iter - 1;i >= 0 ;i--)
{
   
}
```

---

### for OrdersTotal
*mql4 orderselect loop*

```mql5
for(int i=OrdersTotal()-1;i>=0;i--)
{
   if(OrderSelect(i,SELECT_BY_POS) && OrderSymbol() == _Symbol  other conditions)
   {
      
   }
}
```

---

### for OrdersHistoryTotal
*mql4 orderselect loop*

```mql5
for(int i=OrdersHistoryTotal()-1;i>=0;i--)
{
   if(OrderSelect(i,SELECT_BY_POS,MODE_HISTORY) && OrderSymbol() == _Symbol  other conditions)
   {
      
   }
}
```

---

### OnStart
*Script entry point*

```mql5
void OnStart()
{
   
}
```

---

### Script_Template
```mql5

         

         

         
Copyright 2017, Author Name\
,
         
Link\
,
         
1.00\
,
         
,
         
,
         
,
         
,
         
,
         
,
         
,
         
,
         
```

---

### Expert_Template
*expert advisor template*

```mql5

         

         

         
Copyright 2017, Author Name\
,
         
Link\
,
         
1.00\
,
         
,
         
,
         
,
         

         
int OnInit()
{
   EventSetTimer(60);
   
   return(INIT_SUCCEEDED);
}

         

         
,
         
,
         
,
         
,
         
,
         

         
void OnTick()
{
   
}

         

         
,
         
,
         
,
         
,
         

         
void OnChartEvent(const int id,
                const long &lparam,
                const double &dparam,
                const string &sparam)
{
 
}
```

---

### Function Header
```mql5

         

         
,
         
,
         
,
         
```

---

### datetime
```mql5
datetime
```

---

### color
```mql5
color
```

---

### ulong
```mql5
ulong
```

---

### ushort
```mql5
ushort
```

---

### uchar
```mql5
uchar
```

---

### uint
```mql5
uint
```

---

### string
```mql5
string
```

---

### NULL
```mql5
NULL
```

---

### include
*preprocessor include directive*

```mql5
#include <file_name.mqh>
```

---

### dynamic_cast
*Dynamic typecasting is performed using dynamic_cast operator that can be applied only to pointers to classes. Type validation is performed at runtime. This means that the compiler does not check the data type applied for typecasting when dynamic_cast operator is used. If a pointer is converted to a data type which is not the actual type of an object, the result is NULL.*

```mql5
dynamic_cast<type-id>(expression)
```

---

### ENUM_TIMEFRAMES
*Timeframe enum*

```mql5
ENUM_TIMEFRAMES
```

---

### PERIOD_M1
```mql5
PERIOD_M1
```

---

### PERIOD_M5
```mql5
PERIOD_M5
```

---

### PERIOD_M15
```mql5
PERIOD_M15
```

---

### PERIOD_M30
```mql5
PERIOD_M30
```

---

### PERIOD_H1
```mql5
PERIOD_H1
```

---

### PERIOD_H4
```mql5
PERIOD_H4
```

---

### PERIOD_D1
```mql5
PERIOD_D1
```

---

### PERIOD_W1
```mql5
PERIOD_W1
```

---

### PERIOD_MN1
```mql5
PERIOD_MN1
```

---

### OP_BUY
```mql5
OP_BUY
```

---

### OP_BUYLIMIT
```mql5
OP_BUYLIMIT
```

---

### OP_BUYSTOP
```mql5
OP_BUYSTOP
```

---

### OP_SELL
```mql5
OP_SELL
```

---

### OP_SELLLIMIT
```mql5
OP_SELLLIMIT
```

---

### OP_SELLSTOP
```mql5
OP_SELLSTOP
```

---

### ENUM_MA_METHOD
*Timeframe enum*

```mql5
ENUM_TIMEFRAMES
```

---

### MODE_SMA
*Simple averaging*

```mql5
MODE_SMA
```

---

### MODE_EMA
*Exponential averaging*

```mql5
MODE_EMA
```

---

### MODE_SMMA
*Smoothed averaging*

```mql5
MODE_SMMA
```

---

### MODE_LWMA
*Linear-weighted averaging*

```mql5
MODE_LWMA
```

---

### ENUM_APPLIED_PRICE
*Applied price enum*

```mql5
ENUM_APPLIED_PRICE
```

---

### PRICE_CLOSE
```mql5
PRICE_CLOSE
```

---

### PRICE_OPEN
```mql5
PRICE_OPEN
```

---

### PRICE_HIGH
```mql5
PRICE_HIGH
```

---

### PRICE_LOW
```mql5
PRICE_LOW
```

---

### PRICE_MEDIAN
```mql5
PRICE_MEDIAN
```

---

### PRICE_TYPICAL
```mql5
PRICE_TYPICAL
```

---

### PRICE_WEIGHTED
```mql5
PRICE_WEIGHTED
```

---

### MqlDateTime
*<struct> structure contains eight fields of the int type*

```mql5
MqlDateTime 
```

---

### MqlParam
*<struct> The MqlParam structure has been specially designed to provide input parameters when creating the handle of a technical indicator using the IndicatorCreate() function.*

```mql5
MqlParam 
```

---

### MqlRates
*<struct> structure stores information about the prices, volumes and spread.*

```mql5
MqlRates 
```

---

### MqlBookInfo
*<struct> provides information about the market depth data*

```mql5
MqlBookInfo 
```

---

### MqlTradeRequest
*<struct> Interaction between the client terminal and a trade server for executing the order placing operation is performed by using trade requests. *

```mql5
MqlTradeRequest 
```

---

### MqlTradeCheckResult
*<struct> Before sending a request for a trade operation to a trade server, it is recommended to check it. The check is performed using the OrderCheck() function, to which the checked request and a variable of the MqlTradeCheckResult structure type are passed. The check result will be written to this variable.*

```mql5
MqlTradeCheckResult 
```

---

### MqlTradeResult
*<struct> As result of a trade request, a trade server returns data about the trade request processing result as a special predefined structure of MqlTradeResult type.*

```mql5
MqlTradeResult 
```

---

### MqlTick
*<struct> This is a structure for storing the latest prices of the symbol. It is designed for fast retrieval of the most requested information about current prices.*

```mql5
MqlTick 
```

---

### _Symbol
*<string> Returns the string value of the current symbol.*

```mql5
_Symbol
```

---

### _Digits
*<int> Number of decimal places*

```mql5
_Digits
```

---

### _Point
*<double> Size of the current symbol point in the quote currency*

```mql5
_Point
```

---

### _LastError
*<int> last error code*

```mql5
_LastError
```

---

### _Period
*<ENUM_TIMEFRAMES> value of the timeframe of the current chart.*

```mql5
_Period
```

---

### _RandomSeed
*<int> Variable for storing the current state when generating pseudo-random integers*

```mql5
_RandomSeed
```

---

### _StopFlag
*<bool> contains the flag of the mql5-program stop*

```mql5
_StopFlag
```

---

### _UninitReason
*<int> contains the code of the program uninitialization reason.*

```mql5
_UninitReason
```

---

### Bid
*<double> bid*

```mql5
Bid
```

---

### Ask
*<double> ask*

```mql5
Ask
```

---

### Open[]
*<double> Series array that contains open prices of each bar of the current chart*

```mql5
Open[i]
```

---

### High[]
*<double> Series array that contains high prices of each bar of the current chart*

```mql5
High[i]
```

---

### Low[]
*<double> Series array that contains low prices of each bar of the current chart*

```mql5
Low[i]
```

---

### Close[]
*<double> Series array that contains close prices of each bar of the current chart*

```mql5
Close[i]
```

---

### Time[]
*<datetime> Series array that contains time of each bar of the current chart*

```mql5
Time[i]
```

---

### Volume[]
*<long> Series array that contains volume of each bar of the current chart*

```mql5
Volume[i]
```

---

### Alert
*<void> Displays a message in a separate window.*

```mql5
Alert(argument, ...)
```

---

### Check Pointer
*<ENUM_POINTER_TYPE> The function returns the type of the object pointer.*

```mql5
CheckPointer(object* anytype)
```

---

### Comment
*<void> outputs a comment defined by a user in the top left corner of a chart.*

```mql5
Comment(argument, ...)
```

---

### DebugBreak
*<void> sets a debug break point*

```mql5
DebugBreak()
```

---

### ExpertRemove
*<void> stops an Expert Advisor and unloads it from a chart.*

```mql5
ExpertRemove()
```

---

### GetPointer
*<void*> returns the object pointer.*

```mql5
GetPointer(object anytype)
```

---

### GetTickCount
*<uint> returns the number of milliseconds that elapsed since the system start*

```mql5
GetTickCount()
```

---

### GetMicrosecondCount
*<ulong> returns the number of microseconds that have elapsed since the start of MQL5-program.*

```mql5
GetMicrosecondCount()
```

---

### MessageBox
*<int> creates and shows a message box and manages it..*

```mql5
MessageBox(string  text, caption=NULL, int flags)
```

---

### PeriodSeconds
*<int> number of seconds in a period.*

```mql5
PeriodSeconds(ENUM_TIMEFRAMES=PERIOD_CURRENT)
```

---

### PlaySound
*<bool> plays a sound file.*

```mql5
PlaySound(string  filename)
```

---

### Print
*<void> enters a message in the Expert Advisor log. Parameters can be of any type.*

```mql5
Print(argument, ...)
```

---

### PrintFormat
*<void> formats and enters sets of symbols and values in the Expert Advisor log in accordance with a preset format.*

```mql5
PrintFormat(string format_string,  ...)
```

---

### ResetLastError
*<void> Sets the value of the predefined variable _LastError into zero.*

```mql5
ResetLastError()
```

---

### SendNotification
*<bool> Sends push notifications to the mobile terminals, whose MetaQuotes IDs are specified in the \*

```mql5
SendNotification(string text)
```

---

### SendMail
*<bool> Sends an email at the address specified in the settings window of the Email tab.*

```mql5
SendMail(string subject, string text)
```

---

### Sleep
*<void> The function suspends execution of the current Expert Advisor or script within a specified interval.*

```mql5
Sleep(int milliseconds)
```

---

### TranslateKey
*<short> Returns a Unicode character by a virtual key code considering the current input language and the status of control keys.*

```mql5
TranslateKey(int key_code)
```

---

### WebRequest
*<int> sends an HTTP request to a specified server. The function has two versions:*

```mql5
WebRequest(see docs)
```

---

### ZeroMemory
*<void> resets a variable passed to it by reference.*

```mql5
ZeroMemory(void &variable)
```

---

### ArraySize
*<int> The function returns the number of elements of a selected array..*

```mql5
ArraySize(const void& array[])
```

---

### ArrayGetAsSeries
*<bool> It checks direction of an array index..*

```mql5
ArrayGetAsSeries(const void& array[])
```

---

### ArraySetAsSeries
*<bool> The function sets the AS_SERIES flag to a selected object of a dynamic array, and elements will be indexed like in timeseries.*

```mql5
ArraySetAsSeries(const void& array[], ${bool flag})
```

---

### ArrayResize
*<int> The function sets a new size for the first dimension*

```mql5
ArrayResize(void& array[], int new_size,reserved_size=0)
```

---

### ArrayInitialize
*<int> initializes a numeric array by a preset value.*

```mql5
ArrayInitialize(T array[], T value)
```

---

### CharToString
*<tostring> Converting a symbol code into a one-character string.*

```mql5
CharToString(uchar char_code)
```

---

### CharArrayToString
*<string> It copies and converts part of array of uchar type into a returned string..*

```mql5
CharArrayToString(uchar array[], int start, int count=1, uint code_page=CP_ACP)
```

---

### ColorToString
*<string> It converts color value into string of R,G,B form.*

```mql5
ColorToString(color color, bool show_color_name)
```

---

### DoubleToString
*<string> Converting numeric value into text string.*

```mql5
DoubleToString(double value, int digits=8)
```

---

### EnumToString
*<string> Converting an enumeration value of any type to a text form.*

```mql5
EnumToString(any_enum value)
```

---

### TimeToString
*<string> Converting a value containing time in seconds elapsed since 01.01.1970 into a string of yyyy.mm.dd hh:mi format.*

```mql5
TimeToString(datetime value, int mode=TIME_DATE|TIME_MINUTES)
```

---

### NormalizeDouble
*<double> Rounding floating point number to a specified accuracy.*

```mql5
NormalizeDouble(double value, int digits)
```

---

### StringToCharArray
*<int> Symbol-wise copies a string converted from Unicode to ANSI, to a selected place of array of uchar type. It returns the number of copied elements.*

```mql5
StringToCharArray(string text_string, uchar& array[], int start=0, int count=-1, uint codepage=CP_ACP)
```

---

### StringToTime
*<datetime> converts a string containing time or date in yyyy.mm.dd [hh:mi] format into datetime type.*

```mql5
StringToTime(string value)
```

---

### StringFormat
*<string> The function formats obtained parameters and returns a string.*

```mql5
StringFormat(string format, params...)
```

---

### MathAbs
*<double> The function returns the absolute value (modulus) of the specified numeric value.*

```mql5
fabs(double value)
```

---

### MathPow
*<double> The function returns the absolute value (modulus) of the specified numeric value.*

```mql5
pow(double base, double exponent)
```

---

### MathArcsin
*<double> returns the arc sine of x within the range of -π/2 to π/2 radians.*

```mql5
asin(double value)
```

---

### MathArccos
*<double> returns the arccosine of x within the range 0 to π in radians.*

```mql5
acos(double value)
```

---

### MathCeil
*<double> returns integer numeric value closest from above.*

```mql5
ceil(double value)
```

---

### MathFloor
*<double> returns integer numeric value closest from below.*

```mql5
floor(double value)
```

---

### MathLog
*<double> returns a natural logarithm.*

```mql5
log(double value)
```

---

### MathLog10
*<double> Returns the logarithm of a number by base 10.*

```mql5
log10(double value)
```

---

### MathMax
* <double> returns the maximal value of two values.*

```mql5
fmax(double value1, double value2)
```

---

### MathMin
*<double> returns the minimal value of two values.*

```mql5
fmin(double value1, double value2)
```

---

### MathRand
*<int> Returns a pseudorandom integer within the range of 0 to 32767.*

```mql5
rand()
```

---

### MathSrand
*<void> Sets the starting point for generating a series of pseudorandom integers.*

```mql5
srand(${int seed})
```

---

### MathRound
*<double> returns a value rounded off to the nearest integer of the specified numeric value.*

```mql5
round(double value)
```

---

### MathIsValidNumber
*<bool> checks the correctness of a real number*

```mql5
MathIsValidNumber(double value)
```

---

### MathSqrt
*<double> Returns the square root of a number.*

```mql5
sqrt(double value)
```

---

### TimeCurrentStruct
*<datetime> MqlDateTime structure type variable has been passed as a parameter, it is filled accordingly*

```mql5
TimeCurrent(MqlDateTime struct)
```

---

### TimeCurrent
*<datetime> Returns the last known server time*

```mql5
TimeCurrent()
```

---

### TimeTradeServer
*<datetime> Returns the calculated current time of the trade server*

```mql5
TimeTradeServer()
```

---

### TimeLocal
*<datetime> Returns the local time of a computer*

```mql5
TimeLocal()
```

---

### TimeLocal Struct
*<datetime> Returns the local time of a computer; fills struct*

```mql5
TimeLocal(MqlDateTime &struct)
```

---

### TimeGMT
*<datetime> Returns the GMT, which is calculated taking into account the DST switch by the local time on the computer where the client terminal is running.*

```mql5
TimeGMT()
```

---

### TimeGMT Struct
*<datetime> Returns the GMT, which is calculated taking into account the DST switch by the local time on the computer where the client terminal is running.*

```mql5
TimeGMT(MqlDateTime &struct)
```

---

### TimeDaylightSavings
*<datetime> Returns correction for daylight saving time in seconds, if the switch to summer time has been made.*

```mql5
TimeDaylightSavings()
```

---

### TimeGMTOffset
*<datetime> Returns the current difference between GMT time and the local computer time in seconds*

```mql5
TimeGMTOffset()
```

---

### TimeToStruct
*<bool> Converts a value of datetime type (number of seconds since 01.01.1970) into a structure variable MqlDateTime.*

```mql5
TimeToStruct(datetime dt, MqlDateTime &struct)
```

---

### StructToTime
*<datetime> Converts a structure variable MqlDateTime into a value of datetime type and returns the resulting value.*

```mql5
StructToTime(MqlDateTime &struct)
```

---

### StringAdd
*<bool> adds a substring to the end of a string.*

```mql5
StringAdd(string& str_var, string add_substring)
```

---

### StringBufferLen
*<int> returns the size of buffer allocated for the string.*

```mql5
StringBufferLen(string string_var)
```

---

### StringCompare
*<int> compares two strings and returns the comparison result in form of an integer.Case sensitivity mode selection. If it is true, then A>a. If it is false, then A=a.*

```mql5
StringCompare(string str1, string str2,${bool case_sensitive=true})
```

---

### StringFill
*<bool> It fills out a selected string by specified symbols*

```mql5
StringFill(string& str_var, ushort character)
```

---

### StringFind
*<int> Search for a substring in a string.*

```mql5
StringFind(string value, string match_substring,int start_pos=0)
```

---

### StringGetCharacter
*<ushort> returns value of a symbol, located in the specified position of a string.*

```mql5
StringGetCharacter(string str_var, int pos)
```

---

### StringLen
*<int> Returns the number of symbols in a string*

```mql5
StringLen(string str_var)
```

---

### StringReplace
*<int> replaces all the found substrings of a string by a set sequence of symbols. The function returns the number of replacements in case of success, otherwise -1. To get an error code call the GetLastError() function.*

```mql5
StringReplace(string& str, string find, string replace)
```

---

### StringSplit
*<int> Gets substrings by a specified separator from the specified string, returns the number of substrings obtained.*

```mql5
StringSplit(string str, ushort separator, string &result[])
```

---

### StringSubstr
*<string> Extracts a substring from a text string starting from the specified position.*

```mql5
StringSubstr(string str, int start_pos, ${3:int length=-1)
```

---

### StringToLower
*<bool> Transforms all symbols of a selected string into lowercase.*

```mql5
StringToLower(string& str)
```

---

### StringToUpper
*<bool> Transforms all symbols of a selected string into capitals.*

```mql5
StringToUpper(string& str)
```

---

### StringTrimRight
*<int> The function cuts line feed characters, spaces and tabs in the right part of the string after the last meaningful symbol. The string is modified at place.*

```mql5
StringTrimRight(string& str)
```

---

### StringTrimLeft
*<int> The function cuts line feed characters, spaces and tabs in the left part of the string till the first meaningful symbol. The string is modified at place.*

```mql5
StringTrimLeft(string& str)
```

---

### AccountInfoDouble
*<double> Returns the value of the corresponding account property.*

```mql5
AccountInfoDouble(ENUM_ACOUNT_INFO_DOUBLE property_id)
```

---

### AccountInfoInteger
*<long> Returns the value of the corresponding account property.*

```mql5
AccountInfoInteger(ENUM_ACOUNT_INFO_INTEGER  property_id)
```

---

### AccountInfoString
*<string> Returns the value of the corresponding account property.*

```mql5
AccountInfoString(ENUM_ACOUNT_INFO_STRING  property_id)
```

---

### ACCOUNT_LOGIN
*<long> Account number*

```mql5
ACCOUNT_LOGIN
```

---

### ACCOUNT_TRADE_MODE
*<ENUM_ACCOUNT_TRADE_MODE> Account trade mode*

```mql5
ACCOUNT_TRADE_MODE
```

---

### ACCOUNT_LEVERAGE
*<long> Account leverage*

```mql5
ACCOUNT_LEVERAGE
```

---

### ACCOUNT_LIMIT_ORDERS
*<int> Maximum allowed number of active pending orders*

```mql5
ACCOUNT_LIMIT_ORDERS
```

---

### ACCOUNT_MARGIN_SO_MODE
*<ENUM_ACCOUNT_STOPOUT_MODE> Mode for setting the minimal allowed margin*

```mql5
ACCOUNT_MARGIN_SO_MODE
```

---

### ACCOUNT_TRADE_ALLOWED
*<bool> Allowed trade for the current account*

```mql5
ACCOUNT_TRADE_ALLOWED
```

---

### ACCOUNT_TRADE_EXPERT
*<bool> Allowed trade for an Expert Advisor*

```mql5
ACCOUNT_TRADE_EXPERT
```

---

### ACCOUNT_MARGIN_MODE
*<ENUM_ACCOUNT_MARGIN_MODE> Margin calculation mode*

```mql5
ACCOUNT_MARGIN_MODE
```

---

### GetLastError
*<int> Returns the contents of the system variable _LastError*

```mql5
GetLastError()
```

---

### IsStopped
*<bool> Checks the forced shutdown of an mql5 program*

```mql5
IsStopped()
```

---

### UninitializeReason
*<int> Returns the code of a reason for deinitialization.*

```mql5
UninitializeReason()
```

---

### TerminalInfoInteger
*<long> Returns the value of a corresponding property of the mql5 program environment*

```mql5
TerminalInfoInteger(int property_id)
```

---

### TerminalInfoDouble
*<double> Returns the value of a corresponding property of the mql5 program environment*

```mql5
TerminalInfoDouble(int property_id)
```

---

### TerminalInfoString
*<string> Returns the value of a corresponding property of the mql5 program environment*

```mql5
TerminalInfoString(int property_id)
```

---

### MQLInfoInteger
*<int> Returns the value of a corresponding property of a running mql5 program.*

```mql5
MQLInfoInteger(int property_id)
```

---

### MQLInfoString
*<string> Returns the value of a corresponding property of a running mql5 program.*

```mql5
MQLInfoString(int property_id)
```

---

### SymbolsTotal
*<int> Returns the number of available (selected in Market Watch or all) symbols.*

```mql5
SymbolsTotal(bool selected)
```

---

### SymbolName
*<string> returns the name of the symbol from the marketwatch window.*

```mql5
SymbolName(int pos, bool selected)
```

---

### SymbolSelect
*<bool> Selects a symbol in the Market Watch window or removes a symbol from the window.*

```mql5
SymbolSelect(string name, bool select)
```

---

### SymbolIsSynchronized
*<bool> The function checks whether data of a selected symbol in the terminal are synchronized with data on the trade server.*

```mql5
SymbolIsSynchronized(string name)
```

---

### SymbolInfoTick
*<bool> returns current prices of a specified symbol in a variable of the MqlTick type.*

```mql5
SymbolInfoTick(string name, MqlTick& tick)
```

---

### MarketBookAdd
*<bool> Provides opening of Depth of Market for a selected symbol, and subscribes for receiving notifications of the DOM changes.*

```mql5
MarketBookAdd(string name)
```

---

### MarketBookRelease
*<bool> Provides closing of Depth of Market for a selected symbol, and cancels the subscription for receiving notifications of the DOM changes.*

```mql5
MarketBookRelease(string name)
```

---

### MarketBookGet
*<bool> Returns a structure array MqlBookInfo containing records of the Depth of Market of a specified symbol.*

```mql5
MarketBookGet(string name, MqlBookInfo&  book[])
```

---

### SymbolInfoInteger
*<long> Returns the corresponding property of a specified symbol.*

```mql5
SymbolInfoInteger(string name, ENUM_SYMBOL_INFO_STRING prop_id)
```

---

### SymbolInfoString
*<string> Returns the corresponding property of a specified symbol.*

```mql5
SymbolInfoString(string name, ENUM_SYMBOL_INFO_INTEGER prop_id)
```

---

### SymbolInfoDouble
*<double> Returns the corresponding property of a specified symbol.*

```mql5
SymbolInfoDouble(string name, ENUM_SYMBOL_INFO_DOUBLE prop_id)
```

---

### SYMBOL_BID
*<double> Bid*

```mql5
SYMBOL_BID
```

---

### SYMBOL_ASK
*<double> Ask*

```mql5
SYMBOL_ASK
```

---

### SYMBOL_POINT
*<double> Symbol point value.*

```mql5
SYMBOL_POINT
```

---

### SYMBOL_TRADE_TICK_VALUE
*<double> Value of one tick*

```mql5
SYMBOL_TRADE_TICK_VALUE
```

---

### SYMBOL_TRADE_TICK_SIZE
*<double> Minimal price change*

```mql5
SYMBOL_TRADE_TICK_SIZE
```

---

### SYMBOL_VOLUME_MIN
*<double> Minimal volume for a deal*

```mql5
SYMBOL_VOLUME_MIN
```

---

### SYMBOL_VOLUME_MAX
*<double> Maximum volume for a deal.*

```mql5
SYMBOL_VOLUME_MAX
```

---

### SYMBOL_VOLUME_STEP
*<double> Minimal volume change step for deal execution*

```mql5
SYMBOL_VOLUME_STEP
```

---

### SYMBOL_MARGIN_INITIAL
*<double> Initial margin means the amount in the margin currency required for opening an order with the volume of one lot. It is used for checking a client's assets when he or she enters the market.*

```mql5
SYMBOL_MARGIN_INITIAL
```

---

### SYMBOL_CURRENCY_BASE
*<string> Basic currency of a symbol.*

```mql5
SYMBOL_CURRENCY_BASE
```

---

### SYMBOL_CURRENCY_PROFIT
*<string> Profit/counter currency of a symbol.*

```mql5
SYMBOL_CURRENCY_PROFIT
```

---

### SYMBOL_CURRENCY_MARGIN
*<string> Margin Currency*

```mql5
SYMBOL_CURRENCY_MARGIN
```

---

### SYMBOL_DESCRIPTION
*<string> Symbol Description.*

```mql5
SYMBOL_DESCRIPTION
```

---

### SYMBOL_SELECT
*<bool> Symbol is selected in Market Watch. Some symbols can be hidden in Market Watch, but still they are considered as selected.*

```mql5
SYMBOL_SELECT
```

---

### SYMBOL_DIGITS
*<int> Number of decimal places in the symbol quote.*

```mql5
SYMBOL_DIGITS
```

---

### SYMBOL_TIME
*<datetime> Time of the last quote.*

```mql5
SYMBOL_TIME
```

---

### SeriesInfoInteger
*<long> Returns information about the state of historical data.*

```mql5
SeriesInfoInteger(string name, ENUM_TIMEFRAMES timeframe, ENUM_SERIES_INFO_INTEGER prop_id)
```

---

### SERIES_BARS_COUNT
*<long> Bars count for the symbol-period for the current moment*

```mql5
SERIES_BARS_COUNT
```

---

### SERIES_FIRSTDATE
*<datetime> The very first date for the symbol-period for the current moment*

```mql5
SERIES_FIRSTDATE
```

---

### SERIES_LASTBAR_DATE
*<datetime> Open time of the last bar of the symbol-period*

```mql5
SERIES_LASTBAR_DATE
```

---

### SERIES_SERVER_FIRSTDATE
*<datetime> The very first date in the history of the symbol on the server regardless of the timeframe*

```mql5
SERIES_SERVER_FIRSTDATE
```

---

### Bars_From_To
*<int> Returns the number of bars count in the history for a specified symbol and period.*

```mql5
Bars(string name, ENUM_TIMEFRAMES timeframe, datetime start_time, datetime stop_time)
```

---

### Bars
*<int> Returns the number of bars count in the history for a specified symbol and period.*

```mql5
Bars(string name, ENUM_TIMEFRAMES timeframe)
```

---

### BarsCalculated
*<int> Returns the number of calculated data for the specified indicator*

```mql5
BarsCalculated(int ind_handle)
```

---

### IndicatorRelease
*<bool> removes an indicator handle and releases the calculation block of the indicator, if it's not used by anyone else.*

```mql5
IndicatorRelease(int ind_handle)
```

---

### CopyTicks
*<int> receives ticks in the MqlTick format into ticks_array.*

```mql5
CopyTicks(string symbol, MqlTick& tickarray[], uint flags=COPY_TICKS_ALL, ulong from=0, uint count=0)
```

---

### CopyBuffer
*<int> Gets data of a specified buffer of a certain indicator in the necessary quantity.*

```mql5
CopyBuffer(int handle, int buffer_number, int start_pos|datetime start_time, int count|datetime stop_time, double buffer[])
```

---

### CopyRates
*<int> Gets history data of MqlRates structure of a specified symbol-period in specified quantity into the rates_array array. The elements ordering of the copied data is from present to the past, i.e., starting position of 0 means the current bar.*

```mql5
CopyRates(string symbol, ENUM_TIMEFRAMES timeframe, int start_pos|datetime start_time, int count|datetime stop_time, MqlRates rates_array[])
```

---

### EventSetMillisecondTimer
*<bool> indicates to the client terminal that timer events should be generated at intervals less than one second for this Expert Advisor or indicator.*

```mql5
EventSetMillisecondTimer(int milliseconds)
```

---

### EventSetTimer
*<bool> indicates to the client terminal, that for this indicator or Expert Advisor, events from the timer must be generated with the specified periodicity.*

```mql5
EventSetTimer(int seconds)
```

---

### EventKillTimer
*<bool> Specifies the client terminal that is necessary to stop the generation of events from Timer.*

```mql5
EventKillTimer()
```

---

### EventChartCustom
*<bool> The function generates a custom event for the specified chart.*

```mql5
EventChartCustom()
```

---

### OrderClose
*<bool> Closes opened order.*

```mql5
OrderClose(int ticket, double lots, double price, int slippage, color arrow_color=clrNone)
```

---

### OrderCloseBy
*<bool> Closes an opened order by another opposite opened order.*

```mql5
OrderCloseBy(int ticket, int opposite, color arrow_color=clrNone)
```

---

### OrderClosePrice
*<double> Returns close price of the currently selected order. If the order is live this will return the price of which it is to be closed.*

```mql5
OrderClosePrice()
```

---

### OrderCloseTime
*<datetime> Returns close time of the currently selected order.*

```mql5
OrderCloseTime(int ticket, double lots, double price, int slippage, color arrow_color)
```

---

### OrderComment
*<string> Returns comment of the currently selected order.*

```mql5
OrderComment()
```

---

### OrderCommission
*<double> Returns calculated commission of the currently selected order.*

```mql5
OrderCommission()
```

---

### OrderDelete
*<bool> Deletes previously opened pending order.*

```mql5
OrderDelete(int ticket, color arrow_color=clrNone)
```

---

### OrderExpiration
*<datetime> Returns expiration date of the selected pending order.*

```mql5
OrderExpiration()
```

---

### OrderLots
*<double> Returns amount of lots of the selected order.*

```mql5
OrderLots()
```

---

### OrderMagicNumber
*<int> Returns an identifying (magic) number of the currently selected order.*

```mql5
OrderMagicNumber()
```

---

### OrderModify
*<bool> Modification of characteristics of the previously opened or pending orders.*

```mql5
OrderModify(int ticket, double price, double stoploss, double takeprofit, datetime expiration, color arrow_color=clrNone)
```

---

### OrderOpenPrice
*<double> Returns open price of the currently selected order.*

```mql5
OrderOpenPrice()
```

---

### OrderOpenTime
*<datetime> Returns open time of the currently selected order.*

```mql5
OrderOpenTime()
```

---

### OrderPrint
*<void> Prints information about the selected order in the log.*

```mql5
OrderPrint()
```

---

### OrderProfit
*<double> Returns profit of the currently selected order.*

```mql5
OrderProfit()
```

---

### OrderSelect
*<bool> The function selects an order for further processing.*

```mql5
OrderSelect(int position|int ticket, SELECT_BY_POS|SELECT_BY_TICKET, int pool=MODE_TRADES|MODE_HISTORY)
```

---

### OrderSend
*<int> The main function used to open market or place a pending order. Returns number of the ticket assigned to the order by the trade server or -1 if it fails.*

```mql5
OrderSend(string symbol, int cmd, double volume, double price, int slippage, double stoploss, double takeprofit, string comment=NULL, int magic=0, datetime expiration=0, color arrow_color=clrNONE)
```

---

### OrdersHistoryTotal
*<int> Returns the number of closed orders in the account history loaded into the terminal. *

```mql5
OrdersHistoryTotal)
```

---

### OrderStopLoss
*<double> Returns stoploss of the currently selected order.*

```mql5
OrderStopLoss(int ticket, double lots, double price, int slippage, color arrow_color)
```

---

### OrdersTotal
*<int> Returns the number of market and pending orders.*

```mql5
OrdersTotal()
```

---

### OrderSwap
*<double> Returns swap value of the currently selected order.*

```mql5
OrderSwap()
```

---

### OrderTakeProfit
*<datetime> Returns take profit value of the currently selected order.*

```mql5
OrderTakeProfit()
```

---

### OrderSymbol
*<string> Returns symbol of the currently selected order.*

```mql5
OrderSymbol()
```

---

### OrderTicket
*<int> Returns order ticket number of the currently selected order.*

```mql5
OrderTicket()
```

---

### OrderType
*<int> Returns order operation type of the currently selected order. OP_BUY=buy-order, OP_SELL=sell-order, OP_BUYLIMIT=buy-limit, OP_BUYSTOP=buy-stop, OP_SELLLIMIT=sell-limit, OP_SELLSTOP=sell-stop.*

```mql5
OrderType()
```

---

### iATR
*<double> Calculates the Average True Range indicator and returns its value*

```mql5
iATR(string symbol, int timeframe, int period, int shift)
```

---

### iADX
*<double> Calculates the Average Directional Movement Index indicator and returns its value.*

```mql5
iADX(string symbol, int timeframe, int period, int applied_price, int mode, int shift)
```

---

### iBands
*<double> Calculates the Bollinger Bands® indicator and returns its value.*

```mql5
iBands(string symbol, int timeframe, int period, double deviation, int bands_shift, int applied_price, int mode, int shift)
```

---

### iCustom
*<double> Calculates the specified custom indicator and returns its value. The custom indicator must be compiled (*.EX4 file) and be in the terminal_directory\\MQL4\\Indicators\\ directory.*

```mql5
iCustom(string symbol, int timeframe, string name,  ... , int buffer_index, int shift)
```

---

### iMA
*<double> Calculates the Moving Average indicator and returns its value. eg. iMA(NULL,0,13,8,MODE_SMMA,PRICE_MEDIAN,i);*

```mql5
iMA(string symbol, int timeframe, int ma_period, int ma_shift, int ma_method, int applied_price, int shift)
```

---

### iRSI
*<double> Calculates the RSI indicator and returns its value.*

```mql5
iRSI(string symbol, int timeframe, int period, int applied_price, int shift)
```

---

### iStochastic
*<double> Calculates the Moving Average indicator and returns its value. eg. iMA(NULL,0,13,8,MODE_SMMA,PRICE_MEDIAN,i);*

```mql5
iStochastic(string symbol, int timeframe, int Kperiod, int Dperiod, int slowing, int method, int price_field, int mode, int shift)
```

---

### ENUM_CHART_EVENT
*There are 9 types of events that can be processed using the predefined function OnChartEvent(). *

```mql5
ENUM_CHART_EVENT
```

---

### CHARTEVENT_KEYDOWN
*Keystrokes*

```mql5
CHARTEVENT_KEYDOWN
```

---

### CHARTEVENT_MOUSE_MOVE
*Mouse move, mouse clicks (if CHART_EVENT_MOUSE_MOVE=true is set for the chart)*

```mql5
CHARTEVENT_MOUSE_MOVE
```

---

### CHARTEVENT_OBJECT_CREATE
*Graphical object created (if CHART_EVENT_OBJECT_CREATE=true is set for the chart)*

```mql5
CHARTEVENT_OBJECT_CREATE
```

---

### CHARTEVENT_OBJECT_DELETE
*Graphical object deleted (if CHART_EVENT_OBJECT_DELETE=true is set for the chart)*

```mql5
CHARTEVENT_OBJECT_DELETE
```

---

### CHARTEVENT_OBJECT_CHANGE
*Graphical object property changed via the properties dialog*

```mql5
CHARTEVENT_OBJECT_CHANGE
```

---

### CHARTEVENT_CLICK
*Clicking on a graphical object*

```mql5
CHARTEVENT_CLICK
```

---

### CHARTEVENT_OBJECT_DRAG
*Drag and drop of a graphical object*

```mql5
CHARTEVENT_OBJECT_DRAG
```

---

### CHARTEVENT_OBJECT_ENDEDIT
*End of text editing in the graphical object Edit*

```mql5
CHARTEVENT_OBJECT_ENDEDIT
```

---

### CHARTEVENT_CHART_CHANGE
*Change of the chart size or modification of chart properties through the Properties dialog*

```mql5
CHARTEVENT_CHART_CHANGE
```

---

### CHARTEVENT_CUSTOM
*Initial number of an event from a range of custom events*

```mql5
CHARTEVENT_CUSTOM
```

---

### CHARTEVENT_CUSTOM_LAST
*The final number of an event from a range of custom events*

```mql5
CHARTEVENT_CUSTOM_LAST
```

---

### for forward
*mql4 orderselect loop*

```mql5
for(int i=0;i < int max_iter;i++)
{
   
}
```

---

### for backward
*mql4 orderselect loop*

```mql5
for(int i=int max_iter - 1;i >= 0 ;i--)
{
   
}
```

---

### for OrdersTotal
*mql4 orderselect loop*

```mql5
for(int i=OrdersTotal()-1;i>=0;i--)
{
   if(OrderSelect(i,SELECT_BY_POS) && OrderSymbol() == _Symbol  other conditions)
   {
      
   }
}
```

---

### for OrdersHistoryTotal
*mql4 orderselect loop*

```mql5
for(int i=OrdersHistoryTotal()-1;i>=0;i--)
{
   if(OrderSelect(i,SELECT_BY_POS,MODE_HISTORY) && OrderSymbol() == _Symbol  other conditions)
   {
      
   }
}
```

---

### OnStart
*Script entry point*

```mql5
void OnStart()
{
   
}
```

---

### Script_Template
```mql5

         

         

         
Copyright 2017, Author Name\
,
         
Link\
,
         
1.00\
,
         
,
         
,
         
,
         
,
         
,
         
,
         
,
         
,
         
```

---

### Expert_Template
*expert advisor template*

```mql5

         

         

         
Copyright 2017, Author Name\
,
         
Link\
,
         
1.00\
,
         
,
         
,
         
,
         
,
         

         
int OnInit()
{
   EventSetTimer(60);
   
   return(INIT_SUCCEEDED);
}

         

         
,
         
,
         
,
         
,
         
,
         

         
void OnTick()
{
   
}

         

         
,
         
,
         
,
         
,
         

         
void OnChartEvent(const int id,
                const long &lparam,
                const double &dparam,
                const string &sparam)
{
 
}
```

---

### Function Header
```mql5

         

         
,
         
,
         
,
         
```

---

### ChartXYToTimePrice
*Convert coordenate X|Y to time and price*

```mql5
ChartXYToTimePrice(int id, int cordX, int window, datetime resTime, double resPrice);
```

---

### ChartTimePriceToXY
*Convert time and price to coordenate X|Y*

```mql5
ChartTimePriceToXY(int id, int window, datetime time1, double price1, int cordX, int cordY);
```

---

### ChartNavigate
*Shift the chart to specific candle*

```mql5
ChartNavigate(int id, CHART_BEGIN | CHART_CURRENT_POS | CHART_END, int shift);
```

---

### ObjectCreate
*Setter for the object*

```mql5
ObjectSet(int idChart, string name, OBJTYPE, int window, datetime date, double price);
```

---

### ObjectSet
*Setter for the object*

```mql5
ObjectSet(string name, OBJPROP, VALUE)
```

---

### OBJPROP_PRICE1
*Set the property of price1 of the object*

```mql5
OBJPROP_PRICE1
```

---

### OBJPROP_PRICE2
*Set the property of price2 of the object*

```mql5
OBJPROP_PRICE2
```

---

### OBJPROP_PRICE3
*Set the property of price3 of the object*

```mql5
OBJPROP_PRICE3
```

---

### OBJPROP_TIME1
*Set the property of time1 of the object*

```mql5
OBJPROP_TIME1
```

---

### OBJPROP_TIME2
*Set the property of time2 of the object*

```mql5
OBJPROP_TIME2
```

---

### OBJPROP_TIME3
*Set the property of time3 of the object*

```mql5
OBJPROP_TIME3
```

---

### OBJPROP_TEXT
*Set the property of text of the object*

```mql5
OBJPROP_TEXT
```

---

### OBJPROP_SELECTED
*Set the property of the object selection*

```mql5
OBJPROP_SELECTED
```

---

### OBJPROP_ANGLE
*Set the angle*

```mql5
OBJPROP_ANGLE
```

---

### OBJPROP_COLOR
*Set the color*

```mql5
OBJPROP_COLOR
```

---

### OBJPROP_XDISTANCE
*Set the x distance in pixels*

```mql5
OBJPROP_XDISTANCE
```

---

### OBJPROP_YDISTANCE
*Set the y distance in pixels*

```mql5
OBJPROP_YDISTANCE
```

---

### OBJPROP_CORNER
*Set the corner of the ancle*

```mql5
OBJPROP_CORNER
```

---

### OBJPROP_BGCOLOR
*Set the background color*

```mql5
OBJPROP_BGCOLOR
```

---

### OBJPROP_FONTSIZE
*Set the size of text*

```mql5
OBJPROP_FONTSIZE
```

---

### OBJPROP_YSIZE
*Set the y size of the object*

```mql5
OBJPROP_YSIZE
```

---

### OBJPROP_XSIZE
*Set the x size of the object*

```mql5
OBJPROP_XSIZE
```

---

### OBJPROP_LEVELTEXT
*Set the fibo level*

```mql5
OBJPROP_LEVELTEXT
```

---

### OBJPROP_NAME
*Set or get the name of the object*

```mql5
OBJPROP_NAME
```

---

### OBJPROP_TIMEFRAMES
*Set or get the timeframe of the object*

```mql5
OBJPROP_TIMEFRAMES
```

---

### OBJPROP_WITH
*Set the with of the object*

```mql5
OBJPROP_WITH
```

---

### OBJPROP_FONT
*Set the font of the object*

```mql5
OBJPROP_FONT
```

---

### OBJPROP_HIDDEN
*Set the visibility of an object*

```mql5
OBJPROP_HIDDEN
```

---

### OBJPROP_SELECTABLE
*Set the if the object can be selected*

```mql5
OBJPROP_SELECTABLE
```

---

### CHART_WIDTH_IN_PIXELS
*Returns the value of the number of pixels in the <--x-->*

```mql5
CHART_WIDTH_IN_PIXELS
```

---

### ObjectsTotal
*Returns the number of objects in the chart (all periods)*

```mql5
ObjectsTotal()
```

---

### ObjectName
*Returns the number of objects in the chart (all periods)*

```mql5
ObjectName( object)
```

---

