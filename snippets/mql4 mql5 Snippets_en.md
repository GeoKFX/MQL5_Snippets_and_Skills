# MQL4/MQL5 Library (English Reference)

### AccountInfoDouble
(double) Returns the value of the appropriate account property.

```mql5
AccountInfoDouble
```

---

### AccountInfoInteger
(long) Returns the value of the appropriate account property.

```mql5
AccountInfoInteger
```

---

### AccountInfoString
(string) Returns the value of the appropriate account property.

```mql5
AccountInfoString
```

---

### acos
(double) The function returns the arccosine of x within the range 0 to π in radians.

```mql5
acos
```

---

### Alert
(void) Displays a message in a separate window.

```mql5
Alert
```

---

### ArrayBsearch
(int) Searches for a specified value in a multidimensional numeric array sorted ascending. Search is performed through the elements of the first dimension.

```mql5
ArrayBsearch
```

---

### ArrayCompare
(int) The function returns the result of comparing two arrays of the same type. It can be used to compare arrays of simple types or custom structures without complex objects, that is the custom structures that do not contain strings, dynamic arrays, classes and other structures with complex objects.

```mql5
ArrayCompare
```

---

### ArrayCopy
(int) It copies an array into another one.

```mql5
ArrayCopy
```

---

### ArrayFill
(void) The function fills an array with the specified value.

```mql5
ArrayFill
```

---

### ArrayFree
(void) It frees up a buffer of any dynamic array and sets the size of the zero dimension to 0.

```mql5
ArrayFree
```

---

### ArrayGetAsSeries
(bool) It checks direction of an array index.

```mql5
ArrayGetAsSeries
```

---

### ArrayInitialize
(int) The function initializes a numeric array by a preset value.

```mql5
ArrayInitialize
```

---

### ArrayIsDynamic
(bool) The function checks whether an array is dynamic.

```mql5
ArrayIsDynamic
```

---

### ArrayIsSeries
(bool) The function checks whether an array is a timeseries.

```mql5
ArrayIsSeries
```

---

### ArrayMaximum
(int) Searches for the largest element in the first dimension of a multidimensional numeric array.

```mql5
ArrayMaximum
```

---

### ArrayMinimum
(int) Searches for the lowest element in the first dimension of a multidimensional numeric array.

```mql5
ArrayMinimum
```

---

### ArrayRange
(int) The function returns the number of elements in a selected array dimension.

```mql5
ArrayRange
```

---

### ArrayResize
(int) The function sets a new size for the first dimension

```mql5
ArrayResize
```

---

### ArraySetAsSeries
(bool) The function sets the AS_SERIES flag to a selected object of a dynamic array, and elements will be indexed like in timeseries.

```mql5
ArraySetAsSeries
```

---

### ArraySize
(int) The function returns the number of elements of a selected array.

```mql5
ArraySize
```

---

### ArraySort
(bool) Sorts the values in the first dimension of a multidimensional numeric array in the ascending order.

```mql5
ArraySort
```

---

### ArrayPrint
(void) Prints an array of a simple type or a simple structure into journal.

```mql5
ArrayPrint
```

---

### ArrayInsert
(bool) Inserts the specified number of elements from a source array to a receiving one starting from a specified index.

```mql5
ArrayInsert
```

---

### ArrayRemove
(bool) Removes the specified number of elements from the array starting with a specified index.

```mql5
ArrayRemove
```

---

### ArrayReverse
(bool) Reverses the specified number of elements in the array starting with a specified index.

```mql5
ArrayReverse
```

---

### ArraySwap
(bool) Swaps the contents of two dynamic arrays of the same type. For multidimensional arrays, the number of elements in all dimensions except the first one should match.

```mql5
ArraySwap
```

---

### asin
(double) The function returns the arc sine of x within the range of -π/2 to π/2 radians.

```mql5
asin
```

---

### atan
(double) The function returns the arc tangent of x. If x is equal to 0, the function returns 0.

```mql5
atan
```

---

### Bars
(int) Returns the number of bars count in the history for a specified symbol and period. There are 2 variants of functions calls.

```mql5
Bars
```

---

### BarsCalculated
(int) Returns the number of calculated data for the specified indicator.

```mql5
BarsCalculated
```

---

### CalendarCountryById
(bool) Get a country description by its ID.

```mql5
CalendarCountryById
```

---

### CalendarEventById
(bool) Get an event description by its ID.

```mql5
CalendarEventById
```

---

### CalendarValueById
(bool) Get an event value description by its ID.

```mql5
CalendarValueById
```

---

### CalendarCountries
(int) Get the array of country names available in the Calendar.

```mql5
CalendarCountries
```

---

### CalendarEventByCountry
(int) Get the array of descriptions of all events available in the Calendar by a specified country code.

```mql5
CalendarEventByCountry
```

---

### CalendarEventByCurrency
(int) Get the array of descriptions of all events available in the Calendar by a specified currency.

```mql5
CalendarEventByCurrency
```

---

### CalendarValueHistoryByEvent
(bool) Get the array of values for all events in a specified time range by an event ID.

```mql5
CalendarValueHistoryByEvent
```

---

### CalendarValueHistory
(bool) Get the array of values for all events in a specified time range with the ability to sort by country and/or currency.

```mql5
CalendarValueHistory
```

---

### CalendarValueLastByEvent
(int) Get the array of event values by its ID since the Calendar database status with a specified change_id.

```mql5
CalendarValueLastByEvent
```

---

### CalendarValueLast
(int) Get the array of values for all events with the ability to sort by country and/or currency since the calendar database status with a specified change_id.

```mql5
CalendarValueLast
```

---

### ceil
(double) The function returns integer numeric value closest from above.

```mql5
ceil
```

---

### CharArrayToString
(string) It copies and converts part of array of uchar type into a returned string.

```mql5
CharArrayToString
```

---

### ChartApplyTemplate
(bool) Applies a specific template from a specified file to the chart. The command is added to chart messages queue and will be executed after processing of all previous commands.

```mql5
ChartApplyTemplate
```

---

### ChartClose
(bool) Closes the specified chart.

```mql5
ChartClose
```

---

### ChartFirst
(long) Returns the ID of the first chart of the client terminal.

```mql5
ChartFirst()
```

---

### ChartGetDouble
(bool) Returns the value of a corresponding property of the specified chart. Chart property must be of double type. There are 2 variants of the function calls.

```mql5
ChartGetDouble
```

---

### ChartGetInteger
(bool) Returns the value of a corresponding property of the specified chart. Chart property must be of datetime, int or bool type. There are 2 variants of the function calls.

```mql5
ChartGetInteger
```

---

### ChartGetString
(bool) Returns the value of a corresponding property of the specified chart. Chart property must be of string type. There are 2 variants of the function call.

```mql5
ChartGetString
```

---

### ChartID
(long) Returns the ID of the current chart.

```mql5
ChartID()
```

---

### ChartIndicatorAdd
(bool) Adds an indicator with the specified handle into a specified chart window. Indicator and chart should be generated on the same symbol and time frame.

```mql5
ChartIndicatorAdd
```

---

### ChartIndicatorDelete
(bool) Removes an indicator with a specified name from the specified chart window.

```mql5
ChartIndicatorDelete
```

---

### ChartIndicatorGet
(int) Returns the handle of the indicator with the specified short name in the specified chart window.

```mql5
ChartIndicatorGet
```

---

### ChartIndicatorName
(string) Returns the short name of the indicator by the number in the indicators list on the specified chart window.

```mql5
ChartIndicatorName
```

---

### ChartIndicatorsTotal
(int) Returns the number of all indicators applied to the specified chart window.

```mql5
ChartIndicatorsTotal
```

---

### ChartNavigate
(bool) Performs shift of the specified chart by the specified number of bars relative to the specified position in the chart.

```mql5
ChartNavigate
```

---

### ChartNext
(long) Returns the chart ID of the chart next to the specified one.

```mql5
ChartNext
```

---

### ChartOpen
(long) Opens a new chart with the specified symbol and period.

```mql5
ChartOpen
```

---

### CharToString
(string) Converting a symbol code into a one-character string

```mql5
CharToString
```

---

### ChartPeriod
(ENUM_TIMEFRAMES) Returns the timeframe period of specified chart.

```mql5
ChartPeriod
```

---

### ChartPriceOnDropped
(double) Returns the price coordinate corresponding to the chart point the Expert Advisor or script has been dropped to.

```mql5
ChartPriceOnDropped()
```

---

### ChartRedraw
(void) This function calls a forced redrawing of a specified chart.

```mql5
ChartRedraw
```

---

### ChartSaveTemplate
(bool) Saves current chart settings in a template with a specified name.

```mql5
ChartSaveTemplate
```

---

### ChartScreenShot
(bool) The function provides a screenshot of the chart in its current state in the GIF, PNG or BMP format depending on specified extension.

```mql5
ChartScreenShot
```

---

### ChartSetDouble
(bool) Sets a value for a corresponding property of the specified chart. Chart property should be of a double type. The command is added to chart messages queue and will be executed after processing of all previous commands.

```mql5
ChartSetDouble
```

---

### ChartSetInteger
(bool) Sets a value for a corresponding property of the specified chart. Chart property must be datetime, int, color, bool or char. The command is added to chart messages queue and will be executed after processing of all previous commands.

```mql5
ChartSetInteger
```

---

### ChartSetString
(bool) Sets a value for a corresponding property of the specified chart. Chart property must be of the string type. The command is added to chart messages queue and will be executed after processing of all previous commands.

```mql5
ChartSetString
```

---

### ChartSetSymbolPeriod
(bool) Changes the symbol and period of the specified chart. The function is asynchronous, i.e. it sends the command and does not wait for its execution completion. The command is added to chart messages queue and will be executed after processing of all previous commands.

```mql5
ChartSetSymbolPeriod
```

---

### ChartSymbol
(string) Returns the symbol name for the specified chart.

```mql5
ChartSymbol
```

---

### ChartTimeOnDropped
(datetime) Returns the time coordinate corresponding to the chart point the Expert Advisor or script has been dropped to.

```mql5
ChartTimeOnDropped()
```

---

### ChartTimePriceToXY
(bool) Converts the coordinates of a chart from the time/price representation to the X and Y coordinates.

```mql5
ChartTimePriceToXY
```

---

### ChartWindowFind
(int) The function returns the number of a subwindow where an indicator is drawn. There are 2 variants of the function.

```mql5
ChartWindowFind
```

---

### ChartWindowOnDropped
(int) Returns the number (index) of the chart subwindow the Expert Advisor or script has been dropped to. 0 means the main chart window.

```mql5
ChartWindowOnDropped()
```

---

### ChartXOnDropped
(int) Returns the X coordinate of the chart point the Expert Advisor or script has been dropped to.

```mql5
ChartXOnDropped()
```

---

### ChartXYToTimePrice
(bool) Converts the X and Y coordinates on a chart to the time and price values.

```mql5
ChartXYToTimePrice
```

---

### ChartYOnDropped
(int) Returns the Y coordinateof the chart point the Expert Advisor or script has been dropped to.

```mql5
ChartYOnDropped()
```

---

### CheckPointer
(ENUM_POINTER_TYPE) The function returns the type of the object pointer.

```mql5
CheckPointer
```

---

### CLBufferCreate
(int) Creates an OpenCL buffer and returns its handle.

```mql5
CLBufferCreate
```

---

### CLBufferFree
(void) Deletes an OpenCL buffer.

```mql5
CLBufferFree
```

---

### CLBufferRead
(uint) Reads an OpenCL buffer into an array and returns the number of read elements.

```mql5
CLBufferRead
```

---

### CLBufferWrite
(uint) Writes into the OpenCL buffer and returns the number of written elements.

```mql5
CLBufferWrite
```

---

### CLContextCreate
(int) Creates an OpenCL context and returns its handle.

```mql5
CLContextCreate
```

---

### CLContextFree
(void) Removes an OpenCL context.

```mql5
CLContextFree
```

---

### CLExecute
(bool) The function runs an OpenCL program. There are 3 versions of the function:

```mql5
CLExecute
```

---

### CLGetDeviceInfo
(bool) The function receives device property from OpenCL driver.

```mql5
CLGetDeviceInfo
```

---

### CLGetInfoInteger
(long) Returns the value of an integer property for an OpenCL object or device.

```mql5
CLGetInfoInteger
```

---

### CLHandleType
(ENUM_OPENCL_HANDLE_TYPE) Returns the type of an OpenCL handle as a value of the ENUM_OPENCL_HANDLE_TYPE enumeration.

```mql5
CLHandleType
```

---

### CLKernelCreate
(int) Creates the OpenCL program kernel and returns its handle.

```mql5
CLKernelCreate
```

---

### CLKernelFree
(void) Removes an OpenCL start function.

```mql5
CLKernelFree
```

---

### CLProgramCreate
(int) Creates an OpenCL program from a source code.

```mql5
CLProgramCreate
```

---

### CLProgramFree
(void) Removes an OpenCL program.

```mql5
CLProgramFree
```

---

### CLSetKernelArg
(bool) Sets a parameter for the OpenCL function.

```mql5
CLSetKernelArg
```

---

### CLSetKernelArgMem
(bool) Sets an OpenCL buffer as a parameter of the OpenCL function.

```mql5
CLSetKernelArgMem
```

---

### ColorToARGB
(uint) The function converts color type into uint type to get ARGB representation of the color. ARGB color format is used to generate a graphical resource, text display, as well as for CCanvas standard library class.

```mql5
ColorToARGB
```

---

### ColorToString
(string) It converts color value into string of "R,G,B" form.

```mql5
ColorToString
```

---

### Comment
(void) This function outputs a comment defined by a user in the top left corner of a chart.

```mql5
Comment
```

---

### CopyBuffer
(int) Gets data of a specified buffer of a certain indicator in the necessary quantity.

```mql5
CopyBuffer
```

---

### CopyClose
(int) The function gets into close_array the history data of bar close prices for the selected symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopyClose
```

---

### CopyHigh
(int) The function gets into high_array the history data of highest bar prices for the selected symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopyHigh
```

---

### CopyLow
(int) The function gets into low_array the history data of minimal bar prices for the selected symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopyLow
```

---

### CopyOpen
(int) The function gets into open_array the history data of bar open prices for the selected symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopyOpen
```

---

### CopyRates
(int) Gets history data of MqlRates structure of a specified symbol-period in specified quantity into the rates_array array. The elements ordering of the copied data is from present to the past, i.e., starting position of 0 means the current bar.

```mql5
CopyRates
```

---

### CopyRealVolume
(int) The function gets into volume_array the history data of trade volumes for the selected symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopyRealVolume
```

---

### CopySpread
(int) The function gets into spread_array the history data of spread values for the selected symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopySpread
```

---

### CopyTicks
(int) The function receives ticks in the MqlTick format into ticks_array. In this case, ticks are indexed from the past to the present, i.e. the 0 indexed tick is the oldest one in the array. For tick analysis, check the flags field, which shows what exactly has changed in the tick.

```mql5
CopyTicks
```

---

### CopyTickVolume
(int) The function gets into volume_array the history data of tick volumes for the selected symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopyTickVolume
```

---

### CopyTime
(int) The function gets to time_array history data of bar opening time for the specified symbol-period pair in the specified quantity. It should be noted that elements ordering is from present to past, i.e., starting position of 0 means the current bar.

```mql5
CopyTime
```

---

### cos
(double) The function returns the cosine of an angle.

```mql5
cos
```

---

### CryptDecode
(int) Performs the inverse transformation of the data from array, tranformed by CryptEncode().

```mql5
CryptDecode
```

---

### CryptEncode
(int) Transforms the data from array with the specified method.

```mql5
CryptEncode
```

---

### CustomSymbolCreate
(bool) Creates a custom symbol with the specified name in the specified group.

```mql5
CustomSymbolCreate
```

---

### CustomSymbolDelete
(bool) Deletes a custom symbol with the specified name.

```mql5
CustomSymbolDelete
```

---

### CustomSymbolSetInteger
(bool) Sets the integer type property value for a custom symbol.

```mql5
CustomSymbolSetInteger
```

---

### CustomSymbolSetDouble
(bool) Sets the real type property value for a custom symbol.

```mql5
CustomSymbolSetDouble
```

---

### CustomSymbolSetString
(bool) Sets the string type property value for a custom symbol.

```mql5
CustomSymbolSetString
```

---

### CustomSymbolSetMarginRate
(bool) Sets the margin rates depending on the order type and direction for a custom symbol.

```mql5
CustomSymbolSetMarginRate
```

---

### CustomSymbolSetSessionQuote
(bool) Sets the start and end time of the specified quotation session for the specified symbol and week day.

```mql5
CustomSymbolSetSessionQuote
```

---

### CustomSymbolSetSessionTrade
(bool) Sets the start and end time of the specified trading session for the specified symbol and week day.

```mql5
CustomSymbolSetSessionTrade
```

---

### CustomRatesDelete
(int) Deletes all bars from the price history of the custom symbol in the specified time interval.

```mql5
CustomRatesDelete
```

---

### CustomRatesReplace
(int) Fully replaces the price history of the custom symbol within the specified time interval with the data from the MqlRates type array.

```mql5
CustomRatesReplace
```

---

### CustomRatesUpdate
(int) Adds missing bars to the custom symbol history and replaces existing data with  the ones from the MqlRates type array.

```mql5
CustomRatesUpdate
```

---

### CustomTicksAdd
(int) Adds data from an array of the MqlTick type to the price history of a custom symbol. The custom symbol must be selected in the Market Watch window.

```mql5
CustomTicksAdd
```

---

### CustomTicksDelete
(int) Deletes all ticks from the price history of the custom symbol in the specified time interval.

```mql5
CustomTicksDelete
```

---

### CustomTicksReplace
(int) Fully replaces the price history of the custom symbol within the specified time interval with the data from the MqlTick type array.

```mql5
CustomTicksReplace
```

---

### CustomBookAdd
(int) Passes the status of the Depth of Market for a custom symbol. The function allows broadcasting the Depth of Market as if the prices arrive from a broker's server.

```mql5
CustomBookAdd
```

---

### DatabaseOpen
(int) Opens or creates a database in a specified file.

```mql5
DatabaseOpen
```

---

### DatabaseClose
(void) Closes a database.

```mql5
DatabaseClose
```

---

### DatabaseImport
(long) Imports data from a file into a table.

```mql5
DatabaseImport
```

---

### DatabaseExport
(long) Exports a table or an SQL request execution result to a CSV file. The file is created in the UTF-8 encoding.

```mql5
DatabaseExport
```

---

### DatabasePrint
(long) Prints a table or an SQL request execution result in the Experts journal.

```mql5
DatabasePrint
```

---

### DatabaseTableExists
(bool) Checks the presence of the table in a database.

```mql5
DatabaseTableExists
```

---

### DatabaseExecute
(bool) Executes a request to a specified database.

```mql5
DatabaseExecute
```

---

### DatabasePrepare
(int) Creates a handle of a request, which can then be executed using DatabaseRead().

```mql5
DatabasePrepare
```

---

### DatabaseReset
(int) Resets a request, like after calling DatabasePrepare().

```mql5
DatabaseReset
```

---

### DatabaseBind
(bool) Sets a parameter value in a request.

```mql5
DatabaseBind
```

---

### DatabaseBindArray
(bool) Sets an array as a parameter value.

```mql5
DatabaseBindArray
```

---

### DatabaseRead
(bool) Moves to the next entry as a result of a request.

```mql5
DatabaseRead
```

---

### DatabaseReadBind
(bool) Moves to the next record and reads data into the structure from it.

```mql5
DatabaseReadBind
```

---

### DatabaseFinalize
(void) Removes a request created in DatabasePrepare().

```mql5
DatabaseFinalize
```

---

### DatabaseTransactionBegin
(bool) Starts transaction execution.

```mql5
DatabaseTransactionBegin
```

---

### DatabaseTransactionCommit
(bool) Completes transaction execution.

```mql5
DatabaseTransactionCommit
```

---

### DatabaseTransactionRollback
(bool) Rolls back transactions.

```mql5
DatabaseTransactionRollback
```

---

### DatabaseColumnsCount
(int) Gets the number of fields in a request.

```mql5
DatabaseColumnsCount
```

---

### DatabaseColumnName
(bool) Gets a field name by index.

```mql5
DatabaseColumnName
```

---

### DatabaseColumnType
(ENUM_DATABASE_FIELD_TYPE) Gets a field type by index.

```mql5
DatabaseColumnType
```

---

### DatabaseColumnSize
(int) Gets a field size in bytes.

```mql5
DatabaseColumnSize
```

---

### DatabaseColumnText
(bool) Gets a field value as a string from the current record.

```mql5
DatabaseColumnText
```

---

### DatabaseColumnInteger
(bool) Gets the int type value from the current record.

```mql5
DatabaseColumnInteger
```

---

### DatabaseColumnLong
(bool) Gets the long type value from the current record.

```mql5
DatabaseColumnLong
```

---

### DatabaseColumnDouble
(bool) Gets the double type value from the current record.

```mql5
DatabaseColumnDouble
```

---

### DatabaseColumnBlob
(bool) Gets a field value as an array from the current record.

```mql5
DatabaseColumnBlob
```

---

### DebugBreak
(void) It is a program breakpoint in debugging.

```mql5
DebugBreak()
```

---

### Digits
(int) Returns the number of decimal digits determining the accuracy of price of the current chart symbol.

```mql5
Digits()
```

---

### DoubleToString
(string) Converting numeric value into text string.

```mql5
DoubleToString
```

---

### DXContextCreate
(int) Creates a graphic context for rendering frames of a specified size.

```mql5
DXContextCreate
```

---

### DXContextSetSize
(bool) Changes a frame size of a graphic context created in DXContextCreate().

```mql5
DXContextSetSize
```

---

### DXContextClearColors
(bool) Sets a specified color to all pixels for the rendering buffer.

```mql5
DXContextClearColors
```

---

### DXContextClearDepth
(bool) Clears the depth buffer.

```mql5
DXContextClearDepth
```

---

### DXContextGetColors
(bool) Gets an image of a specified size and offset from a graphic context.

```mql5
DXContextGetColors
```

---

### DXContextGetDepth
(bool) Gets the depth buffer of a rendered frame.

```mql5
DXContextGetDepth
```

---

### DXBufferCreate
(int) Creates a buffer of a specified type based on a data array.

```mql5
DXBufferCreate
```

---

### DXTextureCreate
(int) Creates a 2D texture out of a rectangle of a specified size cut from a passed image.

```mql5
DXTextureCreate
```

---

### DXInputCreate
(int) Creates shader inputs.

```mql5
DXInputCreate
```

---

### DXInputSet
(bool) Sets shader inputs.

```mql5
DXInputSet
```

---

### DXShaderCreate
(int) Creates a shader of a specified type.

```mql5
DXShaderCreate
```

---

### DXShaderSetLayout
(bool) Sets vertex layout for the vertex shader.

```mql5
DXShaderSetLayout
```

---

### DXShaderInputsSet
(bool) Sets shader inputs.

```mql5
DXShaderInputsSet
```

---

### DXShaderTexturesSet
(bool) Sets shader textures.

```mql5
DXShaderTexturesSet
```

---

### DXDraw
(bool) Renders the vertices of the vertex buffer set in DXBufferSet().

```mql5
DXDraw
```

---

### DXDrawIndexed
(bool) Renders graphic primitives described by the index buffer from DXBufferSet().

```mql5
DXDrawIndexed
```

---

### DXPrimiveTopologySet
(bool) Sets the type of primitives for rendering using DXDrawIndexed().

```mql5
DXPrimiveTopologySet
```

---

### DXBufferSet
(bool) Sets a buffer for the current rendering.

```mql5
DXBufferSet
```

---

### DXShaderSet
(bool) Sets a shader for rendering.

```mql5
DXShaderSet
```

---

### DXHandleType
(ENUM_DX_HANDLE_TYPE) Returns a handle type.

```mql5
DXHandleType
```

---

### DXRelease
(bool) Releases a handle.

```mql5
DXRelease
```

---

### EnumToString
(string) Converting an enumeration value of any type to a text form.

```mql5
EnumToString
```

---

### EventChartCustom
(bool) The function generates a custom event for the specified chart.

```mql5
EventChartCustom
```

---

### EventKillTimer
(void) Specifies the client terminal that is necessary to stop the generation of events from Timer.

```mql5
EventKillTimer()
```

---

### EventSetMillisecondTimer
(bool) The function indicates to the client terminal that timer events should be generated at intervals less than one second for this Expert Advisor or indicator.

```mql5
EventSetMillisecondTimer
```

---

### EventSetTimer
(bool) The function indicates to the client terminal, that for this indicator or Expert Advisor, events from the timer must be generated with the specified periodicity.

```mql5
EventSetTimer
```

---

### exp
(double) The function returns the value of e raised to the power of d.

```mql5
exp
```

---

### ExpertRemove
(void) The function stops an Expert Advisor and unloads it from a chart.

```mql5
ExpertRemove()
```

---

### fabs
(double) The function returns the absolute value (modulus) of the specified numeric value.

```mql5
fabs
```

---

### FileClose
(void) Close the file previously opened by FileOpen().

```mql5
FileClose
```

---

### FileCopy
(bool) The function copies the original file from a local or shared folder to another file.

```mql5
FileCopy
```

---

### FileDelete
(bool) Deletes the specified file in a local folder of the client terminal.

```mql5
FileDelete
```

---

### FileFindClose
(void) The function closes the search handle.

```mql5
FileFindClose
```

---

### FileFindFirst
(long) The function starts the search of files or subdirectories in a directory in accordance with the specified filter.

```mql5
FileFindFirst
```

---

### FileFindNext
(bool) The function continues the search started by FileFindFirst().

```mql5
FileFindNext
```

---

### FileFlush
(void) Writes to a disk all data remaining in the input/output file buffer.

```mql5
FileFlush
```

---

### FileGetInteger
(long) Gets an integer property of a file. There are two variants of the function.

```mql5
FileGetInteger
```

---

### FileIsEnding
(bool) Defines the end of a file in the process of reading.

```mql5
FileIsEnding
```

---

### FileIsExist
(bool) Checks the existence of a file.

```mql5
FileIsExist
```

---

### FileIsLineEnding
(bool) Defines the line end in a text file in the process of reading.

```mql5
FileIsLineEnding
```

---

### FileMove
(bool) Moves a file from a local or shared folder to another folder.

```mql5
FileMove
```

---

### FileOpen
(int) The function opens the file with the specified name and flag.

```mql5
FileOpen
```

---

### FileReadArray
(uint) Reads from a file of BIN type arrays of any type except string (may be an array of structures, not containing strings, and dynamic arrays).

```mql5
FileReadArray
```

---

### FileReadBool
(bool) Reads from the file of CSV type string from the current position to a delimiter (or till the end of the text line) and converts the read string to a bool type value.

```mql5
FileReadBool
```

---

### FileReadDatetime
(datetime) Reads from the file of CSV type a string of one of the formats: "YYYY.MM.DD HH:MI:SS", "YYYY.MM.DD" or "HH:MI:SS" - and converts it into a value of datetime type.

```mql5
FileReadDatetime
```

---

### FileReadDouble
(double) Reads a double-precision floating point number (double) from the current position of the binary file.

```mql5
FileReadDouble
```

---

### FileReadFloat
(float) Reads the single-precision floating point number (float) from the current position of the binary file.

```mql5
FileReadFloat
```

---

### FileReadInteger
(int) The function reads int, short or char value from the current position of the file pointer depending on the length specified in bytes.

```mql5
FileReadInteger
```

---

### FileReadLong
(long) The function reads an integer of long type (8 bytes) from the current position of the binary file.

```mql5
FileReadLong
```

---

### FileReadNumber
(double) The function reads from the CSV file a string from the current position till a separator (or till the end of a text string) and converts the read string to a value of double type.

```mql5
FileReadNumber
```

---

### FileReadString
(string) The function reads a string from the current position of a file pointer in a file.

```mql5
FileReadString
```

---

### FileReadStruct
(uint) The function reads contents into a structure passed as a parameter from a binary-file, starting with the current position of the file pointer.

```mql5
FileReadStruct
```

---

### FileSeek
(bool) The function moves the position of the file pointer by a specified number of bytes relative to the specified position.

```mql5
FileSeek
```

---

### FileSize
(ulong) The function returns the file size in bytes.

```mql5
FileSize
```

---

### FileTell
(ulong) The file returns the current position of the file pointer of an open file.

```mql5
FileTell
```

---

### FileWrite
(uint) The function is intended for writing of data into a CSV file, delimiter being inserted automatically unless it is equal to 0. After writing into the file, the line end character "\r\n" will be added.

```mql5
FileWrite
```

---

### FileWriteArray
(uint) The function writes arrays of any type except for string to a BIN file (can be an array of structures not containing strings or dynamic arrays).

```mql5
FileWriteArray
```

---

### FileWriteDouble
(uint) The function writes the value of a double parameter to a a bin-file, starting from the current position of the file pointer.

```mql5
FileWriteDouble
```

---

### FileWriteFloat
(uint) The function writes the value of the float parameter to a bin-file, starting from the current position of the file pointer.

```mql5
FileWriteFloat
```

---

### FileWriteInteger
(uint) The function writes the value of the int parameter to a bin-file, starting from the current position of the file pointer.

```mql5
FileWriteInteger
```

---

### FileWriteLong
(uint) The function writes the value of the long-type parameter to a bin-file, starting from the current position of the file pointer.

```mql5
FileWriteLong
```

---

### FileWriteString
(uint) The function writes the value of a string-type parameter into a BIN, CSV or TXT file starting from the current position of the file pointer. When writing to a CSV or TXT file: if there is a symbol in the string '\n' (LF) without previous character '\r' (CR), then before '\n' the missing '\r' is added.

```mql5
FileWriteString
```

---

### FileWriteStruct
(uint) The function writes into a bin-file contents of a structure passed as a parameter, starting from the current position of the file pointer.

```mql5
FileWriteStruct
```

---

### floor
(double) The function returns integer numeric value closest from below.

```mql5
floor
```

---

### fmax
(double) The function returns the maximal value of two values.

```mql5
fmax
```

---

### fmin
(double) The function returns the minimal value of two values.

```mql5
fmin
```

---

### fmod
(double) The function returns the real remainder of division of two numbers.

```mql5
fmod
```

---

### FolderClean
(bool) The function deletes all files in a specified folder.

```mql5
FolderClean
```

---

### FolderCreate
(bool) Creates a directory in the Files folder (depending on the common_flag value)

```mql5
FolderCreate
```

---

### FolderDelete
(bool) The function removes the specified directory. If the folder is not empty, then it can't be removed.

```mql5
FolderDelete
```

---

### FrameAdd
(bool) Adds a frame with data. There are two variants of the function.

```mql5
FrameAdd
```

---

### FrameFilter
(bool) Sets the frame reading filter and moves the pointer to the beginning.

```mql5
FrameFilter
```

---

### FrameFirst
(bool) Moves a pointer of frame reading to the beginning and resets a set filter.

```mql5
FrameFirst()
```

---

### FrameInputs
(bool) Receives input parameters, on which the frame with the specified pass number is formed.

```mql5
FrameInputs
```

---

### FrameNext
(bool) Reads a frame and moves the pointer to the next one. There are two variants of the function.

```mql5
FrameNext
```

---

### GetLastError
(int) Returns the contents of the system variable _LastError.

```mql5
GetLastError()
```

---

### GetPointer
(void) The function returns the object pointer.

```mql5
GetPointer
```

---

### GetTickCount
(uint) The GetTickCount() function returns the number of milliseconds that elapsed since the system start.

```mql5
GetTickCount()
```

---

### GlobalVariableCheck
(bool) Checks the existence of a global variable with the specified name

```mql5
GlobalVariableCheck
```

---

### GlobalVariableDel
(bool) Deletes a global variable from the client terminal.

```mql5
GlobalVariableDel
```

---

### GlobalVariableGet
(bool) Returns the value of an existing global variable of the client terminal. There are 2 variants of the function.

```mql5
GlobalVariableGet
```

---

### GlobalVariableName
(string) Returns the name of a global variable by its ordinal number.

```mql5
GlobalVariableName
```

---

### GlobalVariablesDeleteAll
(int) Deletes global variables of the client terminal.

```mql5
GlobalVariablesDeleteAll
```

---

### GlobalVariableSet
(datetime) Sets a new value for a global variable. If the variable does not exist, the system creates a new global variable.

```mql5
GlobalVariableSet
```

---

### GlobalVariableSetOnCondition
(bool) Sets the new value of the existing global variable if the current value equals to the third parameter check_value. If there is no global variable, the function will generate an error ERR_GLOBALVARIABLE_NOT_FOUND (4501) and return false.

```mql5
GlobalVariableSetOnCondition
```

---

### GlobalVariablesFlush
(void) Forcibly saves contents of all global variables to a disk.

```mql5
GlobalVariablesFlush()
```

---

### GlobalVariablesTotal
(int) Returns the total number of global variables of the client terminal.

```mql5
GlobalVariablesTotal()
```

---

### GlobalVariableTemp
(bool) The function attempts to create a temporary global variable. If the variable doesn't exist, the system creates a new temporary global variable.

```mql5
GlobalVariableTemp
```

---

### GlobalVariableTime
(datetime) Returns the time when the global variable was last accessed.

```mql5
GlobalVariableTime
```

---

### HistoryDealGetDouble
(bool) Returns the requested property of a deal. The deal property must be of the double type. There are 2 variants of the function.

```mql5
HistoryDealGetDouble
```

---

### HistoryDealGetInteger
(bool) Returns the requested property of a deal. The deal property must be of the datetime, int type. There are 2 variants of the function.

```mql5
HistoryDealGetInteger
```

---

### HistoryDealGetString
(bool) Returns the requested property of a deal. The deal property must be of the string type. There are 2 variants of the function.

```mql5
HistoryDealGetString
```

---

### HistoryDealGetTicket
(ulong) The function selects a deal for further processing and returns the deal ticket in history. Prior to calling HistoryDealGetTicket(), first it is necessary to receive the history of deals and orders using the HistorySelect() or HistorySelectByPosition() function.

```mql5
HistoryDealGetTicket
```

---

### HistoryDealSelect
(bool) Selects a deal in the history for further calling it through appropriate functions. It returns true if the function has been successfully completed. Returns false if the function has failed. For more details on error call GetLastError().

```mql5
HistoryDealSelect
```

---

### HistoryDealsTotal
(int) Returns the number of deal in history. Prior to calling HistoryDealsTotal(), first it is necessary to receive the history of deals and orders using the HistorySelect() or HistorySelectByPosition() function.

```mql5
HistoryDealsTotal()
```

---

### HistoryOrderGetDouble
(bool) Returns the requested order property. The order property must be of the double type. There are 2 variants of the function.

```mql5
HistoryOrderGetDouble
```

---

### HistoryOrderGetInteger
(bool) Returns the requested property of an order. The order property must be of datetime, int type. There are 2 variants of the function.

```mql5
HistoryOrderGetInteger
```

---

### HistoryOrderGetString
(bool) Returns the requested property of an order. The order property must be of the string type. There are 2 variants of the function.

```mql5
HistoryOrderGetString
```

---

### HistoryOrderGetTicket
(ulong) Return the ticket of a corresponding order in the history. Prior to calling HistoryOrderGetTicket(), first it is necessary to receive the history of deals and orders using the HistorySelect() or HistorySelectByPosition() function.

```mql5
HistoryOrderGetTicket
```

---

### HistoryOrderSelect
(bool) Selects an order from the history for further calling it through appropriate functions. It returns true if the function has been successfully completed. Returns false if the function has failed. For more details on error call GetLastError().

```mql5
HistoryOrderSelect
```

---

### HistoryOrdersTotal
(int) Returns the number of orders in the history. Prior to calling HistoryOrdersTotal(), first it is necessary to receive the history of deals and orders using the HistorySelect() or HistorySelectByPosition() function.

```mql5
HistoryOrdersTotal()
```

---

### HistorySelect
(bool) Retrieves the history of deals and orders for the specified period of server time.

```mql5
HistorySelect
```

---

### HistorySelectByPosition
(bool) Retrieves the history of deals and orders having the specified position identifier.

```mql5
HistorySelectByPosition
```

---

### iBars
(int) Returns the number of bars of a corresponding symbol and period, available in history.

```mql5
iBars
```

---

### iBarShift
(int) Search bar by time. The function returns the index of the bar corresponding to the specified time.

```mql5
iBarShift
```

---

### iClose
(double) Returns the Close price of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iClose
```

---

### iHigh
(double) Returns the High price of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iHigh
```

---

### iHighest
(int) Returns the index of the highest value found on the corresponding chart (shift relative to the current bar).

```mql5
iHighest
```

---

### iLow
(double) Returns the Low price of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iLow
```

---

### iLowest
(int) Returns the index of the smallest value found on the corresponding chart (shift relative to the current bar).

```mql5
iLowest
```

---

### iOpen
(double) Returns the Open price of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iOpen
```

---

### iTime
(datetime) Returns the opening time of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iTime
```

---

### iTickVolume
(long) Returns the tick volume of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iTickVolume
```

---

### iRealVolume
(long) Returns the real volume of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iRealVolume
```

---

### iVolume
(long) Returns the tick volume of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iVolume
```

---

### iSpread
(long) Returns the spread value of the bar (indicated by the 'shift' parameter) on the corresponding chart.

```mql5
iSpread
```

---

### iAD
(int) The function returns the handle of the Accumulation/Distribution indicator. It has only one buffer.

```mql5
iAD
```

---

### iADX
(int) The function returns the handle of the Average Directional Movement Index indicator.

```mql5
iADX
```

---

### iADXWilder
(int) The function returns the handle of Average Directional Movement Index by Welles Wilder.

```mql5
iADXWilder
```

---

### iAlligator
(int) The function returns the handle of the Alligator indicator.

```mql5
iAlligator
```

---

### iAMA
(int) The function returns the handle of the Adaptive Moving Average indicator. It has only one buffer.

```mql5
iAMA
```

---

### iAO
(int) The function returns the handle of the Awesome Oscillator indicator. It has only one buffer.

```mql5
iAO
```

---

### iATR
(int) The function returns the handle of the Average True Range indicator. It has only one buffer.

```mql5
iATR
```

---

### iBands
(int) The function returns the handle of the Bollinger Bands® indicator.

```mql5
iBands
```

---

### iBearsPower
(int) The function returns the handle of the Bears Power indicator. It has only one buffer.

```mql5
iBearsPower
```

---

### iBullsPower
(int) The function returns the handle of the Bulls Power indicator. It has only one buffer.

```mql5
iBullsPower
```

---

### iBWMFI
(int) The function returns the handle of the Market Facilitation Index indicator. It has only one buffer.

```mql5
iBWMFI
```

---

### iCCI
(int) The function returns the handle of the Commodity Channel Index indicator. It has only one buffer.

```mql5
iCCI
```

---

### iChaikin
(int) The function returns the handle of the Chaikin Oscillator indicator. It has only one buffer.

```mql5
iChaikin
```

---

### iCustom
(int) The function returns the handle of a specified custom indicator.

```mql5
iCustom
```

---

### iDEMA
(int) The function returns the handle of the Double Exponential Moving Average indicator. It has only one buffer.

```mql5
iDEMA
```

---

### iDeMarker
(int) The function returns the handle of the DeMarker indicator. It has only one buffer.

```mql5
iDeMarker
```

---

### iEnvelopes
(int) The function returns the handle of the Envelopes indicator.

```mql5
iEnvelopes
```

---

### iForce
(int) The function returns the handle of the Force Index indicator. It has only one buffer.

```mql5
iForce
```

---

### iFractals
(int) The function returns the handle of the Fractals indicator.

```mql5
iFractals
```

---

### iFrAMA
(int) The function returns the handle of the Fractal Adaptive Moving Average indicator. It has only one buffer.

```mql5
iFrAMA
```

---

### iGator
(int) The function returns the handle of the Gator indicator. The Oscillator shows the difference between the blue and red lines of Alligator (upper histogram) and difference between red and green lines (lower histogram).

```mql5
iGator
```

---

### iIchimoku
(int) The function returns the handle of the Ichimoku Kinko Hyo indicator.

```mql5
iIchimoku
```

---

### iMA
(int) The function returns the handle of the Moving Average indicator. It has only one buffer.

```mql5
iMA
```

---

### iMACD
(int) The function returns the handle of the Moving Averages Convergence/Divergence indicator. In systems where OsMA is called MACD Histogram, this indicator is shown as two lines. In the client terminal the Moving Averages Convergence/Divergence looks like a histogram.

```mql5
iMACD
```

---

### iMFI
(int) The function returns the handle of the Money Flow Index indicator.

```mql5
iMFI
```

---

### iMomentum
(int) The function returns the handle of the Momentum indicator. It has only one buffer.

```mql5
iMomentum
```

---

### IndicatorCreate
(int) The function returns the handle of a specified technical indicator created based on the array of parameters of MqlParam type.

```mql5
IndicatorCreate
```

---

### IndicatorParameters
(int) Based on the specified handle, returns the number of input parameters of the indicator, as well as the values and types of the parameters.

```mql5
IndicatorParameters
```

---

### IndicatorRelease
(bool) The function removes an indicator handle and releases the calculation block of the indicator, if it's not used by anyone else.

```mql5
IndicatorRelease
```

---

### IndicatorSetDouble
(bool) The function sets the value of the corresponding indicator property. Indicator property must be of the double type. There are two variants of the function.

```mql5
IndicatorSetDouble
```

---

### IndicatorSetInteger
(bool) The function sets the value of the corresponding indicator property. Indicator property must be of the int or color type. There are two variants of the function.

```mql5
IndicatorSetInteger
```

---

### IndicatorSetString
(bool) The function sets the value of the corresponding indicator property. Indicator property must be of the string type. There are two variants of the function.

```mql5
IndicatorSetString
```

---

### IntegerToString
(string) This function converts value of integer type into a string of a specified length and returns the obtained string.

```mql5
IntegerToString
```

---

### iOBV
(int) The function returns the handle of the On Balance Volume indicator. It has only one buffer.

```mql5
iOBV
```

---

### iOsMA
(int) The function returns the handle of the Moving Average of Oscillator indicator. The OsMA oscillator shows the difference between values of MACD and its signal line. It has only one buffer.

```mql5
iOsMA
```

---

### iRSI
(int) The function returns the handle of the Relative Strength Index indicator. It has only one buffer.

```mql5
iRSI
```

---

### iRVI
(int) The function returns the handle of the Relative Vigor Index indicator.

```mql5
iRVI
```

---

### iSAR
(int) The function returns the handle of the Parabolic Stop and Reverse system indicator. It has only one buffer.

```mql5
iSAR
```

---

### IsStopped
(bool) Checks the forced shutdown of an mql5 program.

```mql5
IsStopped()
```

---

### iStdDev
(int) The function returns the handle of the Standard Deviation indicator. It has only one buffer.

```mql5
iStdDev
```

---

### iStochastic
(int) The function returns the handle of the Stochastic Oscillator indicator.

```mql5
iStochastic
```

---

### iTEMA
(int) The function returns the handle of the Triple Exponential Moving Average indicator. It has only one buffer.

```mql5
iTEMA
```

---

### iTriX
(int) The function returns the handle of the Triple Exponential Moving Averages Oscillator indicator. It has only one buffer.

```mql5
iTriX
```

---

### iVIDyA
(int) The function returns the handle of the Variable Index Dynamic Average indicator. It has only one buffer.

```mql5
iVIDyA
```

---

### iVolumes
(int) The function returns the handle of the Volumes indicator.  It has an only one buffer.

```mql5
iVolumes
```

---

### iWPR
(int) The function returns the handle of the Larry Williams' Percent Range indicator. It has only one buffer.

```mql5
iWPR
```

---

### log
(double) The function returns a natural logarithm.

```mql5
log
```

---

### log10
(double) Returns the logarithm of a number by base 10.

```mql5
log10
```

---

### MarketBookAdd
(bool) Provides opening of Depth of Market for a selected symbol, and subscribes for receiving notifications of the DOM changes.

```mql5
MarketBookAdd
```

---

### MarketBookGet
(bool) Returns a structure array MqlBookInfo containing records of the Depth of Market of a specified symbol.

```mql5
MarketBookGet
```

---

### MarketBookRelease
(bool) Provides closing of Depth of Market for a selected symbol, and cancels the subscription for receiving notifications of the DOM changes.

```mql5
MarketBookRelease
```

---

### MathAbs
(double) The function returns the absolute value (modulus) of the specified numeric value.

```mql5
MathAbs
```

---

### MathArccos
(double) The function returns the arccosine of x within the range 0 to π in radians.

```mql5
MathArccos
```

---

### MathArcsin
(double) The function returns the arc sine of x within the range of -π/2 to π/2 radians.

```mql5
MathArcsin
```

---

### MathArctan
(double) The function returns the arc tangent of x. If x is equal to 0, the function returns 0.

```mql5
MathArctan
```

---

### MathCeil
(double) The function returns integer numeric value closest from above.

```mql5
MathCeil
```

---

### MathCos
(double) The function returns the cosine of an angle.

```mql5
MathCos
```

---

### MathExp
(double) The function returns the value of e raised to the power of d.

```mql5
MathExp
```

---

### MathFloor
(double) The function returns integer numeric value closest from below.

```mql5
MathFloor
```

---

### MathIsValidNumber
(bool) It checks the correctness of a real number.

```mql5
MathIsValidNumber
```

---

### MathLog
(double) The function returns a natural logarithm.

```mql5
MathLog
```

---

### MathLog10
(double) Returns the logarithm of a number by base 10.

```mql5
MathLog10
```

---

### MathMax
(double) The function returns the maximal value of two values.

```mql5
MathMax
```

---

### MathMin
(double) The function returns the minimal value of two values.

```mql5
MathMin
```

---

### MathMod
(double) The function returns the real remainder of division of two numbers.

```mql5
MathMod
```

---

### MathPow
(double) The function raises a base to a specified power.

```mql5
MathPow
```

---

### MathRand
(int) Returns a pseudorandom integer within the range of 0 to 32767.

```mql5
MathRand()
```

---

### MathRound
(double) The function returns a value rounded off to the nearest integer of the specified numeric value.

```mql5
MathRound
```

---

### MathSin
(double) Returns the sine of a specified angle.

```mql5
MathSin
```

---

### MathSqrt
(double) Returns the square root of a number.

```mql5
MathSqrt
```

---

### MathSrand
(void) Sets the starting point for generating a series of pseudorandom integers.

```mql5
MathSrand
```

---

### MathTan
(double) The function returns a tangent of a number.

```mql5
MathTan
```

---

### MessageBox
(int) It creates and shows a message box and manages it. A message box contains a message and header, any combination of predefined signs and command buttons.

```mql5
MessageBox
```

---

### MQLInfoInteger
(int) Returns the value of a corresponding property of a running mql5 program.

```mql5
MQLInfoInteger
```

---

### MQLInfoString
(string) Returns the value of a corresponding property of a running mql5 program.

```mql5
MQLInfoString
```

---

### NormalizeDouble
(double) Rounding floating point number to a specified accuracy.

```mql5
NormalizeDouble
```

---

### ObjectCreate
(bool) The function creates an object with the specified name, type, and the initial coordinates in the specified chart subwindow. During creation up to 30 coordinates can be specified.

```mql5
ObjectCreate
```

---

### ObjectDelete
(bool) The function removes the object with the specified name from the specified chart.

```mql5
ObjectDelete
```

---

### ObjectFind
(int) The function searches for an object with the specified name in the chart with the specified ID.

```mql5
ObjectFind
```

---

### ObjectGetDouble
(bool) The function returns the value of the corresponding object property. The object property must be of the double type. There are 2 variants of the function.

```mql5
ObjectGetDouble
```

---

### ObjectGetInteger
(bool) The function returns the value of the corresponding object property. The object property must be of the datetime, int, color, bool or char type. There are 2 variants of the function.

```mql5
ObjectGetInteger
```

---

### ObjectGetString
(bool) The function returns the value of the corresponding object property. The object property must be of the string type. There are 2 variants of the function.

```mql5
ObjectGetString
```

---

### ObjectGetTimeByValue
(datetime) The function returns the time value for the specified price value of the specified object.

```mql5
ObjectGetTimeByValue
```

---

### ObjectGetValueByTime
(double) The function returns the price value for the specified time value of the specified object.

```mql5
ObjectGetValueByTime
```

---

### ObjectMove
(bool) The function changes coordinates of the specified anchor point of the object.

```mql5
ObjectMove
```

---

### ObjectName
(string) The function returns the name of the corresponding object in the specified chart, in the specified subwindow, of the specified type.

```mql5
ObjectName
```

---

### ObjectsDeleteAll
(int) Removes all objects from the specified chart, specified chart subwindow, of the specified type.

```mql5
ObjectsDeleteAll
```

---

### ObjectSetDouble
(bool) The function sets the value of the corresponding object property. The object property must be of the double type. There are 2 variants of the function.

```mql5
ObjectSetDouble
```

---

### ObjectSetInteger
(bool) The function sets the value of the corresponding object property. The object property must be of the datetime, int, color, bool or char type. There are 2 variants of the function.

```mql5
ObjectSetInteger
```

---

### ObjectSetString
(bool) The function sets the value of the corresponding object property. The object property must be of the string type. There are 2 variants of the function.

```mql5
ObjectSetString
```

---

### ObjectsTotal
(int) The function returns the number of objects in the specified chart, specified subwindow, of the specified type.

```mql5
ObjectsTotal
```

---

### OnStart
(int) The function is called in scripts and services when the Start event occurs. The function is intended for one-time execution of actions implemented in a program. There are two function types.

```mql5
OnStart
```

---

### OnInit
(int) The function is called in indicators and EAs when the Init event occurs. It is used to initialize a running MQL5 program. There are two function types.

```mql5
OnInit
```

---

### OnDeinit
(void) The function is called in indicators and EAs when the Deinit event occurs. It is used to deinitialize a running MQL5 program.

```mql5
OnDeinit
```

---

### OnTick
(void) The NewTick event is generated only for EAs upon receiving a new tick for a symbol of the chart the EA is attached to.

```mql5
OnTick
```

---

### OnCalculate
(int) The function is called in the indicators when the Calculate event occurs for processing price data changes. There are two function types. Only one of them can be used within a single indicator.

```mql5
OnCalculate
```

---

### OnTimer
(void) The Timer event is periodically generated by the client terminal for an EA, which activated the timer using the EventSetTimer() function.

```mql5
OnTimer
```

---

### OnTrade
(void) OnTrade() is called only for Expert Advisors. It is not used in indicators and scripts even if you add there a function with the same name and type.

```mql5
OnTrade
```

---

### OnTradeTransaction
(void) The function is called in EAs when the TradeTransaction event occurs. The function is meant for handling trade request execution results.

```mql5
OnTradeTransaction
```

---

### OnBookEvent
(void) The function is called in indicators and EAs when the BookEvent event occurs. It is meant for handling Depth of Market changes.

```mql5
OnBookEvent
```

---

### OnChartEvent
(void) The function is called in indicators and EAs when the ChartEvent event occurs. The function is meant for handling chart changes made by a user or an MQL5 program.

```mql5
OnChartEvent
```

---

### OnTester
(double) The function is called in Expert Advisors when the Tester event occurs to perform necessary actions after testing.

```mql5
OnTester
```

---

### OnTesterInit
(int) The function is called in EAs when the TesterInit event occurs to perform necessary actions before optimization in the strategy tester. There are two function types.

```mql5
OnTesterInit
```

---

### OnTesterDeinit
(void) The function is called in EAs when the TesterDeinit event occurs after EA optimization.

```mql5
OnTesterDeinit
```

---

### OnTesterPass
(void) The function is called in EAs when the TesterPass event occurs for handling a new data frame during EA optimization.

```mql5
OnTesterPass
```

---

### OrderCalcMargin
(bool) The function calculates the margin required for the specified order type, on the current account, in the current market environment not taking into account current pending orders and open positions. It allows the evaluation of margin for the trade operation planned. The value is returned in the account currency.

```mql5
OrderCalcMargin
```

---

### OrderCalcProfit
(bool) The function calculates the profit for the current account, in the current market conditions, based on the parameters passed. The function is used for pre-evaluation of the result of a trade operation. The value is returned in the account currency.

```mql5
OrderCalcProfit
```

---

### OrderCheck
(bool) The OrderCheck() function checks if there are enough money to execute a required trade operation. The check results are placed to the fields of the MqlTradeCheckResult structure.

```mql5
OrderCheck
```

---

### OrderGetDouble
(bool) Returns the requested property of an order, pre-selected using OrderGetTicket or OrderSelect. The order property must be of the double type. There are 2 variants of the function.

```mql5
OrderGetDouble
```

---

### OrderGetInteger
(bool) Returns the requested order property, pre-selected using OrderGetTicket or OrderSelect. Order property must be of the datetime, int type. There are 2 variants of the function.

```mql5
OrderGetInteger
```

---

### OrderGetString
(bool) Returns the requested order property, pre-selected using OrderGetTicket or OrderSelect. The order property must be of the string type. There are 2 variants of the function.

```mql5
OrderGetString
```

---

### OrderGetTicket
(ulong) Returns ticket of a corresponding order and automatically selects the order for further working with it using functions.

```mql5
OrderGetTicket
```

---

### OrderSelect
(bool) Selects an order to work with. Returns true if the function has been successfully completed. Returns false if the function completion has failed. For more information about an error call GetLastError().

```mql5
OrderSelect
```

---

### OrderSend
(bool) The OrderSend() function is used for executing trade operations by sending requests to a trade server.

```mql5
OrderSend
```

---

### OrderSendAsync
(bool) The OrderSendAsync() function is used for conducting asynchronous trade operations without waiting for the trade server's response to a sent request. The function is designed for high-frequency trading, when under the terms of the trading algorithm it is unacceptable to waste time waiting for a response from the server.

```mql5
OrderSendAsync
```

---

### OrdersTotal
(int) Returns the number of current orders.

```mql5
OrdersTotal()
```

---

### ParameterGetRange
(bool) Receives data on the values range and the change step for an input variable when optimizing an Expert Advisor in the Strategy Tester. There are 2 variants of the function.

```mql5
ParameterGetRange
```

---

### ParameterSetRange
(bool) Specifies the use of input variable when optimizing an Expert Advisor in the Strategy Tester: value, change step, initial and final values. There are 2 variants of the function.

```mql5
ParameterSetRange
```

---

### Period
(ENUM_TIMEFRAMES) Returns the current chart timeframe.

```mql5
Period()
```

---

### PeriodSeconds
(int) This function returns number of seconds in a period.

```mql5
PeriodSeconds
```

---

### PlaySound
(bool) It plays a sound file.

```mql5
PlaySound
```

---

### PlotIndexGetInteger
(int) The function sets the value of the corresponding property of the corresponding indicator line. The indicator property must be of the int, color, bool or char type. There are 2 variants of the function.

```mql5
PlotIndexGetInteger
```

---

### PlotIndexSetDouble
(bool) The function sets the value of the corresponding property of the corresponding indicator line. The indicator property must be of the double type.

```mql5
PlotIndexSetDouble
```

---

### PlotIndexSetInteger
(bool) The function sets the value of the corresponding property of the corresponding indicator line. The indicator property must be of the int, char, bool or color type. There are 2 variants of the function.

```mql5
PlotIndexSetInteger
```

---

### PlotIndexSetString
(bool) The function sets the value of the corresponding property of the corresponding indicator line. The indicator property must be of the string type.

```mql5
PlotIndexSetString
```

---

### Point
(double) Returns the point size of the current symbol in the quote currency.

```mql5
Point()
```

---

### PositionGetDouble
(bool) The function returns the requested property of an open position, pre-selected using PositionGetSymbol or PositionSelect. The position property must be of the double type. There are 2 variants of the function.

```mql5
PositionGetDouble
```

---

### PositionGetInteger
(bool) The function returns the requested property of an open position, pre-selected using PositionGetSymbol or PositionSelect. The position property should be of datetime, int type. There are 2 variants of the function.

```mql5
PositionGetInteger
```

---

### PositionGetString
(bool) The function returns the requested property of an open position, pre-selected using PositionGetSymbol or PositionSelect. The position property should be of the string type. There are 2 variants of the function.

```mql5
PositionGetString
```

---

### PositionGetSymbol
(string) Returns the symbol corresponding to the open position and automatically selects the position for further working with it using functions PositionGetDouble, PositionGetInteger, PositionGetString.

```mql5
PositionGetSymbol
```

---

### PositionGetTicket
(ulong) The function returns the ticket of a position with the specified index in the list of open positions and automatically selects the position to work with using functions PositionGetDouble, PositionGetInteger, PositionGetString.

```mql5
PositionGetTicket
```

---

### PositionSelect
(bool) Chooses an open position for further working with it. Returns true if the function is successfully completed. Returns false in case of failure. To obtain information about the error, call GetLastError().

```mql5
PositionSelect
```

---

### PositionSelectByTicket
(bool) Selects an open position to work with based on the ticket number specified in the position. If successful, returns true. Returns false if the function failed. Call GetLastError() for error details.

```mql5
PositionSelectByTicket
```

---

### PositionsTotal
(int) Returns the number of open positions.

```mql5
PositionsTotal()
```

---

### pow
(double) The function raises a base to a specified power.

```mql5
pow
```

---

### Print
(void) It enters a message in the Expert Advisor log. Parameters can be of any type.

```mql5
Print
```

---

### PrintFormat
(void) It formats and enters sets of symbols and values in the Expert Advisor log in accordance with a preset format.

```mql5
PrintFormat
```

---

### rand
(int) Returns a pseudorandom integer within the range of 0 to 32767.

```mql5
rand()
```

---

### ResetLastError
(void) Sets the value of the predefined variable _LastError into zero.

```mql5
ResetLastError()
```

---

### ResourceCreate
(bool) Creates an image resource based on a data set. There are two variants of the function:

```mql5
ResourceCreate
```

---

### ResourceFree
(bool) The function deletes dynamically created resource (freeing the memory allocated for it).

```mql5
ResourceFree
```

---

### ResourceReadImage
(bool) The function reads data from the graphical resource created by ResourceCreate() function or saved in EX5 file during compilation.

```mql5
ResourceReadImage
```

---

### ResourceSave
(bool) Saves a resource into the specified file.

```mql5
ResourceSave
```

---

### round
(double) The function returns a value rounded off to the nearest integer of the specified numeric value.

```mql5
round
```

---

### SendFTP
(bool) Sends a file at the address, specified in the setting window of the "FTP" tab.

```mql5
SendFTP
```

---

### SendMail
(bool) Sends an email at the address specified in the settings window of the "Email" tab.

```mql5
SendMail
```

---

### SendNotification
(bool) Sends push notifications to the mobile terminals, whose MetaQuotes IDs are specified in the "Notifications" tab.

```mql5
SendNotification
```

---

### SeriesInfoInteger
(bool) Returns information about the state of historical data. There are 2 variants of function calls.

```mql5
SeriesInfoInteger
```

---

### SetIndexBuffer
(bool) The function binds a specified indicator buffer with one-dimensional dynamic array of the double type.

```mql5
SetIndexBuffer
```

---

### ShortArrayToString
(string) It copies part of array into a returned string.

```mql5
ShortArrayToString
```

---

### ShortToString
(string) It converts the symbol code (unicode) into one-symbol string and returns resulting string.

```mql5
ShortToString
```

---

### SignalBaseGetDouble
(double) Returns the value of double type property for selected signal.

```mql5
SignalBaseGetDouble
```

---

### SignalBaseGetInteger
(long) Returns the value of integer type property for selected signal.

```mql5
SignalBaseGetInteger
```

---

### SignalBaseGetString
(string) Returns the value of string type property for selected signal.

```mql5
SignalBaseGetString
```

---

### SignalBaseSelect
(bool) Selects a signal from signals, available in terminal for further working with it.

```mql5
SignalBaseSelect
```

---

### SignalBaseTotal
(int) Returns the total amount of signals, available in terminal.

```mql5
SignalBaseTotal()
```

---

### SignalInfoGetDouble
(double) Returns the value of double type property of signal copy settings.

```mql5
SignalInfoGetDouble
```

---

### SignalInfoGetInteger
(long) Returns the value of integer type property of signal copy settings.

```mql5
SignalInfoGetInteger
```

---

### SignalInfoGetString
(string) Returns the value of string type property of signal copy settings.

```mql5
SignalInfoGetString
```

---

### SignalInfoSetDouble
(bool) Sets the value of double type property of signal copy settings.

```mql5
SignalInfoSetDouble
```

---

### SignalInfoSetInteger
(bool) Sets the value of integer type property of signal copy settings.

```mql5
SignalInfoSetInteger
```

---

### SignalSubscribe
(bool) Subscribes to the trading signal.

```mql5
SignalSubscribe
```

---

### SignalUnsubscribe
(bool) Cancels subscription.

```mql5
SignalUnsubscribe()
```

---

### sin
(double) Returns the sine of a specified angle.

```mql5
sin
```

---

### Sleep
(void) The function suspends execution of the current Expert Advisor or script within a specified interval.

```mql5
Sleep
```

---

### SocketCreate
(int) Create a socket with specified flags and return its handle.

```mql5
SocketCreate
```

---

### SocketClose
(bool) Close a socket.

```mql5
SocketClose
```

---

### SocketConnect
(bool) Connect to the server with timeout control.

```mql5
SocketConnect
```

---

### SocketIsConnected
(bool) Checks if the socket is currently connected.

```mql5
SocketIsConnected
```

---

### SocketIsReadable
(uint) Get a number of bytes that can be read from a socket.

```mql5
SocketIsReadable
```

---

### SocketIsWritable
(bool) Check whether data can be written to a socket at the current time.

```mql5
SocketIsWritable
```

---

### SocketTimeouts
(bool) Set timeouts for receiving and sending data for a socket system object.

```mql5
SocketTimeouts
```

---

### SocketRead
(int) Read data from a socket.

```mql5
SocketRead
```

---

### SocketSend
(int) Write data to a socket.

```mql5
SocketSend
```

---

### SocketTlsHandshake
(bool) Initiate secure TLS (SSL) connection to a specified host via TLS Handshake protocol. During Handshake, a client and a server agree on connection parameters: applied protocol version and data encryption method.

```mql5
SocketTlsHandshake
```

---

### SocketTlsCertificate
(int) Get data on the certificate used to secure network connection.

```mql5
SocketTlsCertificate
```

---

### SocketTlsRead
(int) Read data from secure TLS connection.

```mql5
SocketTlsRead
```

---

### SocketTlsReadAvailable
(int) Read all available data from secure TLS connection.

```mql5
SocketTlsReadAvailable
```

---

### SocketTlsSend
(int) Send data via secure TLS connection.

```mql5
SocketTlsSend
```

---

### sqrt
(double) Returns the square root of a number.

```mql5
sqrt
```

---

### srand
(void) Sets the starting point for generating a series of pseudorandom integers.

```mql5
srand
```

---

### StringAdd
(bool) The function adds a substring to the end of a string.

```mql5
StringAdd
```

---

### StringBufferLen
(int) The function returns the size of buffer allocated for the string.

```mql5
StringBufferLen
```

---

### StringCompare
(int) The function compares two strings and returns the comparison result in form of an integer.

```mql5
StringCompare
```

---

### StringConcatenate
(int) The function forms a string of passed parameters and returns the size of the formed string. Parameters can be of any type. Number of parameters can't be less than 2 or more than 64.

```mql5
StringConcatenate
```

---

### StringFill
(bool) It fills out a selected string by specified symbols.

```mql5
StringFill
```

---

### StringFind
(int) Search for a substring in a string.

```mql5
StringFind
```

---

### StringFormat
(string) The function formats obtained parameters and returns a string.

```mql5
StringFormat
```

---

### StringGetCharacter
(ushort) Returns value of a symbol, located in the specified position of a string.

```mql5
StringGetCharacter
```

---

### StringInit
(bool) Initializes a string by specified symbols and provides the specified string size.

```mql5
StringInit
```

---

### StringLen
(int) Returns the number of symbols in a string.

```mql5
StringLen
```

---

### StringReplace
(int) It replaces all the found substrings of a string by a set sequence of symbols.

```mql5
StringReplace
```

---

### StringSetCharacter
(bool) Returns copy of a string with a changed character in a specified position.

```mql5
StringSetCharacter
```

---

### StringSplit
(int) Gets substrings by a specified separator from the specified string, returns the number of substrings obtained.

```mql5
StringSplit
```

---

### StringSubstr
(string) Extracts a substring from a text string starting from the specified position.

```mql5
StringSubstr
```

---

### StringToCharArray
(int) Symbol-wise copies a string converted from Unicode to ANSI, to a selected place of array of uchar type. It returns the number of copied elements.

```mql5
StringToCharArray
```

---

### StringToColor
(color) Converting "R,G,B" string or string with color name into color type value.

```mql5
StringToColor
```

---

### StringToDouble
(double) The function converts string containing a symbol representation of number into number of double type.

```mql5
StringToDouble
```

---

### StringToInteger
(long) The function converts string containing a symbol representation of number into number of long (integer) type.

```mql5
StringToInteger
```

---

### StringToLower
(bool) Transforms all symbols of a selected string into lowercase.

```mql5
StringToLower
```

---

### StringToShortArray
(int) The function symbol-wise copies a string into a specified place of an array of ushort type. It returns the number of copied elements.

```mql5
StringToShortArray
```

---

### StringToTime
(datetime) Transforms the string containing time and/or date in the "yyyy.mm.dd [hh:mi]" format into the datetime type number.

```mql5
StringToTime
```

---

### StringToUpper
(bool) Transforms all symbols of a selected string into capitals.

```mql5
StringToUpper
```

---

### StringTrimLeft
(int) The function cuts line feed characters, spaces and tabs in the left part of the string till the first meaningful symbol. The string is modified at place.

```mql5
StringTrimLeft
```

---

### StringTrimRight
(int) The function cuts line feed characters, spaces and tabs in the right part of the string after the last meaningful symbol. The string is modified at place.

```mql5
StringTrimRight
```

---

### StructToTime
(datetime) Converts a structure variable MqlDateTime into a value of datetime type and returns the resulting value.

```mql5
StructToTime
```

---

### Symbol
(string) Returns the name of a symbol of the current chart.

```mql5
Symbol()
```

---

### SymbolInfoDouble
(bool) Returns the corresponding property of a specified symbol. There are 2 variants of the function.

```mql5
SymbolInfoDouble
```

---

### SymbolInfoInteger
(bool) Returns the corresponding property of a specified symbol. There are 2 variants of the function.

```mql5
SymbolInfoInteger
```

---

### SymbolInfoMarginRate
(bool) Returns the margin rates depending on the order type and direction.

```mql5
SymbolInfoMarginRate
```

---

### SymbolInfoSessionQuote
(bool) Allows receiving time of beginning and end of the specified quoting sessions for a specified symbol and day of week.

```mql5
SymbolInfoSessionQuote
```

---

### SymbolInfoSessionTrade
(bool) Allows receiving time of beginning and end of the specified trading sessions for a specified symbol and day of week.

```mql5
SymbolInfoSessionTrade
```

---

### SymbolInfoString
(bool) Returns the corresponding property of a specified symbol. There are 2 variants of the function.

```mql5
SymbolInfoString
```

---

### SymbolInfoTick
(bool) The function returns current prices of a specified symbol in a variable of the MqlTick type.

```mql5
SymbolInfoTick
```

---

### SymbolIsSynchronized
(bool) The function checks whether data of a selected symbol in the terminal are synchronized with data on the trade server.

```mql5
SymbolIsSynchronized
```

---

### SymbolName
(string) Returns the name of a symbol.

```mql5
SymbolName
```

---

### SymbolSelect
(bool) Selects a symbol in the Market Watch window or removes a symbol from the window.

```mql5
SymbolSelect
```

---

### SymbolsTotal
(int) Returns the number of available (selected in Market Watch or all) symbols.

```mql5
SymbolsTotal
```

---

### tan
(double) The function returns a tangent of a number.

```mql5
tan
```

---

### TerminalClose
(bool) The function commands the terminal to complete operation.

```mql5
TerminalClose
```

---

### TerminalInfoDouble
(double) Returns the value of a corresponding property of the mql5 program environment.

```mql5
TerminalInfoDouble
```

---

### TerminalInfoInteger
(int) Returns the value of a corresponding property of the mql5 program environment.

```mql5
TerminalInfoInteger
```

---

### TerminalInfoString
(string) Returns the value of a corresponding property of the mql5 program environment. The property must be of string type.

```mql5
TerminalInfoString
```

---

### TesterStatistics
(double) The function returns the value of the specified statistical parameter calculated based on testing results.

```mql5
TesterStatistics
```

---

### TextGetSize
(bool) The function returns the line width and height at the current font settings.

```mql5
TextGetSize
```

---

### TextOut
(bool) The function displays a text in a custom array (buffer) and returns the result of that operation. The array is designed to create the graphical resource.

```mql5
TextOut
```

---

### TextSetFont
(bool) The function sets the font for displaying the text using drawing methods and returns the result of that operation. Arial font with the size -120 (12 pt) is used by default.

```mql5
TextSetFont
```

---

### TimeCurrent
(datetime) Returns the last known server time, time of the last quote receipt for one of the symbols selected in the "Market Watch" window. In the OnTick() handler, this function returns the time of the received handled tick. In other cases (for example, call in handlers OnInit(), OnDeinit(), OnTimer() and so on) this is the time of the last quote receipt for any symbol available in the "Market Watch" window, the time shown in the title of this window. The time value is formed on a trade server and does not depend on the time settings on your computer. There are 2 variants of the function.

```mql5
TimeCurrent
```

---

### TimeDaylightSavings
(int) Returns correction for daylight saving time in seconds, if the switch to summer time has been made. It depends on the time settings of your computer.

```mql5
TimeDaylightSavings()
```

---

### TimeGMT
(datetime) Returns the GMT, which is calculated taking into account the DST switch by the local time on the computer where the client terminal is running. There are 2 variants of the function.

```mql5
TimeGMT
```

---

### TimeGMTOffset
(int) Returns the current difference between GMT time and the local computer time in seconds, taking into account switch to winter or summer time. Depends on the time settings of your computer.

```mql5
TimeGMTOffset()
```

---

### TimeLocal
(datetime) Returns the local time of a computer, where the client terminal is running. There are 2 variants of the function.

```mql5
TimeLocal
```

---

### TimeToString
(string) Converting a value containing time in seconds elapsed since 01.01.1970 into a string of "yyyy.mm.dd hh:mi" format.

```mql5
TimeToString
```

---

### TimeToStruct
(bool) Converts a value of datetime type (number of seconds since 01.01.1970) into a structure variable MqlDateTime.

```mql5
TimeToStruct
```

---

### TimeTradeServer
(datetime) Returns the calculated current time of the trade server. Unlike TimeCurrent(), the calculation of the time value is performed in the client terminal and depends on the time settings on your computer. There are 2 variants of the function.

```mql5
TimeTradeServer
```

---

### UninitializeReason
(int) Returns the code of a reason for deinitialization.

```mql5
UninitializeReason()
```

---

### WebRequest
(int) The function sends an HTTP request to a specified server. The function has two versions:

```mql5
WebRequest
```

---

### ZeroMemory
(void) The function resets a variable passed to it by reference.

```mql5
ZeroMemory
```

---

### clrAliceBlue
(color) Web color AliceBlue

```mql5
clrAliceBlue
```

---

### clrAntiqueWhite
(color) Web color AntiqueWhite

```mql5
clrAntiqueWhite
```

---

### clrAqua
(color) Web color Aqua

```mql5
clrAqua
```

---

### clrAquamarine
(color) Web color Aquamarine

```mql5
clrAquamarine
```

---

### clrAzure
(color) Web color Azure

```mql5
clrAzure
```

---

### clrBeige
(color) Web color Beige

```mql5
clrBeige
```

---

### clrBisque
(color) Web color Bisque

```mql5
clrBisque
```

---

### clrBlack
(color) Web color Black

```mql5
clrBlack
```

---

### clrBlanchedAlmond
(color) Web color BlanchedAlmond

```mql5
clrBlanchedAlmond
```

---

### clrBlue
(color) Web color Blue

```mql5
clrBlue
```

---

### clrBlueViolet
(color) Web color BlueViolet

```mql5
clrBlueViolet
```

---

### clrBrown
(color) Web color Brown

```mql5
clrBrown
```

---

### clrBurlyWood
(color) Web color BurlyWood

```mql5
clrBurlyWood
```

---

### clrCadetBlue
(color) Web color CadetBlue

```mql5
clrCadetBlue
```

---

### clrChartreuse
(color) Web color Chartreuse

```mql5
clrChartreuse
```

---

### clrChocolate
(color) Web color Chocolate

```mql5
clrChocolate
```

---

### clrCoral
(color) Web color Coral

```mql5
clrCoral
```

---

### clrCornflowerBlue
(color) Web color CornflowerBlue

```mql5
clrCornflowerBlue
```

---

### clrCornsilk
(color) Web color Cornsilk

```mql5
clrCornsilk
```

---

### clrCrimson
(color) Web color Crimson

```mql5
clrCrimson
```

---

### clrCyan
(color) Web color Cyan

```mql5
clrCyan
```

---

### clrDarkBlue
(color) Web color DarkBlue

```mql5
clrDarkBlue
```

---

### clrDarkCyan
(color) Web color DarkCyan

```mql5
clrDarkCyan
```

---

### clrDarkGoldenrod
(color) Web color DarkGoldenrod

```mql5
clrDarkGoldenrod
```

---

### clrDarkGray
(color) Web color DarkGray

```mql5
clrDarkGray
```

---

### clrDarkGreen
(color) Web color DarkGreen

```mql5
clrDarkGreen
```

---

### clrDarkKhaki
(color) Web color DarkKhaki

```mql5
clrDarkKhaki
```

---

### clrDarkMagenta
(color) Web color DarkMagenta

```mql5
clrDarkMagenta
```

---

### clrDarkOliveGreen
(color) Web color DarkOliveGreen

```mql5
clrDarkOliveGreen
```

---

### clrDarkOrange
(color) Web color DarkOrange

```mql5
clrDarkOrange
```

---

### clrDarkOrchid
(color) Web color DarkOrchid

```mql5
clrDarkOrchid
```

---

### clrDarkRed
(color) Web color DarkRed

```mql5
clrDarkRed
```

---

### clrDarkSalmon
(color) Web color DarkSalmon

```mql5
clrDarkSalmon
```

---

### clrDarkSeaGreen
(color) Web color DarkSeaGreen

```mql5
clrDarkSeaGreen
```

---

### clrDarkSlateBlue
(color) Web color DarkSlateBlue

```mql5
clrDarkSlateBlue
```

---

### clrDarkSlateGray
(color) Web color DarkSlateGray

```mql5
clrDarkSlateGray
```

---

### clrDarkTurquoise
(color) Web color DarkTurquoise

```mql5
clrDarkTurquoise
```

---

### clrDarkViolet
(color) Web color DarkViolet

```mql5
clrDarkViolet
```

---

### clrDeepPink
(color) Web color DeepPink

```mql5
clrDeepPink
```

---

### clrDeepSkyBlue
(color) Web color DeepSkyBlue

```mql5
clrDeepSkyBlue
```

---

### clrDimGray
(color) Web color DimGray

```mql5
clrDimGray
```

---

### clrDodgerBlue
(color) Web color DodgerBlue

```mql5
clrDodgerBlue
```

---

### clrFireBrick
(color) Web color FireBrick

```mql5
clrFireBrick
```

---

### clrFloralWhite
(color) Web color FloralWhite

```mql5
clrFloralWhite
```

---

### clrForestGreen
(color) Web color ForestGreen

```mql5
clrForestGreen
```

---

### clrFuchsia
(color) Web color Fuchsia

```mql5
clrFuchsia
```

---

### clrGainsboro
(color) Web color Gainsboro

```mql5
clrGainsboro
```

---

### clrGhostWhite
(color) Web color GhostWhite

```mql5
clrGhostWhite
```

---

### clrGold
(color) Web color Gold

```mql5
clrGold
```

---

### clrGoldenrod
(color) Web color Goldenrod

```mql5
clrGoldenrod
```

---

### clrGray
(color) Web color Gray

```mql5
clrGray
```

---

### clrGreen
(color) Web color Green

```mql5
clrGreen
```

---

### clrGreenYellow
(color) Web color GreenYellow

```mql5
clrGreenYellow
```

---

### clrHoneydew
(color) Web color Honeydew

```mql5
clrHoneydew
```

---

### clrHotPink
(color) Web color HotPink

```mql5
clrHotPink
```

---

### clrIndianRed
(color) Web color IndianRed

```mql5
clrIndianRed
```

---

### clrIndigo
(color) Web color Indigo

```mql5
clrIndigo
```

---

### clrIvory
(color) Web color Ivory

```mql5
clrIvory
```

---

### clrKhaki
(color) Web color Khaki

```mql5
clrKhaki
```

---

### clrLavender
(color) Web color Lavender

```mql5
clrLavender
```

---

### clrLavenderBlush
(color) Web color LavenderBlush

```mql5
clrLavenderBlush
```

---

### clrLawnGreen
(color) Web color LawnGreen

```mql5
clrLawnGreen
```

---

### clrLemonChiffon
(color) Web color LemonChiffon

```mql5
clrLemonChiffon
```

---

### clrLightBlue
(color) Web color LightBlue

```mql5
clrLightBlue
```

---

### clrLightCoral
(color) Web color LightCoral

```mql5
clrLightCoral
```

---

### clrLightCyan
(color) Web color LightCyan

```mql5
clrLightCyan
```

---

### clrLightGoldenrod
(color) Web color LightGoldenrod

```mql5
clrLightGoldenrod
```

---

### clrLightGray
(color) Web color LightGray

```mql5
clrLightGray
```

---

### clrLightGreen
(color) Web color LightGreen

```mql5
clrLightGreen
```

---

### clrLightPink
(color) Web color LightPink

```mql5
clrLightPink
```

---

### clrLightSalmon
(color) Web color LightSalmon

```mql5
clrLightSalmon
```

---

### clrLightSeaGreen
(color) Web color LightSeaGreen

```mql5
clrLightSeaGreen
```

---

### clrLightSkyBlue
(color) Web color LightSkyBlue

```mql5
clrLightSkyBlue
```

---

### clrLightSlateGray
(color) Web color LightSlateGray

```mql5
clrLightSlateGray
```

---

### clrLightSteelBlue
(color) Web color LightSteelBlue

```mql5
clrLightSteelBlue
```

---

### clrLightYellow
(color) Web color LightYellow

```mql5
clrLightYellow
```

---

### clrLime
(color) Web color Lime

```mql5
clrLime
```

---

### clrLimeGreen
(color) Web color LimeGreen

```mql5
clrLimeGreen
```

---

### clrLinen
(color) Web color Linen

```mql5
clrLinen
```

---

### clrMagenta
(color) Web color Magenta

```mql5
clrMagenta
```

---

### clrMaroon
(color) Web color Maroon

```mql5
clrMaroon
```

---

### clrMediumAquamarine
(color) Web color MediumAquamarine

```mql5
clrMediumAquamarine
```

---

### clrMediumBlue
(color) Web color MediumBlue

```mql5
clrMediumBlue
```

---

### clrMediumOrchid
(color) Web color MediumOrchid

```mql5
clrMediumOrchid
```

---

### clrMediumPurple
(color) Web color MediumPurple

```mql5
clrMediumPurple
```

---

### clrMediumSeaGreen
(color) Web color MediumSeaGreen

```mql5
clrMediumSeaGreen
```

---

### clrMediumSlateBlue
(color) Web color MediumSlateBlue

```mql5
clrMediumSlateBlue
```

---

### clrMediumSpringGreen
(color) Web color MediumSpringGreen

```mql5
clrMediumSpringGreen
```

---

### clrMediumTurquoise
(color) Web color MediumTurquoise

```mql5
clrMediumTurquoise
```

---

### clrMediumVioletRed
(color) Web color MediumVioletRed

```mql5
clrMediumVioletRed
```

---

### clrMidnightBlue
(color) Web color MidnightBlue

```mql5
clrMidnightBlue
```

---

### clrMintCream
(color) Web color MintCream

```mql5
clrMintCream
```

---

### clrMistyRose
(color) Web color MistyRose

```mql5
clrMistyRose
```

---

### clrMoccasin
(color) Web color Moccasin

```mql5
clrMoccasin
```

---

### clrNavajoWhite
(color) Web color NavajoWhite

```mql5
clrNavajoWhite
```

---

### clrNavy
(color) Web color Navy

```mql5
clrNavy
```

---

### clrOldLace
(color) Web color OldLace

```mql5
clrOldLace
```

---

### clrOlive
(color) Web color Olive

```mql5
clrOlive
```

---

### clrOliveDrab
(color) Web color OliveDrab

```mql5
clrOliveDrab
```

---

### clrOrange
(color) Web color Orange

```mql5
clrOrange
```

---

### clrOrangeRed
(color) Web color OrangeRed

```mql5
clrOrangeRed
```

---

### clrOrchid
(color) Web color Orchid

```mql5
clrOrchid
```

---

### clrPaleGoldenrod
(color) Web color PaleGoldenrod

```mql5
clrPaleGoldenrod
```

---

### clrPaleGreen
(color) Web color PaleGreen

```mql5
clrPaleGreen
```

---

### clrPaleTurquoise
(color) Web color PaleTurquoise

```mql5
clrPaleTurquoise
```

---

### clrPaleVioletRed
(color) Web color PaleVioletRed

```mql5
clrPaleVioletRed
```

---

### clrPapayaWhip
(color) Web color PapayaWhip

```mql5
clrPapayaWhip
```

---

### clrPeachPuff
(color) Web color PeachPuff

```mql5
clrPeachPuff
```

---

### clrPeru
(color) Web color Peru

```mql5
clrPeru
```

---

### clrPink
(color) Web color Pink

```mql5
clrPink
```

---

### clrPlum
(color) Web color Plum

```mql5
clrPlum
```

---

### clrPowderBlue
(color) Web color PowderBlue

```mql5
clrPowderBlue
```

---

### clrPurple
(color) Web color Purple

```mql5
clrPurple
```

---

### clrRed
(color) Web color Red

```mql5
clrRed
```

---

### clrRosyBrown
(color) Web color RosyBrown

```mql5
clrRosyBrown
```

---

### clrRoyalBlue
(color) Web color RoyalBlue

```mql5
clrRoyalBlue
```

---

### clrSaddleBrown
(color) Web color SaddleBrown

```mql5
clrSaddleBrown
```

---

### clrSalmon
(color) Web color Salmon

```mql5
clrSalmon
```

---

### clrSandyBrown
(color) Web color SandyBrown

```mql5
clrSandyBrown
```

---

### clrSeaGreen
(color) Web color SeaGreen

```mql5
clrSeaGreen
```

---

### clrSeashell
(color) Web color Seashell

```mql5
clrSeashell
```

---

### clrSienna
(color) Web color Sienna

```mql5
clrSienna
```

---

### clrSilver
(color) Web color Silver

```mql5
clrSilver
```

---

### clrSkyBlue
(color) Web color SkyBlue

```mql5
clrSkyBlue
```

---

### clrSlateBlue
(color) Web color SlateBlue

```mql5
clrSlateBlue
```

---

### clrSlateGray
(color) Web color SlateGray

```mql5
clrSlateGray
```

---

### clrSnow
(color) Web color Snow

```mql5
clrSnow
```

---

### clrSpringGreen
(color) Web color SpringGreen

```mql5
clrSpringGreen
```

---

### clrSteelBlue
(color) Web color SteelBlue

```mql5
clrSteelBlue
```

---

### clrTan
(color) Web color Tan

```mql5
clrTan
```

---

### clrTeal
(color) Web color Teal

```mql5
clrTeal
```

---

### clrThistle
(color) Web color Thistle

```mql5
clrThistle
```

---

### clrTomato
(color) Web color Tomato

```mql5
clrTomato
```

---

### clrTurquoise
(color) Web color Turquoise

```mql5
clrTurquoise
```

---

### clrViolet
(color) Web color Violet

```mql5
clrViolet
```

---

### clrWheat
(color) Web color Wheat

```mql5
clrWheat
```

---

### clrWhite
(color) Web color White

```mql5
clrWhite
```

---

### clrWhiteSmoke
(color) Web color WhiteSmoke

```mql5
clrWhiteSmoke
```

---

### clrYellow
(color) Web color Yellow

```mql5
clrYellow
```

---

### clrYellowGreen
(color) Web color YellowGreen

```mql5
clrYellowGreen
```

---

### clrNONE
Absence of color

```mql5
clrNONE
```

---

### __DATE__
File compilation date without time (hours, minutes and seconds are equal to 0)

```mql5
__DATE__
```

---

### __DATETIME__
File compilation date and time

```mql5
__DATETIME__
```

---

### __FILE__
Name of the currently compiled file

```mql5
__FILE__
```

---

### __FUNCSIG__
Signature of the function in whose body the macro is located. Logging of the full description of functions can be useful in the identification of overloaded functions

```mql5
__FUNCSIG__
```

---

### __FUNCTION__
Name of the function, in whose body the macro is located

```mql5
__FUNCTION__
```

---

### __LINE__
Line number in the source code, in which the macro is located

```mql5
__LINE__
```

---

### __MQLBUILD__, __MQL5BUILD__
Compiler build number

```mql5
__MQLBUILD__, __MQL5BUILD__
```

---

### __PATH__
An absolute path to the file that is currently being compiled

```mql5
__PATH__
```

---

### ACCOUNT_ASSETS
The current assets of an account

```mql5
ACCOUNT_ASSETS
```

---

### ACCOUNT_BALANCE
Account balance in the deposit currency

```mql5
ACCOUNT_BALANCE
```

---

### ACCOUNT_COMMISSION_BLOCKED
The current blocked commission amount on an account

```mql5
ACCOUNT_COMMISSION_BLOCKED
```

---

### ACCOUNT_COMPANY
Name of a company that serves the account

```mql5
ACCOUNT_COMPANY
```

---

### ACCOUNT_CREDIT
Account credit in the deposit currency

```mql5
ACCOUNT_CREDIT
```

---

### ACCOUNT_CURRENCY
Account currency

```mql5
ACCOUNT_CURRENCY
```

---

### ACCOUNT_EQUITY
Account equity in the deposit currency

```mql5
ACCOUNT_EQUITY
```

---

### ACCOUNT_LEVERAGE
Account leverage

```mql5
ACCOUNT_LEVERAGE
```

---

### ACCOUNT_LIABILITIES
The current liabilities on an account

```mql5
ACCOUNT_LIABILITIES
```

---

### ACCOUNT_LIMIT_ORDERS
Maximum allowed number of active pending orders

```mql5
ACCOUNT_LIMIT_ORDERS
```

---

### ACCOUNT_LOGIN
Account number

```mql5
ACCOUNT_LOGIN
```

---

### ACCOUNT_MARGIN
Account margin used in the deposit currency

```mql5
ACCOUNT_MARGIN
```

---

### ACCOUNT_MARGIN_FREE
Free margin of an account in the deposit currency

```mql5
ACCOUNT_MARGIN_FREE
```

---

### ACCOUNT_MARGIN_INITIAL
Initial margin. The amount reserved on an account to cover the margin of all pending orders

```mql5
ACCOUNT_MARGIN_INITIAL
```

---

### ACCOUNT_MARGIN_LEVEL
Account margin level in percents

```mql5
ACCOUNT_MARGIN_LEVEL
```

---

### ACCOUNT_MARGIN_MAINTENANCE
Maintenance margin. The minimum equity reserved on an account to cover the minimum amount of all open positions

```mql5
ACCOUNT_MARGIN_MAINTENANCE
```

---

### ACCOUNT_MARGIN_SO_CALL
Margin call level. Depending on the set ACCOUNT_MARGIN_SO_MODE is expressed in percents or in the deposit currency

```mql5
ACCOUNT_MARGIN_SO_CALL
```

---

### ACCOUNT_MARGIN_SO_MODE
Mode for setting the minimal allowed margin

```mql5
ACCOUNT_MARGIN_SO_MODE
```

---

### ACCOUNT_MARGIN_SO_SO
Margin stop out level. Depending on the set ACCOUNT_MARGIN_SO_MODE is expressed in percents or in the deposit currency

```mql5
ACCOUNT_MARGIN_SO_SO
```

---

### ACCOUNT_NAME
Client name

```mql5
ACCOUNT_NAME
```

---

### ACCOUNT_PROFIT
Current profit of an account in the deposit currency

```mql5
ACCOUNT_PROFIT
```

---

### ACCOUNT_SERVER
Trade server name

```mql5
ACCOUNT_SERVER
```

---

### ACCOUNT_STOPOUT_MODE_MONEY
Account stop out mode in money

```mql5
ACCOUNT_STOPOUT_MODE_MONEY
```

---

### ACCOUNT_STOPOUT_MODE_PERCENT
Account stop out mode in percents

```mql5
ACCOUNT_STOPOUT_MODE_PERCENT
```

---

### ACCOUNT_TRADE_ALLOWED
Allowed trade for the current account

```mql5
ACCOUNT_TRADE_ALLOWED
```

---

### ACCOUNT_TRADE_EXPERT
Allowed trade for an Expert Advisor

```mql5
ACCOUNT_TRADE_EXPERT
```

---

### ACCOUNT_TRADE_MODE
Account trade mode

```mql5
ACCOUNT_TRADE_MODE
```

---

### ACCOUNT_TRADE_MODE_CONTEST
Contest account

```mql5
ACCOUNT_TRADE_MODE_CONTEST
```

---

### ACCOUNT_TRADE_MODE_DEMO
Demo account

```mql5
ACCOUNT_TRADE_MODE_DEMO
```

---

### ACCOUNT_TRADE_MODE_REAL
Real account

```mql5
ACCOUNT_TRADE_MODE_REAL
```

---

### ALIGN_CENTER
Centered (only for the Edit object)

```mql5
ALIGN_CENTER
```

---

### ALIGN_LEFT
Left alignment

```mql5
ALIGN_LEFT
```

---

### ALIGN_RIGHT
Right alignment

```mql5
ALIGN_RIGHT
```

---

### ANCHOR_CENTER
Anchor point strictly in the center of the object

```mql5
ANCHOR_CENTER
```

---

### ANCHOR_LEFT
Anchor point to the left in the center

```mql5
ANCHOR_LEFT
```

---

### ANCHOR_LEFT_LOWER
Anchor point at the lower left corner

```mql5
ANCHOR_LEFT_LOWER
```

---

### ANCHOR_LEFT_UPPER
Anchor point at the upper left corner

```mql5
ANCHOR_LEFT_UPPER
```

---

### ANCHOR_LOWER
Anchor point below in the center

```mql5
ANCHOR_LOWER
```

---

### ANCHOR_RIGHT
Anchor point to the right in the center

```mql5
ANCHOR_RIGHT
```

---

### ANCHOR_RIGHT_LOWER
Anchor point at the lower right corner

```mql5
ANCHOR_RIGHT_LOWER
```

---

### ANCHOR_RIGHT_UPPER
Anchor point at the upper right corner

```mql5
ANCHOR_RIGHT_UPPER
```

---

### ANCHOR_UPPER
Anchor point above in the center

```mql5
ANCHOR_UPPER
```

---

### BASE_LINE
Main line

```mql5
BASE_LINE
```

---

### BOOK_TYPE_BUY
Buy order (Bid)

```mql5
BOOK_TYPE_BUY
```

---

### BOOK_TYPE_BUY_MARKET
Buy order by Market

```mql5
BOOK_TYPE_BUY_MARKET
```

---

### BOOK_TYPE_SELL
Sell order (Offer)

```mql5
BOOK_TYPE_SELL
```

---

### BOOK_TYPE_SELL_MARKET
Sell order by Market

```mql5
BOOK_TYPE_SELL_MARKET
```

---

### BORDER_FLAT
Flat form

```mql5
BORDER_FLAT
```

---

### BORDER_RAISED
Prominent form

```mql5
BORDER_RAISED
```

---

### BORDER_SUNKEN
Concave form

```mql5
BORDER_SUNKEN
```

---

### CHAR_MAX
Maximal value, which can be represented by char type

```mql5
CHAR_MAX
```

---

### CHAR_MIN
Minimal value, which can be represented by char type

```mql5
CHAR_MIN
```

---

### CHART_AUTOSCROLL
Mode of automatic moving to the right border of the chart

```mql5
CHART_AUTOSCROLL
```

---

### CHART_BARS
Display as a sequence of bars

```mql5
CHART_BARS
```

---

### CHART_BEGIN
Chart beginning (the oldest prices)

```mql5
CHART_BEGIN
```

---

### CHART_BRING_TO_TOP
Show chart on top of other charts

```mql5
CHART_BRING_TO_TOP
```

---

### CHART_CANDLES
Display as Japanese candlesticks

```mql5
CHART_CANDLES
```

---

### CHART_COLOR_ASK
Ask price level color

```mql5
CHART_COLOR_ASK
```

---

### CHART_COLOR_BACKGROUND
Chart background color

```mql5
CHART_COLOR_BACKGROUND
```

---

### CHART_COLOR_BID
Bid price level color

```mql5
CHART_COLOR_BID
```

---

### CHART_COLOR_CANDLE_BEAR
Body color of a bear candlestick

```mql5
CHART_COLOR_CANDLE_BEAR
```

---

### CHART_COLOR_CANDLE_BULL
Body color of a bull candlestick

```mql5
CHART_COLOR_CANDLE_BULL
```

---

### CHART_COLOR_CHART_DOWN
Color for the down bar, shadows and body borders of bear candlesticks

```mql5
CHART_COLOR_CHART_DOWN
```

---

### CHART_COLOR_CHART_LINE
Line chart color and color of "Doji" Japanese candlesticks

```mql5
CHART_COLOR_CHART_LINE
```

---

### CHART_COLOR_CHART_UP
Color for the up bar, shadows and body borders of bull candlesticks

```mql5
CHART_COLOR_CHART_UP
```

---

### CHART_COLOR_FOREGROUND
Color of axes, scales and OHLC line

```mql5
CHART_COLOR_FOREGROUND
```

---

### CHART_COLOR_GRID
Grid color

```mql5
CHART_COLOR_GRID
```

---

### CHART_COLOR_LAST
Line color of the last executed deal price (Last)

```mql5
CHART_COLOR_LAST
```

---

### CHART_COLOR_STOP_LEVEL
Color of stop order levels (Stop Loss and Take Profit)

```mql5
CHART_COLOR_STOP_LEVEL
```

---

### CHART_COLOR_VOLUME
Color of volumes and position opening levels

```mql5
CHART_COLOR_VOLUME
```

---

### CHART_COMMENT
Text of a comment in a chart

```mql5
CHART_COMMENT
```

---

### CHART_CURRENT_POS
Current position

```mql5
CHART_CURRENT_POS
```

---

### CHART_DRAG_TRADE_LEVELS
Permission to drag trading levels on a chart with a mouse. The drag mode is enabled by default (true value)

```mql5
CHART_DRAG_TRADE_LEVELS
```

---

### CHART_EVENT_MOUSE_MOVE
Send notifications of mouse move and mouse click events (CHARTEVENT_MOUSE_MOVE) to all mql5 programs on a chart

```mql5
CHART_EVENT_MOUSE_MOVE
```

---

### CHART_EVENT_OBJECT_CREATE
Send a notification of an event of new object creation (CHARTEVENT_OBJECT_CREATE) to all mql5-programs on a chart

```mql5
CHART_EVENT_OBJECT_CREATE
```

---

### CHART_EVENT_OBJECT_DELETE
Send a notification of an event of object deletion (CHARTEVENT_OBJECT_DELETE) to all mql5-programs on a chart

```mql5
CHART_EVENT_OBJECT_DELETE
```

---

### CHART_FIRST_VISIBLE_BAR
Number of the first visible bar in the chart. Indexing of bars is the same as for timeseries.

```mql5
CHART_FIRST_VISIBLE_BAR
```

---

### CHART_FIXED_MAX
Fixed  chart maximum

```mql5
CHART_FIXED_MAX
```

---

### CHART_FIXED_MIN
Fixed  chart minimum

```mql5
CHART_FIXED_MIN
```

---

### CHART_FIXED_POSITION
Chart fixed position from the left border in percent value. Chart fixed position is marked by a small gray triangle on the horizontal time axis. It is displayed only if the automatic chart scrolling to the right on tick incoming is disabled (see CHART_AUTOSCROLL property). The bar on a fixed position remains in the same place when zooming in and out.

```mql5
CHART_FIXED_POSITION
```

---

### CHART_FOREGROUND
Price chart in the foreground

```mql5
CHART_FOREGROUND
```

---

### CHART_HEIGHT_IN_PIXELS
Chart height in pixels

```mql5
CHART_HEIGHT_IN_PIXELS
```

---

### CHART_IS_OBJECT
Identifying "Chart" (OBJ_CHART) object – returns true for a graphical object. Returns false for a real chart

```mql5
CHART_IS_OBJECT
```

---

### CHART_LINE
Display as a line drawn by Close prices

```mql5
CHART_LINE
```

---

### CHART_MODE
Chart type (candlesticks, bars or line)

```mql5
CHART_MODE
```

---

### CHART_MOUSE_SCROLL
Scrolling the chart horizontally using the left mouse button. Vertical scrolling is also available if the value of any following properties is set to true: CHART_SCALEFIX, CHART_SCALEFIX_11 or CHART_SCALE_PT_PER_BAR

```mql5
CHART_MOUSE_SCROLL
```

---

### CHART_POINTS_PER_BAR
Scale in points per bar

```mql5
CHART_POINTS_PER_BAR
```

---

### CHART_PRICE_MAX
Chart maximum

```mql5
CHART_PRICE_MAX
```

---

### CHART_PRICE_MIN
Chart minimum

```mql5
CHART_PRICE_MIN
```

---

### CHART_SCALE
Scale

```mql5
CHART_SCALE
```

---

### CHART_SCALE_PT_PER_BAR
Scale to be specified in points per bar

```mql5
CHART_SCALE_PT_PER_BAR
```

---

### CHART_SCALEFIX
Fixed scale mode

```mql5
CHART_SCALEFIX
```

---

### CHART_SCALEFIX_11
Scale 1:1 mode

```mql5
CHART_SCALEFIX_11
```

---

### CHART_SHIFT
Mode of price chart indent from the right border

```mql5
CHART_SHIFT
```

---

### CHART_SHIFT_SIZE
The size of the zero bar indent from the right border in percents

```mql5
CHART_SHIFT_SIZE
```

---

### CHART_SHOW_ASK_LINE
Display Ask values as a horizontal line in a chart

```mql5
CHART_SHOW_ASK_LINE
```

---

### CHART_SHOW_BID_LINE
Display Bid values as a horizontal line in a chart

```mql5
CHART_SHOW_BID_LINE
```

---

### CHART_SHOW_DATE_SCALE
Showing the time scale on a chart

```mql5
CHART_SHOW_DATE_SCALE
```

---

### CHART_SHOW_GRID
Display grid in the chart

```mql5
CHART_SHOW_GRID
```

---

### CHART_SHOW_LAST_LINE
Display Last values as a horizontal line in a chart

```mql5
CHART_SHOW_LAST_LINE
```

---

### CHART_SHOW_OBJECT_DESCR
Pop-up descriptions of graphical objects

```mql5
CHART_SHOW_OBJECT_DESCR
```

---

### CHART_SHOW_OHLC
Show OHLC values in the upper left corner

```mql5
CHART_SHOW_OHLC
```

---

### CHART_SHOW_ONE_CLICK
Showing the "One click trading" panel on a chart

```mql5
CHART_SHOW_ONE_CLICK
```

---

### CHART_SHOW_PERIOD_SEP
Display vertical separators between adjacent periods

```mql5
CHART_SHOW_PERIOD_SEP
```

---

### CHART_SHOW_PRICE_SCALE
Showing the price scale on a chart

```mql5
CHART_SHOW_PRICE_SCALE
```

---

### CHART_SHOW_TRADE_LEVELS
Displaying trade levels in the chart (levels of open positions, Stop Loss, Take Profit and pending orders)

```mql5
CHART_SHOW_TRADE_LEVELS
```

---

### CHART_SHOW_VOLUMES
Display volume in the chart

```mql5
CHART_SHOW_VOLUMES
```

---

### CHART_VISIBLE_BARS
The number of bars on the chart that can be displayed

```mql5
CHART_VISIBLE_BARS
```

---

### CHART_VOLUME_HIDE
Volumes are not shown

```mql5
CHART_VOLUME_HIDE
```

---

### CHART_VOLUME_REAL
Trade volumes

```mql5
CHART_VOLUME_REAL
```

---

### CHART_VOLUME_TICK
Tick volumes

```mql5
CHART_VOLUME_TICK
```

---

### CHART_WIDTH_IN_BARS
Chart width in bars

```mql5
CHART_WIDTH_IN_BARS
```

---

### CHART_WIDTH_IN_PIXELS
Chart width in pixels

```mql5
CHART_WIDTH_IN_PIXELS
```

---

### CHART_WINDOW_HANDLE
Chart window handle (HWND)

```mql5
CHART_WINDOW_HANDLE
```

---

### CHART_WINDOW_IS_VISIBLE
Visibility of subwindows

```mql5
CHART_WINDOW_IS_VISIBLE
```

---

### CHART_WINDOW_YDISTANCE
The distance between the upper frame of the indicator subwindow and the upper frame of the main chart window, along the vertical Y axis, in pixels. In case of a mouse event, the cursor coordinates are passed in terms of the coordinates of the main chart window, while the coordinates of graphical objects in an indicator subwindow are set relative to the upper left corner of the subwindow. 
The value is required for converting the absolute coordinates of the main chart to the local coordinates of a subwindow for correct work with the graphical objects, whose coordinates are set relative to  the upper left corner of the subwindow frame.

```mql5
CHART_WINDOW_YDISTANCE
```

---

### CHART_WINDOWS_TOTAL
The total number of chart windows, including indicator subwindows

```mql5
CHART_WINDOWS_TOTAL
```

---

### CHARTEVENT_CHART_CHANGE
Change of the chart size or modification of chart properties through the Properties dialog

```mql5
CHARTEVENT_CHART_CHANGE
```

---

### CHARTEVENT_CLICK
Clicking on a chart

```mql5
CHARTEVENT_CLICK
```

---

### CHARTEVENT_CUSTOM
Initial number of an event from a range of custom events

```mql5
CHARTEVENT_CUSTOM
```

---

### CHARTEVENT_CUSTOM_LAST
The final number of an event from a range of custom events

```mql5
CHARTEVENT_CUSTOM_LAST
```

---

### CHARTEVENT_KEYDOWN
Keystrokes

```mql5
CHARTEVENT_KEYDOWN
```

---

### CHARTEVENT_MOUSE_MOVE
Mouse move, mouse clicks (if CHART_EVENT_MOUSE_MOVE=true is set for the chart)

```mql5
CHARTEVENT_MOUSE_MOVE
```

---

### CHARTEVENT_OBJECT_CHANGE
Graphical object property changed via the properties dialog

```mql5
CHARTEVENT_OBJECT_CHANGE
```

---

### CHARTEVENT_OBJECT_CLICK
Clicking on a graphical object

```mql5
CHARTEVENT_OBJECT_CLICK
```

---

### CHARTEVENT_OBJECT_CREATE
Graphical object created (if CHART_EVENT_OBJECT_CREATE=true is set for the chart)

```mql5
CHARTEVENT_OBJECT_CREATE
```

---

### CHARTEVENT_OBJECT_DELETE
Graphical object deleted (if CHART_EVENT_OBJECT_DELETE=true is set for the chart)

```mql5
CHARTEVENT_OBJECT_DELETE
```

---

### CHARTEVENT_OBJECT_DRAG
Drag and drop of a graphical object

```mql5
CHARTEVENT_OBJECT_DRAG
```

---

### CHARTEVENT_OBJECT_ENDEDIT
End of text editing in the graphical object Edit

```mql5
CHARTEVENT_OBJECT_ENDEDIT
```

---

### CHARTS_MAX
The maximum possible number of simultaneously open charts in the terminal

```mql5
CHARTS_MAX
```

---

### CHIKOUSPAN_LINE
Chikou Span line

```mql5
CHIKOUSPAN_LINE
```

---

### CORNER_LEFT_LOWER
Center of coordinates is in the lower left corner of the chart

```mql5
CORNER_LEFT_LOWER
```

---

### CORNER_LEFT_UPPER
Center of coordinates is in the upper left corner of the chart

```mql5
CORNER_LEFT_UPPER
```

---

### CORNER_RIGHT_LOWER
Center of coordinates is in the lower right corner of the chart

```mql5
CORNER_RIGHT_LOWER
```

---

### CORNER_RIGHT_UPPER
Center of coordinates is in the upper right corner of the chart

```mql5
CORNER_RIGHT_UPPER
```

---

### CP_ACP
The current Windows ANSI code page.

```mql5
CP_ACP
```

---

### CP_MACCP
The current system Macintosh code page.
Note: This value is mostly used in earlier created program codes and is of no use now, since modern Macintosh computers use Unicode for encoding.

```mql5
CP_MACCP
```

---

### CP_OEMCP
The current system OEM code page.

```mql5
CP_OEMCP
```

---

### CP_SYMBOL
Symbol code page

```mql5
CP_SYMBOL
```

---

### CP_THREAD_ACP
The Windows ANSI code page for the current thread.

```mql5
CP_THREAD_ACP
```

---

### CP_UTF7
UTF-7 code page.

```mql5
CP_UTF7
```

---

### CP_UTF8
UTF-8 code page.

```mql5
CP_UTF8
```

---

### CRYPT_AES128
AES encryption with 128 bit key (16 bytes)

```mql5
CRYPT_AES128
```

---

### CRYPT_AES256
AES encryption with 256 bit key (32 bytes)

```mql5
CRYPT_AES256
```

---

### CRYPT_ARCH_ZIP
ZIP archives

```mql5
CRYPT_ARCH_ZIP
```

---

### CRYPT_BASE64
BASE64

```mql5
CRYPT_BASE64
```

---

### CRYPT_DES
DES encryption with 56 bit key (7 bytes)

```mql5
CRYPT_DES
```

---

### CRYPT_HASH_MD5
MD5 HASH calculation

```mql5
CRYPT_HASH_MD5
```

---

### CRYPT_HASH_SHA1
SHA1 HASH calculation

```mql5
CRYPT_HASH_SHA1
```

---

### CRYPT_HASH_SHA256
SHA256 HASH calculation

```mql5
CRYPT_HASH_SHA256
```

---

### DBL_DIG
Number of significant decimal digits for double type

```mql5
DBL_DIG
```

---

### DBL_EPSILON
Minimal value, which satisfies the condition:
1.0+DBL_EPSILON != 1.0 (for double type)

```mql5
DBL_EPSILON
```

---

### DBL_MANT_DIG
Bits count in a mantissa for double type

```mql5
DBL_MANT_DIG
```

---

### DBL_MAX
Maximal value, which can be represented by double type

```mql5
DBL_MAX
```

---

### DBL_MAX_10_EXP
Maximal decimal value of exponent degree for double type

```mql5
DBL_MAX_10_EXP
```

---

### DBL_MAX_EXP
Maximal binary value of exponent degree for double type

```mql5
DBL_MAX_EXP
```

---

### DBL_MIN
Minimal positive value, which can be represented by double type

```mql5
DBL_MIN
```

---

### DBL_MIN_10_EXP
Minimal decimal value of exponent degree for double type

```mql5
DBL_MIN_10_EXP
```

---

### DBL_MIN_EXP
Minimal binary value of exponent degree for double type

```mql5
DBL_MIN_EXP
```

---

### DEAL_COMMENT
Deal comment

```mql5
DEAL_COMMENT
```

---

### DEAL_COMMISSION
Deal commission

```mql5
DEAL_COMMISSION
```

---

### DEAL_ENTRY
Deal entry - entry in, entry out, reverse

```mql5
DEAL_ENTRY
```

---

### DEAL_ENTRY_IN
Entry in

```mql5
DEAL_ENTRY_IN
```

---

### DEAL_ENTRY_INOUT
Reverse

```mql5
DEAL_ENTRY_INOUT
```

---

### DEAL_ENTRY_OUT
Entry out

```mql5
DEAL_ENTRY_OUT
```

---

### DEAL_MAGIC
Deal magic number (see ORDER_MAGIC)

```mql5
DEAL_MAGIC
```

---

### DEAL_ORDER
Deal order number

```mql5
DEAL_ORDER
```

---

### DEAL_POSITION_ID
Identifier of a position, in the opening, modification or change of which this deal took part. Each position has a unique identifier that is assigned to all deals executed for the symbol during the entire lifetime of the position.

```mql5
DEAL_POSITION_ID
```

---

### DEAL_PRICE
Deal price

```mql5
DEAL_PRICE
```

---

### DEAL_PROFIT
Deal profit

```mql5
DEAL_PROFIT
```

---

### DEAL_SWAP
Cumulative swap on close

```mql5
DEAL_SWAP
```

---

### DEAL_SYMBOL
Deal symbol

```mql5
DEAL_SYMBOL
```

---

### DEAL_TIME
Deal time

```mql5
DEAL_TIME
```

---

### DEAL_TIME_MSC
The time of a deal execution in milliseconds since 01.01.1970

```mql5
DEAL_TIME_MSC
```

---

### DEAL_TYPE
Deal type

```mql5
DEAL_TYPE
```

---

### DEAL_TYPE_BALANCE
Balance

```mql5
DEAL_TYPE_BALANCE
```

---

### DEAL_TYPE_BONUS
Bonus

```mql5
DEAL_TYPE_BONUS
```

---

### DEAL_TYPE_BUY
Buy

```mql5
DEAL_TYPE_BUY
```

---

### DEAL_TYPE_BUY_CANCELED
Canceled buy deal. There can be a situation when a previously executed buy deal is canceled. In this case, the type of the previously executed deal (DEAL_TYPE_BUY) is changed to DEAL_TYPE_BUY_CANCELED, and its profit/loss is zeroized. Previously obtained profit/loss is charged/withdrawn using a separated balance operation

```mql5
DEAL_TYPE_BUY_CANCELED
```

---

### DEAL_TYPE_CHARGE
Additional charge

```mql5
DEAL_TYPE_CHARGE
```

---

### DEAL_TYPE_COMMISSION
Additional commission

```mql5
DEAL_TYPE_COMMISSION
```

---

### DEAL_TYPE_COMMISSION_AGENT_DAILY
Daily agent commission

```mql5
DEAL_TYPE_COMMISSION_AGENT_DAILY
```

---

### DEAL_TYPE_COMMISSION_AGENT_MONTHLY
Monthly agent commission

```mql5
DEAL_TYPE_COMMISSION_AGENT_MONTHLY
```

---

### DEAL_TYPE_COMMISSION_DAILY
Daily commission

```mql5
DEAL_TYPE_COMMISSION_DAILY
```

---

### DEAL_TYPE_COMMISSION_MONTHLY
Monthly commission

```mql5
DEAL_TYPE_COMMISSION_MONTHLY
```

---

### DEAL_TYPE_CORRECTION
Correction

```mql5
DEAL_TYPE_CORRECTION
```

---

### DEAL_TYPE_CREDIT
Credit

```mql5
DEAL_TYPE_CREDIT
```

---

### DEAL_TYPE_INTEREST
Interest rate

```mql5
DEAL_TYPE_INTEREST
```

---

### DEAL_TYPE_SELL
Sell

```mql5
DEAL_TYPE_SELL
```

---

### DEAL_TYPE_SELL_CANCELED
Canceled sell deal. There can be a situation when a previously executed sell deal is canceled. In this case, the type of the previously executed deal (DEAL_TYPE_SELL) is changed to DEAL_TYPE_SELL_CANCELED, and its profit/loss is zeroized. Previously obtained profit/loss is charged/withdrawn using a separated balance operation

```mql5
DEAL_TYPE_SELL_CANCELED
```

---

### DEAL_VOLUME
Deal volume

```mql5
DEAL_VOLUME
```

---

### DRAW_ARROW
Drawing arrows

```mql5
DRAW_ARROW
```

---

### DRAW_BARS
Display as a sequence of bars

```mql5
DRAW_BARS
```

---

### DRAW_CANDLES
Display as a sequence of candlesticks

```mql5
DRAW_CANDLES
```

---

### DRAW_COLOR_ARROW
Drawing multicolored arrows

```mql5
DRAW_COLOR_ARROW
```

---

### DRAW_COLOR_BARS
Multicolored bars

```mql5
DRAW_COLOR_BARS
```

---

### DRAW_COLOR_CANDLES
Multicolored candlesticks

```mql5
DRAW_COLOR_CANDLES
```

---

### DRAW_COLOR_HISTOGRAM
Multicolored histogram from the zero line

```mql5
DRAW_COLOR_HISTOGRAM
```

---

### DRAW_COLOR_HISTOGRAM2
Multicolored histogram of the two indicator buffers

```mql5
DRAW_COLOR_HISTOGRAM2
```

---

### DRAW_COLOR_LINE
Multicolored line

```mql5
DRAW_COLOR_LINE
```

---

### DRAW_COLOR_SECTION
Multicolored section

```mql5
DRAW_COLOR_SECTION
```

---

### DRAW_COLOR_ZIGZAG
Multicolored ZigZag

```mql5
DRAW_COLOR_ZIGZAG
```

---

### DRAW_FILLING
Color fill between the two levels

```mql5
DRAW_FILLING
```

---

### DRAW_HISTOGRAM
Histogram from the zero line

```mql5
DRAW_HISTOGRAM
```

---

### DRAW_HISTOGRAM2
Histogram of the two indicator buffers

```mql5
DRAW_HISTOGRAM2
```

---

### DRAW_LINE
Line

```mql5
DRAW_LINE
```

---

### DRAW_NONE
Not drawn

```mql5
DRAW_NONE
```

---

### DRAW_SECTION
Section

```mql5
DRAW_SECTION
```

---

### DRAW_ZIGZAG
Style Zigzag allows vertical section on the bar

```mql5
DRAW_ZIGZAG
```

---

### ELLIOTT_CYCLE
Cycle

```mql5
ELLIOTT_CYCLE
```

---

### ELLIOTT_GRAND_SUPERCYCLE
Grand Supercycle

```mql5
ELLIOTT_GRAND_SUPERCYCLE
```

---

### ELLIOTT_INTERMEDIATE
Intermediate

```mql5
ELLIOTT_INTERMEDIATE
```

---

### ELLIOTT_MINOR
Minor

```mql5
ELLIOTT_MINOR
```

---

### ELLIOTT_MINUETTE
Minuette

```mql5
ELLIOTT_MINUETTE
```

---

### ELLIOTT_MINUTE
Minute

```mql5
ELLIOTT_MINUTE
```

---

### ELLIOTT_PRIMARY
Primary

```mql5
ELLIOTT_PRIMARY
```

---

### ELLIOTT_SUBMINUETTE
Subminuette

```mql5
ELLIOTT_SUBMINUETTE
```

---

### ELLIOTT_SUPERCYCLE
Supercycle

```mql5
ELLIOTT_SUPERCYCLE
```

---

### EMPTY_VALUE
Empty value in an indicator buffer

```mql5
EMPTY_VALUE
```

---

### ERR_ACCOUNT_WRONG_PROPERTY
Wrong account property ID

```mql5
ERR_ACCOUNT_WRONG_PROPERTY
```

---

### ERR_ARRAY_BAD_SIZE
Requested array size exceeds 2 GB

```mql5
ERR_ARRAY_BAD_SIZE
```

---

### ERR_ARRAY_RESIZE_ERROR
Not enough memory for the relocation of an array, or an attempt to change the size of a static array

```mql5
ERR_ARRAY_RESIZE_ERROR
```

---

### ERR_BOOKS_CANNOT_ADD
Depth Of Market can not be added

```mql5
ERR_BOOKS_CANNOT_ADD
```

---

### ERR_BOOKS_CANNOT_DELETE
Depth Of Market can not be removed

```mql5
ERR_BOOKS_CANNOT_DELETE
```

---

### ERR_BOOKS_CANNOT_GET
The data from Depth Of Market can not be obtained

```mql5
ERR_BOOKS_CANNOT_GET
```

---

### ERR_BOOKS_CANNOT_SUBSCRIBE
Error in subscribing to receive new data from Depth Of Market

```mql5
ERR_BOOKS_CANNOT_SUBSCRIBE
```

---

### ERR_BUFFERS_NO_MEMORY
Not enough memory for the distribution of indicator buffers

```mql5
ERR_BUFFERS_NO_MEMORY
```

---

### ERR_BUFFERS_WRONG_INDEX
Wrong indicator buffer index

```mql5
ERR_BUFFERS_WRONG_INDEX
```

---

### ERR_CANNOT_CLEAN_DIRECTORY
Failed to clear the directory (probably one or more files are blocked and removal operation failed)

```mql5
ERR_CANNOT_CLEAN_DIRECTORY
```

---

### ERR_CANNOT_DELETE_DIRECTORY
The directory cannot be removed

```mql5
ERR_CANNOT_DELETE_DIRECTORY
```

---

### ERR_CANNOT_DELETE_FILE
File deleting error

```mql5
ERR_CANNOT_DELETE_FILE
```

---

### ERR_CANNOT_OPEN_FILE
File opening error

```mql5
ERR_CANNOT_OPEN_FILE
```

---

### ERR_CHAR_ARRAY_ONLY
Must be an array of type char

```mql5
ERR_CHAR_ARRAY_ONLY
```

---

### ERR_CHART_CANNOT_CHANGE
Failed to change chart symbol and period

```mql5
ERR_CHART_CANNOT_CHANGE
```

---

### ERR_CHART_CANNOT_CREATE_TIMER
Failed to create timer

```mql5
ERR_CHART_CANNOT_CREATE_TIMER
```

---

### ERR_CHART_CANNOT_OPEN
Chart opening error

```mql5
ERR_CHART_CANNOT_OPEN
```

---

### ERR_CHART_INDICATOR_CANNOT_ADD
Error adding an indicator to chart

```mql5
ERR_CHART_INDICATOR_CANNOT_ADD
```

---

### ERR_CHART_INDICATOR_CANNOT_DEL
Error deleting an indicator from the chart

```mql5
ERR_CHART_INDICATOR_CANNOT_DEL
```

---

### ERR_CHART_INDICATOR_NOT_FOUND
Indicator not found on the specified chart

```mql5
ERR_CHART_INDICATOR_NOT_FOUND
```

---

### ERR_CHART_NAVIGATE_FAILED
Error navigating through chart

```mql5
ERR_CHART_NAVIGATE_FAILED
```

---

### ERR_CHART_NO_EXPERT
No Expert Advisor in the chart that could handle the event

```mql5
ERR_CHART_NO_EXPERT
```

---

### ERR_CHART_NO_REPLY
Chart does not respond

```mql5
ERR_CHART_NO_REPLY
```

---

### ERR_CHART_NOT_FOUND
Chart not found

```mql5
ERR_CHART_NOT_FOUND
```

---

### ERR_CHART_SCREENSHOT_FAILED
Error creating screenshots

```mql5
ERR_CHART_SCREENSHOT_FAILED
```

---

### ERR_CHART_TEMPLATE_FAILED
Error applying template

```mql5
ERR_CHART_TEMPLATE_FAILED
```

---

### ERR_CHART_WINDOW_NOT_FOUND
Subwindow containing the indicator was not found

```mql5
ERR_CHART_WINDOW_NOT_FOUND
```

---

### ERR_CHART_WRONG_ID
Wrong chart ID

```mql5
ERR_CHART_WRONG_ID
```

---

### ERR_CHART_WRONG_PARAMETER
Error value of the parameter for the function of working with charts

```mql5
ERR_CHART_WRONG_PARAMETER
```

---

### ERR_CHART_WRONG_PROPERTY
Wrong chart property ID

```mql5
ERR_CHART_WRONG_PROPERTY
```

---

### ERR_CUSTOM_WRONG_PROPERTY
Wrong ID of the custom indicator property

```mql5
ERR_CUSTOM_WRONG_PROPERTY
```

---

### ERR_DIRECTORY_NOT_EXIST
Directory does not exist

```mql5
ERR_DIRECTORY_NOT_EXIST
```

---

### ERR_DOUBLE_ARRAY_ONLY
Must be an array of type double

```mql5
ERR_DOUBLE_ARRAY_ONLY
```

---

### ERR_FILE_BINSTRINGSIZE
String size must be specified, because the file is opened as binary

```mql5
ERR_FILE_BINSTRINGSIZE
```

---

### ERR_FILE_CACHEBUFFER_ERROR
Not enough memory for cache to read

```mql5
ERR_FILE_CACHEBUFFER_ERROR
```

---

### ERR_FILE_CANNOT_REWRITE
File can not be rewritten

```mql5
ERR_FILE_CANNOT_REWRITE
```

---

### ERR_FILE_IS_DIRECTORY
This is not a file, this is a directory

```mql5
ERR_FILE_IS_DIRECTORY
```

---

### ERR_FILE_ISNOT_DIRECTORY
This is a file, not a directory

```mql5
ERR_FILE_ISNOT_DIRECTORY
```

---

### ERR_FILE_NOT_EXIST
File does not exist

```mql5
ERR_FILE_NOT_EXIST
```

---

### ERR_FILE_NOTBIN
The file must be opened as a binary one

```mql5
ERR_FILE_NOTBIN
```

---

### ERR_FILE_NOTCSV
The file must be opened as CSV

```mql5
ERR_FILE_NOTCSV
```

---

### ERR_FILE_NOTTOREAD
The file must be opened for reading

```mql5
ERR_FILE_NOTTOREAD
```

---

### ERR_FILE_NOTTOWRITE
The file must be opened for writing

```mql5
ERR_FILE_NOTTOWRITE
```

---

### ERR_FILE_NOTTXT
The file must be opened as a text

```mql5
ERR_FILE_NOTTXT
```

---

### ERR_FILE_NOTTXTORCSV
The file must be opened as a text or CSV

```mql5
ERR_FILE_NOTTXTORCSV
```

---

### ERR_FILE_READERROR
File reading error

```mql5
ERR_FILE_READERROR
```

---

### ERR_FILE_WRITEERROR
Failed to write a resource to a file

```mql5
ERR_FILE_WRITEERROR
```

---

### ERR_FLOAT_ARRAY_ONLY
Must be an array of type float

```mql5
ERR_FLOAT_ARRAY_ONLY
```

---

### ERR_FTP_SEND_FAILED
File sending via ftp failed

```mql5
ERR_FTP_SEND_FAILED
```

---

### ERR_FUNCTION_NOT_ALLOWED
Function is not allowed for call

```mql5
ERR_FUNCTION_NOT_ALLOWED
```

---

### ERR_GLOBALVARIABLE_EXISTS
Global variable of the client terminal with the same name already exists

```mql5
ERR_GLOBALVARIABLE_EXISTS
```

---

### ERR_GLOBALVARIABLE_NOT_FOUND
Global variable of the client terminal is not found

```mql5
ERR_GLOBALVARIABLE_NOT_FOUND
```

---

### ERR_HISTORY_NOT_FOUND
Requested history not found

```mql5
ERR_HISTORY_NOT_FOUND
```

---

### ERR_HISTORY_WRONG_PROPERTY
Wrong ID of the history property

```mql5
ERR_HISTORY_WRONG_PROPERTY
```

---

### ERR_INCOMPATIBLE_ARRAYS
Copying incompatible arrays. String array can be copied only to a string array, and a numeric array - in numeric array only

```mql5
ERR_INCOMPATIBLE_ARRAYS
```

---

### ERR_INCOMPATIBLE_FILE
A text file must be for string arrays, for other arrays - binary

```mql5
ERR_INCOMPATIBLE_FILE
```

---

### ERR_INDICATOR_CANNOT_ADD
Error applying an indicator to chart

```mql5
ERR_INDICATOR_CANNOT_ADD
```

---

### ERR_INDICATOR_CANNOT_APPLY
The indicator cannot be applied to another indicator

```mql5
ERR_INDICATOR_CANNOT_APPLY
```

---

### ERR_INDICATOR_CANNOT_CREATE
Indicator cannot be created

```mql5
ERR_INDICATOR_CANNOT_CREATE
```

---

### ERR_INDICATOR_CUSTOM_NAME
The first parameter in the array must be the name of the custom indicator

```mql5
ERR_INDICATOR_CUSTOM_NAME
```

---

### ERR_INDICATOR_DATA_NOT_FOUND
Requested data not found

```mql5
ERR_INDICATOR_DATA_NOT_FOUND
```

---

### ERR_INDICATOR_NO_MEMORY
Not enough memory to add the indicator

```mql5
ERR_INDICATOR_NO_MEMORY
```

---

### ERR_INDICATOR_PARAMETER_TYPE
Invalid parameter type in the array when creating an indicator

```mql5
ERR_INDICATOR_PARAMETER_TYPE
```

---

### ERR_INDICATOR_PARAMETERS_MISSING
No parameters when creating an indicator

```mql5
ERR_INDICATOR_PARAMETERS_MISSING
```

---

### ERR_INDICATOR_UNKNOWN_SYMBOL
Unknown symbol

```mql5
ERR_INDICATOR_UNKNOWN_SYMBOL
```

---

### ERR_INDICATOR_WRONG_HANDLE
Wrong indicator handle

```mql5
ERR_INDICATOR_WRONG_HANDLE
```

---

### ERR_INDICATOR_WRONG_INDEX
Wrong index of the requested indicator buffer

```mql5
ERR_INDICATOR_WRONG_INDEX
```

---

### ERR_INDICATOR_WRONG_PARAMETERS
Wrong number of parameters when creating an indicator

```mql5
ERR_INDICATOR_WRONG_PARAMETERS
```

---

### ERR_INT_ARRAY_ONLY
Must be an array of type int

```mql5
ERR_INT_ARRAY_ONLY
```

---

### ERR_INTERNAL_ERROR
Unexpected internal error

```mql5
ERR_INTERNAL_ERROR
```

---

### ERR_INVALID_ARRAY
Array of a wrong type, wrong size, or a damaged object of a dynamic array

```mql5
ERR_INVALID_ARRAY
```

---

### ERR_INVALID_DATETIME
Invalid date and/or time

```mql5
ERR_INVALID_DATETIME
```

---

### ERR_INVALID_FILEHANDLE
A file with this handle was closed, or was not opening at all

```mql5
ERR_INVALID_FILEHANDLE
```

---

### ERR_INVALID_PARAMETER
Wrong parameter when calling the system function

```mql5
ERR_INVALID_PARAMETER
```

---

### ERR_INVALID_POINTER
Wrong pointer

```mql5
ERR_INVALID_POINTER
```

---

### ERR_INVALID_POINTER_TYPE
Wrong type of pointer

```mql5
ERR_INVALID_POINTER_TYPE
```

---

### ERR_LONG_ARRAY_ONLY
Must be an array of type long

```mql5
ERR_LONG_ARRAY_ONLY
```

---

### ERR_MAIL_SEND_FAILED
Email sending failed

```mql5
ERR_MAIL_SEND_FAILED
```

---

### ERR_MARKET_LASTTIME_UNKNOWN
Time of the last tick is not known (no ticks)

```mql5
ERR_MARKET_LASTTIME_UNKNOWN
```

---

### ERR_MARKET_NOT_SELECTED
Symbol is not selected in MarketWatch

```mql5
ERR_MARKET_NOT_SELECTED
```

---

### ERR_MARKET_SELECT_ERROR
Error adding or deleting a symbol in MarketWatch

```mql5
ERR_MARKET_SELECT_ERROR
```

---

### ERR_MARKET_UNKNOWN_SYMBOL
Unknown symbol

```mql5
ERR_MARKET_UNKNOWN_SYMBOL
```

---

### ERR_MARKET_WRONG_PROPERTY
Wrong identifier of a symbol property

```mql5
ERR_MARKET_WRONG_PROPERTY
```

---

### ERR_MQL5_WRONG_PROPERTY
Wrong identifier of the program property

```mql5
ERR_MQL5_WRONG_PROPERTY
```

---

### ERR_NO_STRING_DATE
No date in the string

```mql5
ERR_NO_STRING_DATE
```

---

### ERR_NOT_ENOUGH_MEMORY
Not enough memory to perform the system function

```mql5
ERR_NOT_ENOUGH_MEMORY
```

---

### ERR_NOTIFICATION_SEND_FAILED
Failed to send a notification

```mql5
ERR_NOTIFICATION_SEND_FAILED
```

---

### ERR_NOTIFICATION_TOO_FREQUENT
Too frequent sending of notifications

```mql5
ERR_NOTIFICATION_TOO_FREQUENT
```

---

### ERR_NOTIFICATION_WRONG_PARAMETER
Invalid parameter for sending a notification – an empty string or NULL has been passed to the SendNotification() function

```mql5
ERR_NOTIFICATION_WRONG_PARAMETER
```

---

### ERR_NOTIFICATION_WRONG_SETTINGS
Wrong settings of notifications in the terminal (ID is not specified or permission is not set)

```mql5
ERR_NOTIFICATION_WRONG_SETTINGS
```

---

### ERR_NOTINITIALIZED_STRING
Not initialized string

```mql5
ERR_NOTINITIALIZED_STRING
```

---

### ERR_NUMBER_ARRAYS_ONLY
Must be a numeric array

```mql5
ERR_NUMBER_ARRAYS_ONLY
```

---

### ERR_OBJECT_ERROR
Error working with a graphical object

```mql5
ERR_OBJECT_ERROR
```

---

### ERR_OBJECT_GETDATE_FAILED
Unable to get date corresponding to the value

```mql5
ERR_OBJECT_GETDATE_FAILED
```

---

### ERR_OBJECT_GETVALUE_FAILED
Unable to get value corresponding to the date

```mql5
ERR_OBJECT_GETVALUE_FAILED
```

---

### ERR_OBJECT_NOT_FOUND
Graphical object was not found

```mql5
ERR_OBJECT_NOT_FOUND
```

---

### ERR_OBJECT_WRONG_PROPERTY
Wrong ID of a graphical object property

```mql5
ERR_OBJECT_WRONG_PROPERTY
```

---

### ERR_ONEDIM_ARRAYS_ONLY
Must be a one-dimensional array

```mql5
ERR_ONEDIM_ARRAYS_ONLY
```

---

### ERR_OPENCL_BUFFER_CREATE
Failed to create an OpenCL buffer

```mql5
ERR_OPENCL_BUFFER_CREATE
```

---

### ERR_OPENCL_CONTEXT_CREATE
Error creating the OpenCL context

```mql5
ERR_OPENCL_CONTEXT_CREATE
```

---

### ERR_OPENCL_EXECUTE
OpenCL program runtime error

```mql5
ERR_OPENCL_EXECUTE
```

---

### ERR_OPENCL_INTERNAL
Internal error occurred when running OpenCL

```mql5
ERR_OPENCL_INTERNAL
```

---

### ERR_OPENCL_INVALID_HANDLE
Invalid OpenCL handle

```mql5
ERR_OPENCL_INVALID_HANDLE
```

---

### ERR_OPENCL_KERNEL_CREATE
Error creating an OpenCL kernel

```mql5
ERR_OPENCL_KERNEL_CREATE
```

---

### ERR_OPENCL_NOT_SUPPORTED
OpenCL functions are not supported on this computer

```mql5
ERR_OPENCL_NOT_SUPPORTED
```

---

### ERR_OPENCL_PROGRAM_CREATE
Error occurred when compiling an OpenCL program

```mql5
ERR_OPENCL_PROGRAM_CREATE
```

---

### ERR_OPENCL_QUEUE_CREATE
Failed to create a run queue in OpenCL

```mql5
ERR_OPENCL_QUEUE_CREATE
```

---

### ERR_OPENCL_SET_KERNEL_PARAMETER
Error occurred when setting parameters for the OpenCL kernel

```mql5
ERR_OPENCL_SET_KERNEL_PARAMETER
```

---

### ERR_OPENCL_TOO_LONG_KERNEL_NAME
Too long kernel name (OpenCL kernel)

```mql5
ERR_OPENCL_TOO_LONG_KERNEL_NAME
```

---

### ERR_OPENCL_WRONG_BUFFER_OFFSET
Invalid offset in the OpenCL buffer

```mql5
ERR_OPENCL_WRONG_BUFFER_OFFSET
```

---

### ERR_OPENCL_WRONG_BUFFER_SIZE
Invalid size of the OpenCL buffer

```mql5
ERR_OPENCL_WRONG_BUFFER_SIZE
```

---

### ERR_PLAY_SOUND_FAILED
Sound playing failed

```mql5
ERR_PLAY_SOUND_FAILED
```

---

### ERR_RESOURCE_NAME_DUPLICATED
The names of the dynamic and the static resource match

```mql5
ERR_RESOURCE_NAME_DUPLICATED
```

---

### ERR_RESOURCE_NAME_IS_TOO_LONG
The resource name exceeds 63 characters

```mql5
ERR_RESOURCE_NAME_IS_TOO_LONG
```

---

### ERR_RESOURCE_NOT_FOUND
Resource with this name has not been found in EX5

```mql5
ERR_RESOURCE_NOT_FOUND
```

---

### ERR_RESOURCE_UNSUPPOTED_TYPE
Unsupported resource type or its size exceeds 16 Mb

```mql5
ERR_RESOURCE_UNSUPPOTED_TYPE
```

---

### ERR_SERIES_ARRAY
Timeseries cannot be used

```mql5
ERR_SERIES_ARRAY
```

---

### ERR_SHORT_ARRAY_ONLY
Must be an array of type short

```mql5
ERR_SHORT_ARRAY_ONLY
```

---

### ERR_SMALL_ARRAY
Too small array, the starting position is outside the array

```mql5
ERR_SMALL_ARRAY
```

---

### ERR_SMALL_ASSERIES_ARRAY
The receiving array is declared as AS_SERIES, and it is of insufficient size

```mql5
ERR_SMALL_ASSERIES_ARRAY
```

---

### ERR_STRING_OUT_OF_MEMORY
Not enough memory for the string

```mql5
ERR_STRING_OUT_OF_MEMORY
```

---

### ERR_STRING_RESIZE_ERROR
Not enough memory for the relocation of string

```mql5
ERR_STRING_RESIZE_ERROR
```

---

### ERR_STRING_SMALL_LEN
The string length is less than expected

```mql5
ERR_STRING_SMALL_LEN
```

---

### ERR_STRING_TIME_ERROR
Error converting string to date

```mql5
ERR_STRING_TIME_ERROR
```

---

### ERR_STRING_TOO_BIGNUMBER
Too large number, more than ULONG_MAX

```mql5
ERR_STRING_TOO_BIGNUMBER
```

---

### ERR_STRING_UNKNOWNTYPE
Unknown data type when converting to a string

```mql5
ERR_STRING_UNKNOWNTYPE
```

---

### ERR_STRING_ZEROADDED
0 added to the string end, a useless operation

```mql5
ERR_STRING_ZEROADDED
```

---

### ERR_STRINGPOS_OUTOFRANGE
Position outside the string

```mql5
ERR_STRINGPOS_OUTOFRANGE
```

---

### ERR_STRUCT_WITHOBJECTS_ORCLASS
The structure contains objects of strings and/or dynamic arrays and/or structure of such objects and/or classes

```mql5
ERR_STRUCT_WITHOBJECTS_ORCLASS
```

---

### ERR_SUCCESS
The operation completed successfully

```mql5
ERR_SUCCESS
```

---

### ERR_TERMINAL_WRONG_PROPERTY
Wrong identifier of the terminal property

```mql5
ERR_TERMINAL_WRONG_PROPERTY
```

---

### ERR_TOO_LONG_FILENAME
Too long file name

```mql5
ERR_TOO_LONG_FILENAME
```

---

### ERR_TOO_MANY_FILES
More than 64 files cannot be opened at the same time

```mql5
ERR_TOO_MANY_FILES
```

---

### ERR_TOO_MANY_FORMATTERS
Amount of format specifiers more than the parameters

```mql5
ERR_TOO_MANY_FORMATTERS
```

---

### ERR_TOO_MANY_PARAMETERS
Amount of parameters more than the format specifiers

```mql5
ERR_TOO_MANY_PARAMETERS
```

---

### ERR_TRADE_DEAL_NOT_FOUND
Deal not found

```mql5
ERR_TRADE_DEAL_NOT_FOUND
```

---

### ERR_TRADE_DISABLED
Trading by Expert Advisors prohibited

```mql5
ERR_TRADE_DISABLED
```

---

### ERR_TRADE_ORDER_NOT_FOUND
Order not found

```mql5
ERR_TRADE_ORDER_NOT_FOUND
```

---

### ERR_TRADE_POSITION_NOT_FOUND
Position not found

```mql5
ERR_TRADE_POSITION_NOT_FOUND
```

---

### ERR_TRADE_SEND_FAILED
Trade request sending failed

```mql5
ERR_TRADE_SEND_FAILED
```

---

### ERR_TRADE_WRONG_PROPERTY
Wrong trade property ID

```mql5
ERR_TRADE_WRONG_PROPERTY
```

---

### ERR_USER_ERROR_FIRST
User defined errors start with this code

```mql5
ERR_USER_ERROR_FIRST
```

---

### ERR_WEBREQUEST_CONNECT_FAILED
Failed to connect to specified URL

```mql5
ERR_WEBREQUEST_CONNECT_FAILED
```

---

### ERR_WEBREQUEST_INVALID_ADDRESS
Invalid URL

```mql5
ERR_WEBREQUEST_INVALID_ADDRESS
```

---

### ERR_WEBREQUEST_REQUEST_FAILED
HTTP request failed

```mql5
ERR_WEBREQUEST_REQUEST_FAILED
```

---

### ERR_WEBREQUEST_TIMEOUT
Timeout exceeded

```mql5
ERR_WEBREQUEST_TIMEOUT
```

---

### ERR_WRONG_DIRECTORYNAME
Wrong directory name

```mql5
ERR_WRONG_DIRECTORYNAME
```

---

### ERR_WRONG_FILEHANDLE
Wrong file handle

```mql5
ERR_WRONG_FILEHANDLE
```

---

### ERR_WRONG_FILENAME
Invalid file name

```mql5
ERR_WRONG_FILENAME
```

---

### ERR_WRONG_FORMATSTRING
Invalid format string

```mql5
ERR_WRONG_FORMATSTRING
```

---

### ERR_WRONG_INTERNAL_PARAMETER
Wrong parameter in the inner call of the client terminal function

```mql5
ERR_WRONG_INTERNAL_PARAMETER
```

---

### ERR_WRONG_STRING_DATE
Wrong date in the string

```mql5
ERR_WRONG_STRING_DATE
```

---

### ERR_WRONG_STRING_OBJECT
Damaged string object

```mql5
ERR_WRONG_STRING_OBJECT
```

---

### ERR_WRONG_STRING_PARAMETER
Damaged parameter of string type

```mql5
ERR_WRONG_STRING_PARAMETER
```

---

### ERR_WRONG_STRING_TIME
Wrong time in the string

```mql5
ERR_WRONG_STRING_TIME
```

---

### ERR_ZEROSIZE_ARRAY
An array of zero length

```mql5
ERR_ZEROSIZE_ARRAY
```

---

### FILE_ACCESS_DATE
Date of the last access to the file

```mql5
FILE_ACCESS_DATE
```

---

### FILE_ANSI
Strings of ANSI type (one byte symbols). Flag is used in FileOpen().

```mql5
FILE_ANSI
```

---

### FILE_BIN
Binary read/write mode (without string to string conversion). Flag is used in FileOpen().

```mql5
FILE_BIN
```

---

### FILE_COMMON
The file path in the common folder of all client terminals \Terminal\Common\Files. Flag is used in FileOpen(), FileCopy(), FileMove() and in FileIsExist() functions.

```mql5
FILE_COMMON
```

---

### FILE_CREATE_DATE
Date of creation

```mql5
FILE_CREATE_DATE
```

---

### FILE_CSV
CSV file (all its elements are converted to strings of the appropriate type, Unicode or ANSI, and separated by separator). Flag is used in FileOpen().

```mql5
FILE_CSV
```

---

### FILE_END
Get the end of file sign

```mql5
FILE_END
```

---

### FILE_EXISTS
Check the existence

```mql5
FILE_EXISTS
```

---

### FILE_IS_ANSI
The file is opened as ANSI (see FILE_ANSI)

```mql5
FILE_IS_ANSI
```

---

### FILE_IS_BINARY
The file is opened as a binary file (see FILE_BIN)

```mql5
FILE_IS_BINARY
```

---

### FILE_IS_COMMON
The file is opened in a shared folder of all terminals (see FILE_COMMON)

```mql5
FILE_IS_COMMON
```

---

### FILE_IS_CSV
The file is opened as CSV (see FILE_CSV)

```mql5
FILE_IS_CSV
```

---

### FILE_IS_READABLE
The opened file is readable (see FILE_READ)

```mql5
FILE_IS_READABLE
```

---

### FILE_IS_TEXT
The file is opened as a text file (see FILE_TXT)

```mql5
FILE_IS_TEXT
```

---

### FILE_IS_WRITABLE
The opened file is writable (see FILE_WRITE)

```mql5
FILE_IS_WRITABLE
```

---

### FILE_LINE_END
Get the end of line sign

```mql5
FILE_LINE_END
```

---

### FILE_MODIFY_DATE
Date of the last modification

```mql5
FILE_MODIFY_DATE
```

---

### FILE_POSITION
Position of a pointer in the file

```mql5
FILE_POSITION
```

---

### FILE_READ
File is opened for reading. Flag is used in FileOpen(). When opening a file specification of FILE_WRITE and/or FILE_READ is required.

```mql5
FILE_READ
```

---

### FILE_REWRITE
Possibility for the file rewrite using functions FileCopy() and FileMove(). The file should exist or should be opened for writing, otherwise the file will not be opened.

```mql5
FILE_REWRITE
```

---

### FILE_SHARE_READ
Shared access for reading from several programs. Flag is used in FileOpen(), but it does not replace the necessity to indicate FILE_WRITE and/or the FILE_READ flag when opening a file.

```mql5
FILE_SHARE_READ
```

---

### FILE_SHARE_WRITE
Shared access for writing from several programs. Flag is used in FileOpen(), but it does not replace the necessity to indicate FILE_WRITE and/or the FILE_READ flag when opening a file.

```mql5
FILE_SHARE_WRITE
```

---

### FILE_SIZE
File size in bytes

```mql5
FILE_SIZE
```

---

### FILE_TXT
Simple text file (the same as csv file, but without taking into account the separators). Flag is used in FileOpen().

```mql5
FILE_TXT
```

---

### FILE_UNICODE
Strings of UNICODE type (two byte symbols). Flag is used in FileOpen().

```mql5
FILE_UNICODE
```

---

### FILE_WRITE
File is opened for writing. Flag is used in FileOpen(). When opening a file specification of FILE_WRITE and/or FILE_READ is required.

```mql5
FILE_WRITE
```

---

### FLT_DIG
Number of significant decimal digits for float type

```mql5
FLT_DIG
```

---

### FLT_EPSILON
Minimal value, which satisfies the condition:
1.0+DBL_EPSILON != 1.0 (for float type)

```mql5
FLT_EPSILON
```

---

### FLT_MANT_DIG
Bits count in a mantissa for float type

```mql5
FLT_MANT_DIG
```

---

### FLT_MAX
Maximal value, which can be represented by float type

```mql5
FLT_MAX
```

---

### FLT_MAX_10_EXP
Maximal decimal value of exponent degree for float type

```mql5
FLT_MAX_10_EXP
```

---

### FLT_MAX_EXP
Maximal binary value of exponent degree for float type

```mql5
FLT_MAX_EXP
```

---

### FLT_MIN
Minimal positive value, which can be represented by float type

```mql5
FLT_MIN
```

---

### FLT_MIN_10_EXP
Minimal decimal value of exponent degree for float type

```mql5
FLT_MIN_10_EXP
```

---

### FLT_MIN_EXP
Minimal binary value of exponent degree for float type

```mql5
FLT_MIN_EXP
```

---

### FRIDAY
Friday

```mql5
FRIDAY
```

---

### GANN_DOWN_TREND
Line corresponding to the downward trend

```mql5
GANN_DOWN_TREND
```

---

### GANN_UP_TREND
Line corresponding to the uptrend line

```mql5
GANN_UP_TREND
```

---

### GATORJAW_LINE
Jaw line

```mql5
GATORJAW_LINE
```

---

### GATORLIPS_LINE
Lips line

```mql5
GATORLIPS_LINE
```

---

### GATORTEETH_LINE
Teeth line

```mql5
GATORTEETH_LINE
```

---

### IDABORT
"Abort" button has been pressed

```mql5
IDABORT
```

---

### IDCANCEL
"Cancel" button has been pressed

```mql5
IDCANCEL
```

---

### IDCONTINUE
"Continue" button has been pressed

```mql5
IDCONTINUE
```

---

### IDIGNORE
"Ignore" button has been pressed

```mql5
IDIGNORE
```

---

### IDNO
"No" button has been pressed

```mql5
IDNO
```

---

### IDOK
"OK" button has been pressed

```mql5
IDOK
```

---

### IDRETRY
"Retry" button has been pressed

```mql5
IDRETRY
```

---

### IDTRYAGAIN
"Try Again" button has been pressed

```mql5
IDTRYAGAIN
```

---

### IDYES
"Yes" button has been pressed

```mql5
IDYES
```

---

### IND_AC
Accelerator Oscillator

```mql5
IND_AC
```

---

### IND_AD
Accumulation/Distribution

```mql5
IND_AD
```

---

### IND_ADX
Average Directional Index

```mql5
IND_ADX
```

---

### IND_ADXW
ADX by Welles Wilder

```mql5
IND_ADXW
```

---

### IND_ALLIGATOR
Alligator

```mql5
IND_ALLIGATOR
```

---

### IND_AMA
Adaptive Moving Average

```mql5
IND_AMA
```

---

### IND_AO
Awesome Oscillator

```mql5
IND_AO
```

---

### IND_ATR
Average True Range

```mql5
IND_ATR
```

---

### IND_BANDS
Bollinger Bands®

```mql5
IND_BANDS
```

---

### IND_BEARS
Bears Power

```mql5
IND_BEARS
```

---

### IND_BULLS
Bulls Power

```mql5
IND_BULLS
```

---

### IND_BWMFI
Market Facilitation Index

```mql5
IND_BWMFI
```

---

### IND_CCI
Commodity Channel Index

```mql5
IND_CCI
```

---

### IND_CHAIKIN
Chaikin Oscillator

```mql5
IND_CHAIKIN
```

---

### IND_CUSTOM
Custom indicator

```mql5
IND_CUSTOM
```

---

### IND_DEMA
Double Exponential Moving Average

```mql5
IND_DEMA
```

---

### IND_DEMARKER
DeMarker

```mql5
IND_DEMARKER
```

---

### IND_ENVELOPES
Envelopes

```mql5
IND_ENVELOPES
```

---

### IND_FORCE
Force Index

```mql5
IND_FORCE
```

---

### IND_FRACTALS
Fractals

```mql5
IND_FRACTALS
```

---

### IND_FRAMA
Fractal Adaptive Moving Average

```mql5
IND_FRAMA
```

---

### IND_GATOR
Gator Oscillator

```mql5
IND_GATOR
```

---

### IND_ICHIMOKU
Ichimoku Kinko Hyo

```mql5
IND_ICHIMOKU
```

---

### IND_MA
Moving Average

```mql5
IND_MA
```

---

### IND_MACD
MACD

```mql5
IND_MACD
```

---

### IND_MFI
Money Flow Index

```mql5
IND_MFI
```

---

### IND_MOMENTUM
Momentum

```mql5
IND_MOMENTUM
```

---

### IND_OBV
On Balance Volume

```mql5
IND_OBV
```

---

### IND_OSMA
OsMA

```mql5
IND_OSMA
```

---

### IND_RSI
Relative Strength Index

```mql5
IND_RSI
```

---

### IND_RVI
Relative Vigor Index

```mql5
IND_RVI
```

---

### IND_SAR
Parabolic SAR

```mql5
IND_SAR
```

---

### IND_STDDEV
Standard Deviation

```mql5
IND_STDDEV
```

---

### IND_STOCHASTIC
Stochastic Oscillator

```mql5
IND_STOCHASTIC
```

---

### IND_TEMA
Triple Exponential Moving Average

```mql5
IND_TEMA
```

---

### IND_TRIX
Triple Exponential Moving Averages Oscillator

```mql5
IND_TRIX
```

---

### IND_VIDYA
Variable Index Dynamic Average

```mql5
IND_VIDYA
```

---

### IND_VOLUMES
Volumes

```mql5
IND_VOLUMES
```

---

### IND_WPR
Williams' Percent Range

```mql5
IND_WPR
```

---

### INDICATOR_CALCULATIONS
Auxiliary buffers for intermediate calculations

```mql5
INDICATOR_CALCULATIONS
```

---

### INDICATOR_COLOR_INDEX
Color

```mql5
INDICATOR_COLOR_INDEX
```

---

### INDICATOR_DATA
Data to draw

```mql5
INDICATOR_DATA
```

---

### INDICATOR_DIGITS
Accuracy of drawing of indicator values

```mql5
INDICATOR_DIGITS
```

---

### INDICATOR_HEIGHT
Fixed height of the indicator's window (the preprocessor command #property indicator_height)

```mql5
INDICATOR_HEIGHT
```

---

### INDICATOR_LEVELCOLOR
Color of the level line

```mql5
INDICATOR_LEVELCOLOR
```

---

### INDICATOR_LEVELS
Number of levels in the indicator window

```mql5
INDICATOR_LEVELS
```

---

### INDICATOR_LEVELSTYLE
Style of the level line

```mql5
INDICATOR_LEVELSTYLE
```

---

### INDICATOR_LEVELTEXT
Level description

```mql5
INDICATOR_LEVELTEXT
```

---

### INDICATOR_LEVELVALUE
Level value

```mql5
INDICATOR_LEVELVALUE
```

---

### INDICATOR_LEVELWIDTH
Thickness of the level line

```mql5
INDICATOR_LEVELWIDTH
```

---

### INDICATOR_MAXIMUM
Maximum of the indicator window

```mql5
INDICATOR_MAXIMUM
```

---

### INDICATOR_MINIMUM
Minimum of the indicator window

```mql5
INDICATOR_MINIMUM
```

---

### INDICATOR_SHORTNAME
Short indicator name

```mql5
INDICATOR_SHORTNAME
```

---

### INT_MAX
Maximal value, which can be represented by int type

```mql5
INT_MAX
```

---

### INT_MIN
Minimal value, which can be represented by int type

```mql5
INT_MIN
```

---

### INVALID_HANDLE
Incorrect handle

```mql5
INVALID_HANDLE
```

---

### IS_DEBUG_MODE
Flag that a mq5-program operates in debug mode

```mql5
IS_DEBUG_MODE
```

---

### IS_PROFILE_MODE
Flag that a mq5-program operates in profiling mode

```mql5
IS_PROFILE_MODE
```

---

### KIJUNSEN_LINE
Kijun-sen line

```mql5
KIJUNSEN_LINE
```

---

### LICENSE_DEMO
A trial version of a paid product from the Market. It works only in the strategy tester

```mql5
LICENSE_DEMO
```

---

### LICENSE_FREE
A free unlimited version

```mql5
LICENSE_FREE
```

---

### LICENSE_FULL
A purchased licensed version allows at least 5 activations. The number of activations is specified by seller. Seller may increase the allowed number of activations

```mql5
LICENSE_FULL
```

---

### LICENSE_TIME
A version with a limited term license

```mql5
LICENSE_TIME
```

---

### LONG_MAX
Maximal value, which can be represented by long type

```mql5
LONG_MAX
```

---

### LONG_MIN
Minimal value, which can be represented by long type

```mql5
LONG_MIN
```

---

### LOWER_BAND
Lower limit

```mql5
LOWER_BAND
```

---

### LOWER_HISTOGRAM
Bottom histogram

```mql5
LOWER_HISTOGRAM
```

---

### LOWER_LINE
Bottom line

```mql5
LOWER_LINE
```

---

### M_1_PI
1/pi

```mql5
M_1_PI
```

---

### M_2_PI
2/pi

```mql5
M_2_PI
```

---

### M_2_SQRTPI
2/sqrt(pi)

```mql5
M_2_SQRTPI
```

---

### M_E
e

```mql5
M_E
```

---

### M_LN10
ln(10)

```mql5
M_LN10
```

---

### M_LN2
ln(2)

```mql5
M_LN2
```

---

### M_LOG10E
log10(e)

```mql5
M_LOG10E
```

---

### M_LOG2E
log2(e)

```mql5
M_LOG2E
```

---

### M_PI
pi

```mql5
M_PI
```

---

### M_PI_2
pi/2

```mql5
M_PI_2
```

---

### M_PI_4
pi/4

```mql5
M_PI_4
```

---

### M_SQRT1_2
1/sqrt(2)

```mql5
M_SQRT1_2
```

---

### M_SQRT2
sqrt(2)

```mql5
M_SQRT2
```

---

### MAIN_LINE
Main line

```mql5
MAIN_LINE
```

---

### MB_ABORTRETRYIGNORE
Message window contains three buttons: Abort, Retry and Ignore

```mql5
MB_ABORTRETRYIGNORE
```

---

### MB_CANCELTRYCONTINUE
Message window contains three buttons: Cancel, Try Again, Continue

```mql5
MB_CANCELTRYCONTINUE
```

---

### MB_DEFBUTTON1
The first button MB_DEFBUTTON1 - is default, if the other buttons MB_DEFBUTTON2, MB_DEFBUTTON3, or MB_DEFBUTTON4 are not specified

```mql5
MB_DEFBUTTON1
```

---

### MB_DEFBUTTON2
The second button is default

```mql5
MB_DEFBUTTON2
```

---

### MB_DEFBUTTON3
The third button is default

```mql5
MB_DEFBUTTON3
```

---

### MB_DEFBUTTON4
The fourth button is default

```mql5
MB_DEFBUTTON4
```

---

### MB_ICONEXCLAMATION, 
MB_ICONWARNING
The exclamation/warning sign icon

```mql5
MB_ICONEXCLAMATION, 
MB_ICONWARNING
```

---

### MB_ICONINFORMATION, 
MB_ICONASTERISK
The encircled i sign

```mql5
MB_ICONINFORMATION, 
MB_ICONASTERISK
```

---

### MB_ICONQUESTION
The question sign icon

```mql5
MB_ICONQUESTION
```

---

### MB_ICONSTOP, 
MB_ICONERROR, 
MB_ICONHAND
The STOP sign icon

```mql5
MB_ICONSTOP, 
MB_ICONERROR, 
MB_ICONHAND
```

---

### MB_OK
Message window contains only one button: OK. Default

```mql5
MB_OK
```

---

### MB_OKCANCEL
Message window contains two buttons: OK and Cancel

```mql5
MB_OKCANCEL
```

---

### MB_RETRYCANCEL
Message window contains two buttons: Retry and Cancel

```mql5
MB_RETRYCANCEL
```

---

### MB_YESNO
Message window contains two buttons: Yes and No

```mql5
MB_YESNO
```

---

### MB_YESNOCANCEL
Message window contains three buttons: Yes, No and Cancel

```mql5
MB_YESNOCANCEL
```

---

### MINUSDI_LINE
Line –DI

```mql5
MINUSDI_LINE
```

---

### MODE_EMA
Exponential averaging

```mql5
MODE_EMA
```

---

### MODE_LWMA
Linear-weighted averaging

```mql5
MODE_LWMA
```

---

### MODE_SMA
Simple averaging

```mql5
MODE_SMA
```

---

### MODE_SMMA
Smoothed averaging

```mql5
MODE_SMMA
```

---

### MONDAY
Monday

```mql5
MONDAY
```

---

### MQL_DEBUG
The flag, that indicates the debug mode

```mql5
MQL_DEBUG
```

---

### MQL_DLLS_ALLOWED
The permission to use DLL for the given executed program

```mql5
MQL_DLLS_ALLOWED
```

---

### MQL_FRAME_MODE
The flag, that indicates the Expert Advisor operating in gathering optimization result frames mode

```mql5
MQL_FRAME_MODE
```

---

### MQL_LICENSE_TYPE
Type of license of the EX5 module. The license refers to the EX5 module, from which a request is made using MQLInfoInteger(MQL_LICENSE_TYPE).

```mql5
MQL_LICENSE_TYPE
```

---

### MQL_MEMORY_LIMIT
Maximum possible amount of dynamic memory for MQL5 program in MB

```mql5
MQL_MEMORY_LIMIT
```

---

### MQL_MEMORY_USED
The memory size used by MQL5 program in MB

```mql5
MQL_MEMORY_USED
```

---

### MQL_OPTIMIZATION
The flag, that indicates the optimization process

```mql5
MQL_OPTIMIZATION
```

---

### MQL_PROFILER
The flag, that indicates the program operating in the code profiling mode

```mql5
MQL_PROFILER
```

---

### MQL_PROGRAM_NAME
Name of the mql5-program executed

```mql5
MQL_PROGRAM_NAME
```

---

### MQL_PROGRAM_PATH
Path for the given executed program

```mql5
MQL_PROGRAM_PATH
```

---

### MQL_PROGRAM_TYPE
Type of the mql5 program

```mql5
MQL_PROGRAM_TYPE
```

---

### MQL_SIGNALS_ALLOWED
The permission to modify the Signals for the given executed program

```mql5
MQL_SIGNALS_ALLOWED
```

---

### MQL_TESTER
The flag, that indicates the tester process

```mql5
MQL_TESTER
```

---

### MQL_TRADE_ALLOWED
The permission to trade for the given executed program

```mql5
MQL_TRADE_ALLOWED
```

---

### MQL_VISUAL_MODE
The flag, that indicates the visual tester process

```mql5
MQL_VISUAL_MODE
```

---

### NULL
Zero for any types

```mql5
NULL
```

---

### OBJ_ALL_PERIODS
The object is drawn in all timeframes

```mql5
OBJ_ALL_PERIODS
```

---

### OBJ_ARROW
Arrow

```mql5
OBJ_ARROW
```

---

### OBJ_ARROW_BUY
Buy Sign

```mql5
OBJ_ARROW_BUY
```

---

### OBJ_ARROW_CHECK
Check Sign

```mql5
OBJ_ARROW_CHECK
```

---

### OBJ_ARROW_DOWN
Arrow Down

```mql5
OBJ_ARROW_DOWN
```

---

### OBJ_ARROW_LEFT_PRICE
Left Price Label

```mql5
OBJ_ARROW_LEFT_PRICE
```

---

### OBJ_ARROW_RIGHT_PRICE
Right Price Label

```mql5
OBJ_ARROW_RIGHT_PRICE
```

---

### OBJ_ARROW_SELL
Sell Sign

```mql5
OBJ_ARROW_SELL
```

---

### OBJ_ARROW_STOP
Stop Sign

```mql5
OBJ_ARROW_STOP
```

---

### OBJ_ARROW_THUMB_DOWN
Thumbs Down

```mql5
OBJ_ARROW_THUMB_DOWN
```

---

### OBJ_ARROW_THUMB_UP
Thumbs Up

```mql5
OBJ_ARROW_THUMB_UP
```

---

### OBJ_ARROW_UP
Arrow Up

```mql5
OBJ_ARROW_UP
```

---

### OBJ_ARROWED_LINE
Arrowed Line

```mql5
OBJ_ARROWED_LINE
```

---

### OBJ_BITMAP
Bitmap

```mql5
OBJ_BITMAP
```

---

### OBJ_BITMAP_LABEL
Bitmap Label

```mql5
OBJ_BITMAP_LABEL
```

---

### OBJ_BUTTON
Button

```mql5
OBJ_BUTTON
```

---

### OBJ_CHANNEL
Equidistant Channel

```mql5
OBJ_CHANNEL
```

---

### OBJ_CHART
Chart

```mql5
OBJ_CHART
```

---

### OBJ_CYCLES
Cycle Lines

```mql5
OBJ_CYCLES
```

---

### OBJ_EDIT
Edit

```mql5
OBJ_EDIT
```

---

### OBJ_ELLIOTWAVE3
Elliott Correction Wave

```mql5
OBJ_ELLIOTWAVE3
```

---

### OBJ_ELLIOTWAVE5
Elliott Motive Wave

```mql5
OBJ_ELLIOTWAVE5
```

---

### OBJ_ELLIPSE
Ellipse

```mql5
OBJ_ELLIPSE
```

---

### OBJ_EVENT
The "Event" object corresponding to an event in the economic calendar

```mql5
OBJ_EVENT
```

---

### OBJ_EXPANSION
Fibonacci Expansion

```mql5
OBJ_EXPANSION
```

---

### OBJ_FIBO
Fibonacci Retracement

```mql5
OBJ_FIBO
```

---

### OBJ_FIBOARC
Fibonacci Arcs

```mql5
OBJ_FIBOARC
```

---

### OBJ_FIBOCHANNEL
Fibonacci Channel

```mql5
OBJ_FIBOCHANNEL
```

---

### OBJ_FIBOFAN
Fibonacci Fan

```mql5
OBJ_FIBOFAN
```

---

### OBJ_FIBOTIMES
Fibonacci Time Zones

```mql5
OBJ_FIBOTIMES
```

---

### OBJ_GANNFAN
Gann Fan

```mql5
OBJ_GANNFAN
```

---

### OBJ_GANNGRID
Gann Grid

```mql5
OBJ_GANNGRID
```

---

### OBJ_GANNLINE
Gann Line

```mql5
OBJ_GANNLINE
```

---

### OBJ_HLINE
Horizontal Line

```mql5
OBJ_HLINE
```

---

### OBJ_LABEL
Label

```mql5
OBJ_LABEL
```

---

### OBJ_NO_PERIODS
The object is not drawn in all timeframes

```mql5
OBJ_NO_PERIODS
```

---

### OBJ_PERIOD_D1
The object is drawn in day charts

```mql5
OBJ_PERIOD_D1
```

---

### OBJ_PERIOD_H1
The object is drawn in 1-hour chart

```mql5
OBJ_PERIOD_H1
```

---

### OBJ_PERIOD_H12
The object is drawn in 12-hour chart

```mql5
OBJ_PERIOD_H12
```

---

### OBJ_PERIOD_H2
The object is drawn in 2-hour chart

```mql5
OBJ_PERIOD_H2
```

---

### OBJ_PERIOD_H3
The object is drawn in 3-hour chart

```mql5
OBJ_PERIOD_H3
```

---

### OBJ_PERIOD_H4
The object is drawn in 4-hour chart

```mql5
OBJ_PERIOD_H4
```

---

### OBJ_PERIOD_H6
The object is drawn in 6-hour chart

```mql5
OBJ_PERIOD_H6
```

---

### OBJ_PERIOD_H8
The object is drawn in 8-hour chart

```mql5
OBJ_PERIOD_H8
```

---

### OBJ_PERIOD_M1
The object is drawn in 1-minute chart

```mql5
OBJ_PERIOD_M1
```

---

### OBJ_PERIOD_M10
The object is drawn in 10-minute chart

```mql5
OBJ_PERIOD_M10
```

---

### OBJ_PERIOD_M12
The object is drawn in 12-minute chart

```mql5
OBJ_PERIOD_M12
```

---

### OBJ_PERIOD_M15
The object is drawn in 15-minute chart

```mql5
OBJ_PERIOD_M15
```

---

### OBJ_PERIOD_M2
The object is drawn in 2-minute chart

```mql5
OBJ_PERIOD_M2
```

---

### OBJ_PERIOD_M20
The object is drawn in 20-minute chart

```mql5
OBJ_PERIOD_M20
```

---

### OBJ_PERIOD_M3
The object is drawn in 3-minute chart

```mql5
OBJ_PERIOD_M3
```

---

### OBJ_PERIOD_M30
The object is drawn in 30-minute chart

```mql5
OBJ_PERIOD_M30
```

---

### OBJ_PERIOD_M4
The object is drawn in 4-minute chart

```mql5
OBJ_PERIOD_M4
```

---

### OBJ_PERIOD_M5
The object is drawn in 5-minute chart

```mql5
OBJ_PERIOD_M5
```

---

### OBJ_PERIOD_M6
The object is drawn in 6-minute chart

```mql5
OBJ_PERIOD_M6
```

---

### OBJ_PERIOD_MN1
The object is drawn in month charts

```mql5
OBJ_PERIOD_MN1
```

---

### OBJ_PERIOD_W1
The object is drawn in week charts

```mql5
OBJ_PERIOD_W1
```

---

### OBJ_PITCHFORK
Andrews’ Pitchfork

```mql5
OBJ_PITCHFORK
```

---

### OBJ_RECTANGLE
Rectangle

```mql5
OBJ_RECTANGLE
```

---

### OBJ_RECTANGLE_LABEL
The "Rectangle label" object for creating and designing the custom graphical interface.

```mql5
OBJ_RECTANGLE_LABEL
```

---

### OBJ_REGRESSION
Linear Regression Channel

```mql5
OBJ_REGRESSION
```

---

### OBJ_STDDEVCHANNEL
Standard Deviation Channel

```mql5
OBJ_STDDEVCHANNEL
```

---

### OBJ_TEXT
Text

```mql5
OBJ_TEXT
```

---

### OBJ_TREND
Trend Line

```mql5
OBJ_TREND
```

---

### OBJ_TRENDBYANGLE
Trend Line By Angle

```mql5
OBJ_TRENDBYANGLE
```

---

### OBJ_TRIANGLE
Triangle

```mql5
OBJ_TRIANGLE
```

---

### OBJ_VLINE
Vertical Line

```mql5
OBJ_VLINE
```

---

### OBJPROP_ALIGN
Horizontal text alignment in the "Edit" object (OBJ_EDIT)

```mql5
OBJPROP_ALIGN
```

---

### OBJPROP_ANCHOR
Location of the anchor point of a graphical object

```mql5
OBJPROP_ANCHOR
```

---

### OBJPROP_ANGLE
Angle. For the objects with no angle specified, created from a program, the value is equal to EMPTY_VALUE

```mql5
OBJPROP_ANGLE
```

---

### OBJPROP_ARROWCODE
Arrow code for the Arrow object

```mql5
OBJPROP_ARROWCODE
```

---

### OBJPROP_BACK
Object in the background

```mql5
OBJPROP_BACK
```

---

### OBJPROP_BGCOLOR
The background color for  OBJ_EDIT, OBJ_BUTTON, OBJ_RECTANGLE_LABEL

```mql5
OBJPROP_BGCOLOR
```

---

### OBJPROP_BMPFILE
The name of BMP-file for Bitmap Label. See also Resources

```mql5
OBJPROP_BMPFILE
```

---

### OBJPROP_BORDER_COLOR
Border color for the OBJ_EDIT and OBJ_BUTTON objects

```mql5
OBJPROP_BORDER_COLOR
```

---

### OBJPROP_BORDER_TYPE
Border type for the "Rectangle label" object

```mql5
OBJPROP_BORDER_TYPE
```

---

### OBJPROP_CHART_ID
ID of the "Chart" object (OBJ_CHART). It allows working with the properties of this object like with a normal chart using the functions described in Chart Operations, but there some exceptions.

```mql5
OBJPROP_CHART_ID
```

---

### OBJPROP_CHART_SCALE
The scale for the Chart object

```mql5
OBJPROP_CHART_SCALE
```

---

### OBJPROP_COLOR
Color

```mql5
OBJPROP_COLOR
```

---

### OBJPROP_CORNER
The corner of the chart to link a graphical object

```mql5
OBJPROP_CORNER
```

---

### OBJPROP_CREATETIME
Time of object creation

```mql5
OBJPROP_CREATETIME
```

---

### OBJPROP_DATE_SCALE
Displaying the time scale for the Chart object

```mql5
OBJPROP_DATE_SCALE
```

---

### OBJPROP_DEGREE
Level of the Elliott Wave Marking

```mql5
OBJPROP_DEGREE
```

---

### OBJPROP_DEVIATION
Deviation for the Standard Deviation Channel

```mql5
OBJPROP_DEVIATION
```

---

### OBJPROP_DIRECTION
Trend of the Gann object

```mql5
OBJPROP_DIRECTION
```

---

### OBJPROP_DRAWLINES
Displaying lines for marking the Elliott Wave

```mql5
OBJPROP_DRAWLINES
```

---

### OBJPROP_ELLIPSE
Showing the full ellipse of the Fibonacci Arc object (OBJ_FIBOARC)

```mql5
OBJPROP_ELLIPSE
```

---

### OBJPROP_FILL
Fill an object with color (for OBJ_RECTANGLE, OBJ_TRIANGLE, OBJ_ELLIPSE, OBJ_CHANNEL, OBJ_STDDEVCHANNEL, OBJ_REGRESSION)

```mql5
OBJPROP_FILL
```

---

### OBJPROP_FONT
Font

```mql5
OBJPROP_FONT
```

---

### OBJPROP_FONTSIZE
Font size

```mql5
OBJPROP_FONTSIZE
```

---

### OBJPROP_HIDDEN
Prohibit showing of the name of a graphical object in the list of objects from the terminal menu "Charts" - "Objects" - "List of objects". The true value allows to hide an object from the list. By default, true is set to the objects that display calendar events, trading history and to the objects created from MQL5 programs. To see such graphical objects and access their properties, click on the "All" button in the "List of objects" window.

```mql5
OBJPROP_HIDDEN
```

---

### OBJPROP_LEVELCOLOR
Color of the line-level

```mql5
OBJPROP_LEVELCOLOR
```

---

### OBJPROP_LEVELS
Number of levels

```mql5
OBJPROP_LEVELS
```

---

### OBJPROP_LEVELSTYLE
Style of the line-level

```mql5
OBJPROP_LEVELSTYLE
```

---

### OBJPROP_LEVELTEXT
Level description

```mql5
OBJPROP_LEVELTEXT
```

---

### OBJPROP_LEVELVALUE
Level value

```mql5
OBJPROP_LEVELVALUE
```

---

### OBJPROP_LEVELWIDTH
Thickness of the line-level

```mql5
OBJPROP_LEVELWIDTH
```

---

### OBJPROP_NAME
Object name

```mql5
OBJPROP_NAME
```

---

### OBJPROP_PERIOD
Timeframe for the Chart object

```mql5
OBJPROP_PERIOD
```

---

### OBJPROP_PRICE
Price coordinate

```mql5
OBJPROP_PRICE
```

---

### OBJPROP_PRICE_SCALE
Displaying the price scale for the Chart object

```mql5
OBJPROP_PRICE_SCALE
```

---

### OBJPROP_RAY
A vertical line goes through all the windows of a chart

```mql5
OBJPROP_RAY
```

---

### OBJPROP_RAY_LEFT
Ray goes to the left

```mql5
OBJPROP_RAY_LEFT
```

---

### OBJPROP_RAY_RIGHT
Ray goes to the right

```mql5
OBJPROP_RAY_RIGHT
```

---

### OBJPROP_READONLY
Ability to edit text in the Edit object

```mql5
OBJPROP_READONLY
```

---

### OBJPROP_SCALE
Scale (properties of Gann objects and Fibonacci Arcs)

```mql5
OBJPROP_SCALE
```

---

### OBJPROP_SELECTABLE
Object availability

```mql5
OBJPROP_SELECTABLE
```

---

### OBJPROP_SELECTED
Object is selected

```mql5
OBJPROP_SELECTED
```

---

### OBJPROP_STATE
Button state (pressed / depressed)

```mql5
OBJPROP_STATE
```

---

### OBJPROP_STYLE
Style

```mql5
OBJPROP_STYLE
```

---

### OBJPROP_SYMBOL
Symbol for the Chart object

```mql5
OBJPROP_SYMBOL
```

---

### OBJPROP_TEXT
Description of the object (the text contained in the object)

```mql5
OBJPROP_TEXT
```

---

### OBJPROP_TIME
Time coordinate

```mql5
OBJPROP_TIME
```

---

### OBJPROP_TIMEFRAMES
Visibility of an object at timeframes

```mql5
OBJPROP_TIMEFRAMES
```

---

### OBJPROP_TOOLTIP
The text of a tooltip. If the property is not set, then the tooltip generated automatically by the terminal is shown. A tooltip can be disabled by setting the "\n" (line feed) value to it

```mql5
OBJPROP_TOOLTIP
```

---

### OBJPROP_TYPE
Object type

```mql5
OBJPROP_TYPE
```

---

### OBJPROP_WIDTH
Line thickness

```mql5
OBJPROP_WIDTH
```

---

### OBJPROP_XDISTANCE
The distance in pixels along the X axis from the binding corner (see note)

```mql5
OBJPROP_XDISTANCE
```

---

### OBJPROP_XOFFSET
The X coordinate of the upper left corner of the rectangular visible area in the graphical objects "Bitmap Label" and "Bitmap" (OBJ_BITMAP_LABEL and OBJ_BITMAP). The value is set in pixels relative to the upper left corner of the original image.

```mql5
OBJPROP_XOFFSET
```

---

### OBJPROP_XSIZE
The object's width along the X axis in pixels. Specified for  OBJ_LABEL (read only), OBJ_BUTTON, OBJ_CHART, OBJ_BITMAP, OBJ_BITMAP_LABEL, OBJ_EDIT, OBJ_RECTANGLE_LABEL objects.

```mql5
OBJPROP_XSIZE
```

---

### OBJPROP_YDISTANCE
The distance in pixels along the Y axis from the binding corner (see note)

```mql5
OBJPROP_YDISTANCE
```

---

### OBJPROP_YOFFSET
The Y coordinate of the upper left corner of the rectangular visible area in the graphical objects "Bitmap Label" and "Bitmap" (OBJ_BITMAP_LABEL and OBJ_BITMAP). The value is set in pixels relative to the upper left corner of the original image.

```mql5
OBJPROP_YOFFSET
```

---

### OBJPROP_YSIZE
The object's height along the Y axis in pixels. Specified for  OBJ_LABEL (read only), OBJ_BUTTON, OBJ_CHART, OBJ_BITMAP, OBJ_BITMAP_LABEL, OBJ_EDIT, OBJ_RECTANGLE_LABEL objects.

```mql5
OBJPROP_YSIZE
```

---

### OBJPROP_ZORDER
Priority of a graphical object for receiving events of clicking on a chart (CHARTEVENT_CLICK). The default zero value is set when creating an object; the priority can be increased if necessary. When applying objects one over another, only one of them with the highest priority will receive the CHARTEVENT_CLICK event.

```mql5
OBJPROP_ZORDER
```

---

### ORDER_COMMENT
Order comment

```mql5
ORDER_COMMENT
```

---

### ORDER_FILLING_FOK
This filling policy means that an order can be filled only in the specified amount. If the necessary amount of a financial instrument is currently unavailable in the market, the order will not be executed. The required volume can be filled using several offers available on the market at the moment.

```mql5
ORDER_FILLING_FOK
```

---

### ORDER_FILLING_IOC
This mode means that a trader agrees to execute a deal with the volume maximally available in the market within that indicated in the order. In case the the entire volume of an order cannot be filled, the available volume of it will be filled, and the remaining volume will be canceled.

```mql5
ORDER_FILLING_IOC
```

---

### ORDER_FILLING_RETURN
This policy is used only for market orders (ORDER_TYPE_BUY and ORDER_TYPE_SELL), limit and stop limit orders (ORDER_TYPE_BUY_LIMIT, ORDER_TYPE_SELL_LIMIT, ORDER_TYPE_BUY_STOP_LIMIT and ORDER_TYPE_SELL_STOP_LIMIT ) and only for the symbols with Market or Exchange execution. In case of partial filling a market or limit order with remaining volume is not canceled but processed further.
For the activation of the ORDER_TYPE_BUY_STOP_LIMIT and ORDER_TYPE_SELL_STOP_LIMIT orders, a corresponding limit order ORDER_TYPE_BUY_LIMIT/ORDER_TYPE_SELL_LIMIT with the ORDER_FILLING_RETURN execution type is created.

```mql5
ORDER_FILLING_RETURN
```

---

### ORDER_MAGIC
ID of an Expert Advisor that has placed the order (designed to ensure that each Expert Advisor places its own unique number)

```mql5
ORDER_MAGIC
```

---

### ORDER_POSITION_ID
Position identifier that is set to an order as soon as it is executed. Each executed order results in a deal that opens or modifies an already existing position. The identifier of exactly this position is set to the executed order at this moment.

```mql5
ORDER_POSITION_ID
```

---

### ORDER_PRICE_CURRENT
The current price of the order symbol

```mql5
ORDER_PRICE_CURRENT
```

---

### ORDER_PRICE_OPEN
Price specified in the order

```mql5
ORDER_PRICE_OPEN
```

---

### ORDER_PRICE_STOPLIMIT
The Limit order price for the StopLimit order

```mql5
ORDER_PRICE_STOPLIMIT
```

---

### ORDER_SL
Stop Loss value

```mql5
ORDER_SL
```

---

### ORDER_STATE
Order state

```mql5
ORDER_STATE
```

---

### ORDER_STATE_CANCELED
Order canceled by client

```mql5
ORDER_STATE_CANCELED
```

---

### ORDER_STATE_EXPIRED
Order expired

```mql5
ORDER_STATE_EXPIRED
```

---

### ORDER_STATE_FILLED
Order fully executed

```mql5
ORDER_STATE_FILLED
```

---

### ORDER_STATE_PARTIAL
Order partially executed

```mql5
ORDER_STATE_PARTIAL
```

---

### ORDER_STATE_PLACED
Order accepted

```mql5
ORDER_STATE_PLACED
```

---

### ORDER_STATE_REJECTED
Order rejected

```mql5
ORDER_STATE_REJECTED
```

---

### ORDER_STATE_REQUEST_ADD
Order is being registered (placing to the trading system)

```mql5
ORDER_STATE_REQUEST_ADD
```

---

### ORDER_STATE_REQUEST_CANCEL
Order is being deleted (deleting from the trading system)

```mql5
ORDER_STATE_REQUEST_CANCEL
```

---

### ORDER_STATE_REQUEST_MODIFY
Order is being modified (changing its parameters)

```mql5
ORDER_STATE_REQUEST_MODIFY
```

---

### ORDER_STATE_STARTED
Order checked, but not yet accepted by broker

```mql5
ORDER_STATE_STARTED
```

---

### ORDER_SYMBOL
Symbol of the order

```mql5
ORDER_SYMBOL
```

---

### ORDER_TIME_DAY
Good till current trade day order

```mql5
ORDER_TIME_DAY
```

---

### ORDER_TIME_DONE
Order execution or cancellation time

```mql5
ORDER_TIME_DONE
```

---

### ORDER_TIME_DONE_MSC
Order execution/cancellation time in milliseconds since 01.01.1970

```mql5
ORDER_TIME_DONE_MSC
```

---

### ORDER_TIME_EXPIRATION
Order expiration time

```mql5
ORDER_TIME_EXPIRATION
```

---

### ORDER_TIME_GTC
Good till cancel order

```mql5
ORDER_TIME_GTC
```

---

### ORDER_TIME_SETUP
Order setup time

```mql5
ORDER_TIME_SETUP
```

---

### ORDER_TIME_SETUP_MSC
The time of placing an order for execution in milliseconds since 01.01.1970

```mql5
ORDER_TIME_SETUP_MSC
```

---

### ORDER_TIME_SPECIFIED
Good till expired order

```mql5
ORDER_TIME_SPECIFIED
```

---

### ORDER_TIME_SPECIFIED_DAY
The order will be effective till 23:59:59 of the specified day. If this time is outside a trading session, the order expires in the nearest trading time.

```mql5
ORDER_TIME_SPECIFIED_DAY
```

---

### ORDER_TP
Take Profit value

```mql5
ORDER_TP
```

---

### ORDER_TYPE
Order type

```mql5
ORDER_TYPE
```

---

### ORDER_TYPE_BUY
Market Buy order

```mql5
ORDER_TYPE_BUY
```

---

### ORDER_TYPE_BUY_LIMIT
Buy Limit pending order

```mql5
ORDER_TYPE_BUY_LIMIT
```

---

### ORDER_TYPE_BUY_STOP
Buy Stop pending order

```mql5
ORDER_TYPE_BUY_STOP
```

---

### ORDER_TYPE_BUY_STOP_LIMIT
Upon reaching the order price, a pending Buy Limit order is placed at the StopLimit price

```mql5
ORDER_TYPE_BUY_STOP_LIMIT
```

---

### ORDER_TYPE_FILLING
Order filling type

```mql5
ORDER_TYPE_FILLING
```

---

### ORDER_TYPE_SELL
Market Sell order

```mql5
ORDER_TYPE_SELL
```

---

### ORDER_TYPE_SELL_LIMIT
Sell Limit pending order

```mql5
ORDER_TYPE_SELL_LIMIT
```

---

### ORDER_TYPE_SELL_STOP
Sell Stop pending order

```mql5
ORDER_TYPE_SELL_STOP
```

---

### ORDER_TYPE_SELL_STOP_LIMIT
Upon reaching the order price, a pending Sell Limit order is placed at the StopLimit price

```mql5
ORDER_TYPE_SELL_STOP_LIMIT
```

---

### ORDER_TYPE_TIME
Order lifetime

```mql5
ORDER_TYPE_TIME
```

---

### ORDER_VOLUME_CURRENT
Order current volume

```mql5
ORDER_VOLUME_CURRENT
```

---

### ORDER_VOLUME_INITIAL
Order initial volume

```mql5
ORDER_VOLUME_INITIAL
```

---

### PERIOD_CURRENT
Current timeframe

```mql5
PERIOD_CURRENT
```

---

### PERIOD_D1
1 day

```mql5
PERIOD_D1
```

---

### PERIOD_H1
1 hour

```mql5
PERIOD_H1
```

---

### PERIOD_H12
12 hours

```mql5
PERIOD_H12
```

---

### PERIOD_H2
2 hours

```mql5
PERIOD_H2
```

---

### PERIOD_H3
3 hours

```mql5
PERIOD_H3
```

---

### PERIOD_H4
4 hours

```mql5
PERIOD_H4
```

---

### PERIOD_H6
6 hours

```mql5
PERIOD_H6
```

---

### PERIOD_H8
8 hours

```mql5
PERIOD_H8
```

---

### PERIOD_M1
1 minute

```mql5
PERIOD_M1
```

---

### PERIOD_M10
10 minutes

```mql5
PERIOD_M10
```

---

### PERIOD_M12
12 minutes

```mql5
PERIOD_M12
```

---

### PERIOD_M15
15 minutes

```mql5
PERIOD_M15
```

---

### PERIOD_M2
2 minutes

```mql5
PERIOD_M2
```

---

### PERIOD_M20
20 minutes

```mql5
PERIOD_M20
```

---

### PERIOD_M3
3 minutes

```mql5
PERIOD_M3
```

---

### PERIOD_M30
30 minutes

```mql5
PERIOD_M30
```

---

### PERIOD_M4
4 minutes

```mql5
PERIOD_M4
```

---

### PERIOD_M5
5 minutes

```mql5
PERIOD_M5
```

---

### PERIOD_M6
6 minutes

```mql5
PERIOD_M6
```

---

### PERIOD_MN1
1 month

```mql5
PERIOD_MN1
```

---

### PERIOD_W1
1 week

```mql5
PERIOD_W1
```

---

### PLOT_ARROW
Arrow code for style DRAW_ARROW

```mql5
PLOT_ARROW
```

---

### PLOT_ARROW_SHIFT
Vertical shift of arrows for style DRAW_ARROW

```mql5
PLOT_ARROW_SHIFT
```

---

### PLOT_COLOR_INDEXES
The number of colors

```mql5
PLOT_COLOR_INDEXES
```

---

### PLOT_DRAW_BEGIN
Number of initial bars without drawing and values in the DataWindow

```mql5
PLOT_DRAW_BEGIN
```

---

### PLOT_DRAW_TYPE
Type of graphical construction

```mql5
PLOT_DRAW_TYPE
```

---

### PLOT_EMPTY_VALUE
An empty value for plotting, for which there is no drawing

```mql5
PLOT_EMPTY_VALUE
```

---

### PLOT_LABEL
The name of the indicator graphical series to display in the DataWindow. When working with complex graphical styles requiring several indicator buffers for display, the names for each buffer can be specified using ";" as a separator. Sample code is shown in DRAW_CANDLES

```mql5
PLOT_LABEL
```

---

### PLOT_LINE_COLOR
The index of a buffer containing the drawing color

```mql5
PLOT_LINE_COLOR
```

---

### PLOT_LINE_STYLE
Drawing line style

```mql5
PLOT_LINE_STYLE
```

---

### PLOT_LINE_WIDTH
The thickness of the drawing line

```mql5
PLOT_LINE_WIDTH
```

---

### PLOT_SHIFT
Shift of indicator plotting along the time axis in bars

```mql5
PLOT_SHIFT
```

---

### PLOT_SHOW_DATA
Sign of display of construction values in the DataWindow

```mql5
PLOT_SHOW_DATA
```

---

### PLUSDI_LINE
Line +DI

```mql5
PLUSDI_LINE
```

---

### POINTER_AUTOMATIC
Pointer of any objects created automatically (not using new())

```mql5
POINTER_AUTOMATIC
```

---

### POINTER_DYNAMIC
Pointer of the object created by the new() operator

```mql5
POINTER_DYNAMIC
```

---

### POINTER_INVALID
Incorrect pointer

```mql5
POINTER_INVALID
```

---

### POSITION_COMMENT
Position comment

```mql5
POSITION_COMMENT
```

---

### POSITION_COMMISSION
Commission

```mql5
POSITION_COMMISSION
```

---

### POSITION_IDENTIFIER
Position identifier is a unique number that is assigned to every newly opened position and doesn't change during the entire lifetime of the position. Position turnover doesn't change its identifier.

```mql5
POSITION_IDENTIFIER
```

---

### POSITION_MAGIC
Position magic number (see ORDER_MAGIC)

```mql5
POSITION_MAGIC
```

---

### POSITION_PRICE_CURRENT
Current price of the position symbol

```mql5
POSITION_PRICE_CURRENT
```

---

### POSITION_PRICE_OPEN
Position open price

```mql5
POSITION_PRICE_OPEN
```

---

### POSITION_PROFIT
Current profit

```mql5
POSITION_PROFIT
```

---

### POSITION_SL
Stop Loss level of opened position

```mql5
POSITION_SL
```

---

### POSITION_SWAP
Cumulative swap

```mql5
POSITION_SWAP
```

---

### POSITION_SYMBOL
Symbol of the position

```mql5
POSITION_SYMBOL
```

---

### POSITION_TIME
Position open time

```mql5
POSITION_TIME
```

---

### POSITION_TIME_MSC
Position opening time in milliseconds since 01.01.1970

```mql5
POSITION_TIME_MSC
```

---

### POSITION_TIME_UPDATE
Position changing time in seconds since 01.01.1970

```mql5
POSITION_TIME_UPDATE
```

---

### POSITION_TIME_UPDATE_MSC
Position changing time in milliseconds since 01.01.1970

```mql5
POSITION_TIME_UPDATE_MSC
```

---

### POSITION_TP
Take Profit level of opened position

```mql5
POSITION_TP
```

---

### POSITION_TYPE
Position type

```mql5
POSITION_TYPE
```

---

### POSITION_TYPE_BUY
Buy

```mql5
POSITION_TYPE_BUY
```

---

### POSITION_TYPE_SELL
Sell

```mql5
POSITION_TYPE_SELL
```

---

### POSITION_VOLUME
Position volume

```mql5
POSITION_VOLUME
```

---

### PRICE_CLOSE
Close price

```mql5
PRICE_CLOSE
```

---

### PRICE_HIGH
The maximum price for the period

```mql5
PRICE_HIGH
```

---

### PRICE_LOW
The minimum price for the period

```mql5
PRICE_LOW
```

---

### PRICE_MEDIAN
Median price, (high + low)/2

```mql5
PRICE_MEDIAN
```

---

### PRICE_OPEN
Open price

```mql5
PRICE_OPEN
```

---

### PRICE_TYPICAL
Typical price, (high + low + close)/3

```mql5
PRICE_TYPICAL
```

---

### PRICE_WEIGHTED
Average price, (high + low + close + close)/4

```mql5
PRICE_WEIGHTED
```

---

### PROGRAM_EXPERT
Expert

```mql5
PROGRAM_EXPERT
```

---

### PROGRAM_INDICATOR
Indicator

```mql5
PROGRAM_INDICATOR
```

---

### PROGRAM_SCRIPT
Script

```mql5
PROGRAM_SCRIPT
```

---

### REASON_ACCOUNT
Another account has been activated or reconnection to the trade server has occurred due to changes in the account settings

```mql5
REASON_ACCOUNT
```

---

### REASON_CHARTCHANGE
Symbol or chart period has been changed

```mql5
REASON_CHARTCHANGE
```

---

### REASON_CHARTCLOSE
Chart has been closed

```mql5
REASON_CHARTCLOSE
```

---

### REASON_CLOSE
Terminal has been closed

```mql5
REASON_CLOSE
```

---

### REASON_INITFAILED
This value means that OnInit() handler has returned a nonzero value

```mql5
REASON_INITFAILED
```

---

### REASON_PARAMETERS
Input parameters have been changed by a user

```mql5
REASON_PARAMETERS
```

---

### REASON_PROGRAM
Expert Advisor terminated its operation by calling the ExpertRemove() function

```mql5
REASON_PROGRAM
```

---

### REASON_RECOMPILE
Program has been recompiled

```mql5
REASON_RECOMPILE
```

---

### REASON_REMOVE
Program has been deleted from the chart

```mql5
REASON_REMOVE
```

---

### REASON_TEMPLATE
A new template has been applied

```mql5
REASON_TEMPLATE
```

---

### SATURDAY
Saturday

```mql5
SATURDAY
```

---

### SEEK_CUR
Current position of a file pointer

```mql5
SEEK_CUR
```

---

### SEEK_END
File end

```mql5
SEEK_END
```

---

### SEEK_SET
File beginning

```mql5
SEEK_SET
```

---

### SENKOUSPANA_LINE
Senkou Span A line

```mql5
SENKOUSPANA_LINE
```

---

### SENKOUSPANB_LINE
Senkou Span B line

```mql5
SENKOUSPANB_LINE
```

---

### SERIES_BARS_COUNT
Bars count for the symbol-period for the current moment

```mql5
SERIES_BARS_COUNT
```

---

### SERIES_FIRSTDATE
The very first date for the symbol-period for the current moment

```mql5
SERIES_FIRSTDATE
```

---

### SERIES_LASTBAR_DATE
Open time of the last bar of the symbol-period

```mql5
SERIES_LASTBAR_DATE
```

---

### SERIES_SERVER_FIRSTDATE
The very first date in the history of the symbol on the server regardless of the timeframe

```mql5
SERIES_SERVER_FIRSTDATE
```

---

### SERIES_SYNCHRONIZED
Symbol/period data synchronization flag for the current moment

```mql5
SERIES_SYNCHRONIZED
```

---

### SERIES_TERMINAL_FIRSTDATE
The very first date in the history of the symbol in the client terminal, regardless of the timeframe

```mql5
SERIES_TERMINAL_FIRSTDATE
```

---

### SHORT_MAX
Maximal value, which can be represented by short type

```mql5
SHORT_MAX
```

---

### SHORT_MIN
Minimal value, which can be represented by short type

```mql5
SHORT_MIN
```

---

### SIGNAL_BASE_AUTHOR_LOGIN
Author login

```mql5
SIGNAL_BASE_AUTHOR_LOGIN
```

---

### SIGNAL_BASE_BALANCE
Account balance

```mql5
SIGNAL_BASE_BALANCE
```

---

### SIGNAL_BASE_BROKER
Broker name (company)

```mql5
SIGNAL_BASE_BROKER
```

---

### SIGNAL_BASE_BROKER_SERVER
Broker server

```mql5
SIGNAL_BASE_BROKER_SERVER
```

---

### SIGNAL_BASE_CURRENCY
Signal base currency

```mql5
SIGNAL_BASE_CURRENCY
```

---

### SIGNAL_BASE_DATE_PUBLISHED
Publication date (date when it become available for subscription)

```mql5
SIGNAL_BASE_DATE_PUBLISHED
```

---

### SIGNAL_BASE_DATE_STARTED
Monitoring starting date

```mql5
SIGNAL_BASE_DATE_STARTED
```

---

### SIGNAL_BASE_EQUITY
Account equity

```mql5
SIGNAL_BASE_EQUITY
```

---

### SIGNAL_BASE_GAIN
Account gain

```mql5
SIGNAL_BASE_GAIN
```

---

### SIGNAL_BASE_ID
Signal ID

```mql5
SIGNAL_BASE_ID
```

---

### SIGNAL_BASE_LEVERAGE
Account leverage

```mql5
SIGNAL_BASE_LEVERAGE
```

---

### SIGNAL_BASE_MAX_DRAWDOWN
Account maximum drawdown

```mql5
SIGNAL_BASE_MAX_DRAWDOWN
```

---

### SIGNAL_BASE_NAME
Signal name

```mql5
SIGNAL_BASE_NAME
```

---

### SIGNAL_BASE_PIPS
Profit in pips

```mql5
SIGNAL_BASE_PIPS
```

---

### SIGNAL_BASE_PRICE
Signal subscription price

```mql5
SIGNAL_BASE_PRICE
```

---

### SIGNAL_BASE_RATING
Position in rating

```mql5
SIGNAL_BASE_RATING
```

---

### SIGNAL_BASE_ROI
Return on Investment (%)

```mql5
SIGNAL_BASE_ROI
```

---

### SIGNAL_BASE_SUBSCRIBERS
Number of subscribers

```mql5
SIGNAL_BASE_SUBSCRIBERS
```

---

### SIGNAL_BASE_TRADE_MODE
Account type (0-real, 1-demo, 2-contest)

```mql5
SIGNAL_BASE_TRADE_MODE
```

---

### SIGNAL_BASE_TRADES
Number of trades

```mql5
SIGNAL_BASE_TRADES
```

---

### SIGNAL_INFO_CONFIRMATIONS_DISABLED
The flag enables synchronization without confirmation dialog

```mql5
SIGNAL_INFO_CONFIRMATIONS_DISABLED
```

---

### SIGNAL_INFO_COPY_SLTP
Copy Stop Loss and Take Profit flag

```mql5
SIGNAL_INFO_COPY_SLTP
```

---

### SIGNAL_INFO_DEPOSIT_PERCENT
Deposit percent (%)

```mql5
SIGNAL_INFO_DEPOSIT_PERCENT
```

---

### SIGNAL_INFO_EQUITY_LIMIT
Equity limit

```mql5
SIGNAL_INFO_EQUITY_LIMIT
```

---

### SIGNAL_INFO_ID
Signal id, r/o

```mql5
SIGNAL_INFO_ID
```

---

### SIGNAL_INFO_NAME
Signal name, r/o

```mql5
SIGNAL_INFO_NAME
```

---

### SIGNAL_INFO_SLIPPAGE
Slippage (used when placing market orders in synchronization of positions and copying of trades)

```mql5
SIGNAL_INFO_SLIPPAGE
```

---

### SIGNAL_INFO_SUBSCRIPTION_ENABLED
"Copy trades by subscription" permission flag

```mql5
SIGNAL_INFO_SUBSCRIPTION_ENABLED
```

---

### SIGNAL_INFO_TERMS_AGREE
"Agree to terms of use of Signals service" flag, r/o

```mql5
SIGNAL_INFO_TERMS_AGREE
```

---

### SIGNAL_INFO_VOLUME_PERCENT
Maximum percent of deposit used (%), r/o

```mql5
SIGNAL_INFO_VOLUME_PERCENT
```

---

### SIGNAL_LINE
Signal line

```mql5
SIGNAL_LINE
```

---

### STAT_BALANCE_DD
Maximum balance drawdown in monetary terms. In the process of trading, a balance may have numerous drawdowns; here the largest value is taken

```mql5
STAT_BALANCE_DD
```

---

### STAT_BALANCE_DD_RELATIVE
Balance drawdown in monetary terms that was recorded at the moment of the maximum balance drawdown as a percentage (STAT_BALANCE_DDREL_PERCENT).

```mql5
STAT_BALANCE_DD_RELATIVE
```

---

### STAT_BALANCE_DDREL_PERCENT
Maximum balance drawdown as a percentage. In the process of trading, a balance may have numerous drawdowns, for each of which the relative drawdown value in percents is calculated. The greatest value is returned

```mql5
STAT_BALANCE_DDREL_PERCENT
```

---

### STAT_BALANCEDD_PERCENT
Balance drawdown as a percentage that was recorded at the moment of the maximum balance drawdown in monetary terms (STAT_BALANCE_DD).

```mql5
STAT_BALANCEDD_PERCENT
```

---

### STAT_BALANCEMIN
Minimum balance value

```mql5
STAT_BALANCEMIN
```

---

### STAT_CONLOSSMAX
Maximum loss in a series of losing trades. The value is less than or equal to zero

```mql5
STAT_CONLOSSMAX
```

---

### STAT_CONLOSSMAX_TRADES
The number of trades that have formed STAT_CONLOSSMAX (maximum loss in a series of losing trades)

```mql5
STAT_CONLOSSMAX_TRADES
```

---

### STAT_CONPROFITMAX
Maximum profit in a series of profitable trades. The value is greater than or equal to zero

```mql5
STAT_CONPROFITMAX
```

---

### STAT_CONPROFITMAX_TRADES
The number of trades that have formed STAT_CONPROFITMAX (maximum profit in a series of profitable trades)

```mql5
STAT_CONPROFITMAX_TRADES
```

---

### STAT_CUSTOM_ONTESTER
The value of the calculated custom optimization criterion returned by the OnTester() function

```mql5
STAT_CUSTOM_ONTESTER
```

---

### STAT_DEALS
The number of deals

```mql5
STAT_DEALS
```

---

### STAT_EQUITY_DD
Maximum equity drawdown in monetary terms. In the process of trading, numerous drawdowns may appear on the equity; here the largest value is taken

```mql5
STAT_EQUITY_DD
```

---

### STAT_EQUITY_DD_RELATIVE
Equity drawdown in monetary terms that was recorded at the moment of the maximum equity drawdown in percent (STAT_EQUITY_DDREL_PERCENT).

```mql5
STAT_EQUITY_DD_RELATIVE
```

---

### STAT_EQUITY_DDREL_PERCENT
Maximum equity drawdown as a percentage. In the process of trading, an equity may have numerous drawdowns, for each of which the relative drawdown value in percents is calculated. The greatest value is returned

```mql5
STAT_EQUITY_DDREL_PERCENT
```

---

### STAT_EQUITYDD_PERCENT
Drawdown in percent that was recorded at the moment of the maximum equity drawdown in monetary terms (STAT_EQUITY_DD).

```mql5
STAT_EQUITYDD_PERCENT
```

---

### STAT_EQUITYMIN
Minimum equity value

```mql5
STAT_EQUITYMIN
```

---

### STAT_EXPECTED_PAYOFF
Expected payoff

```mql5
STAT_EXPECTED_PAYOFF
```

---

### STAT_GROSS_LOSS
Total loss, the sum of all negative trades. The value is less than or equal to zero

```mql5
STAT_GROSS_LOSS
```

---

### STAT_GROSS_PROFIT
Total profit, the sum of all profitable (positive) trades. The value is greater than or equal to zero

```mql5
STAT_GROSS_PROFIT
```

---

### STAT_INITIAL_DEPOSIT
The value of the initial deposit

```mql5
STAT_INITIAL_DEPOSIT
```

---

### STAT_LONG_TRADES
Long trades

```mql5
STAT_LONG_TRADES
```

---

### STAT_LOSS_TRADES
Losing trades

```mql5
STAT_LOSS_TRADES
```

---

### STAT_LOSSTRADES_AVGCON
Average length of a losing series of trades

```mql5
STAT_LOSSTRADES_AVGCON
```

---

### STAT_MAX_CONLOSS_TRADES
The number of trades in the longest series of losing trades STAT_MAX_CONLOSSES

```mql5
STAT_MAX_CONLOSS_TRADES
```

---

### STAT_MAX_CONLOSSES
The total loss of the longest series of losing trades

```mql5
STAT_MAX_CONLOSSES
```

---

### STAT_MAX_CONPROFIT_TRADES
The number of trades in the longest series of profitable trades STAT_MAX_CONWINS

```mql5
STAT_MAX_CONPROFIT_TRADES
```

---

### STAT_MAX_CONWINS
The total profit of the longest series of profitable trades

```mql5
STAT_MAX_CONWINS
```

---

### STAT_MAX_LOSSTRADE
Maximum loss – the lowest value of all losing trades. The value is less than or equal to zero

```mql5
STAT_MAX_LOSSTRADE
```

---

### STAT_MAX_PROFITTRADE
Maximum profit – the largest value of all profitable trades. The value is greater than or equal to zero

```mql5
STAT_MAX_PROFITTRADE
```

---

### STAT_MIN_MARGINLEVEL
Minimum value of the margin level

```mql5
STAT_MIN_MARGINLEVEL
```

---

### STAT_PROFIT
Net profit after testing, the sum of STAT_GROSS_PROFIT and STAT_GROSS_LOSS (STAT_GROSS_LOSS is always less than or equal to zero)

```mql5
STAT_PROFIT
```

---

### STAT_PROFIT_FACTOR
Profit factor, equal to  the ratio of STAT_GROSS_PROFIT/STAT_GROSS_LOSS. If STAT_GROSS_LOSS=0, the profit factor is equal to DBL_MAX

```mql5
STAT_PROFIT_FACTOR
```

---

### STAT_PROFIT_LONGTRADES
Profitable long trades

```mql5
STAT_PROFIT_LONGTRADES
```

---

### STAT_PROFIT_SHORTTRADES
Profitable short trades

```mql5
STAT_PROFIT_SHORTTRADES
```

---

### STAT_PROFIT_TRADES
Profitable trades

```mql5
STAT_PROFIT_TRADES
```

---

### STAT_PROFITTRADES_AVGCON
Average length of a profitable series of trades

```mql5
STAT_PROFITTRADES_AVGCON
```

---

### STAT_RECOVERY_FACTOR
Recovery factor, equal to the ratio of STAT_PROFIT/STAT_BALANCE_DD

```mql5
STAT_RECOVERY_FACTOR
```

---

### STAT_SHARPE_RATIO
Sharpe ratio

```mql5
STAT_SHARPE_RATIO
```

---

### STAT_SHORT_TRADES
Short trades

```mql5
STAT_SHORT_TRADES
```

---

### STAT_TRADES
The number of trades

```mql5
STAT_TRADES
```

---

### STAT_WITHDRAWAL
Money withdrawn from an account

```mql5
STAT_WITHDRAWAL
```

---

### STO_CLOSECLOSE
Calculation is based on Close/Close prices

```mql5
STO_CLOSECLOSE
```

---

### STO_LOWHIGH
Calculation is based on Low/High prices

```mql5
STO_LOWHIGH
```

---

### STYLE_DASH
Broken line

```mql5
STYLE_DASH
```

---

### STYLE_DASHDOT
Dash-dot line

```mql5
STYLE_DASHDOT
```

---

### STYLE_DASHDOTDOT
Dash - two points

```mql5
STYLE_DASHDOTDOT
```

---

### STYLE_DOT
Dotted line

```mql5
STYLE_DOT
```

---

### STYLE_SOLID
Solid line

```mql5
STYLE_SOLID
```

---

### SUNDAY
Sunday

```mql5
SUNDAY
```

---

### SYMBOL_ASK
Ask - best buy offer

```mql5
SYMBOL_ASK
```

---

### SYMBOL_ASKHIGH
Maximal Ask of the day

```mql5
SYMBOL_ASKHIGH
```

---

### SYMBOL_ASKLOW
Minimal Ask of the day

```mql5
SYMBOL_ASKLOW
```

---

### SYMBOL_BANK
Feeder of the current quote

```mql5
SYMBOL_BANK
```

---

### SYMBOL_BASIS
The underlying asset of a derivative

```mql5
SYMBOL_BASIS
```

---

### SYMBOL_BID
Bid - best sell offer

```mql5
SYMBOL_BID
```

---

### SYMBOL_BIDHIGH
Maximal Bid of the day

```mql5
SYMBOL_BIDHIGH
```

---

### SYMBOL_BIDLOW
Minimal Bid of the day

```mql5
SYMBOL_BIDLOW
```

---

### SYMBOL_CALC_MODE_CFD
CFD mode - calculation of margin and profit for CFD

```mql5
SYMBOL_CALC_MODE_CFD
```

---

### SYMBOL_CALC_MODE_CFDINDEX
CFD index mode - calculation of margin and profit for CFD by indexes

```mql5
SYMBOL_CALC_MODE_CFDINDEX
```

---

### SYMBOL_CALC_MODE_CFDLEVERAGE
CFD Leverage mode - calculation of margin and profit for CFD at leverage trading

```mql5
SYMBOL_CALC_MODE_CFDLEVERAGE
```

---

### SYMBOL_CALC_MODE_EXCH_FUTURES
Futures mode –  calculation of margin and profit for trading futures contracts on a stock exchange

```mql5
SYMBOL_CALC_MODE_EXCH_FUTURES
```

---

### SYMBOL_CALC_MODE_EXCH_FUTURES_FORTS
FORTS Futures mode –  calculation of margin and profit for trading futures contracts on FORTS.

```mql5
SYMBOL_CALC_MODE_EXCH_FUTURES_FORTS
```

---

### SYMBOL_CALC_MODE_EXCH_STOCKS
Exchange mode – calculation of margin and profit for trading securities on a stock exchange

```mql5
SYMBOL_CALC_MODE_EXCH_STOCKS
```

---

### SYMBOL_CALC_MODE_FOREX
Forex mode - calculation of profit and margin for Forex

```mql5
SYMBOL_CALC_MODE_FOREX
```

---

### SYMBOL_CALC_MODE_FUTURES
Futures mode - calculation of margin and profit for futures

```mql5
SYMBOL_CALC_MODE_FUTURES
```

---

### SYMBOL_CALC_MODE_SERV_COLLATERAL
Collateral mode - a symbol is used as a non-tradable asset on a trading account.

```mql5
SYMBOL_CALC_MODE_SERV_COLLATERAL
```

---

### SYMBOL_CURRENCY_BASE
Basic currency of a symbol

```mql5
SYMBOL_CURRENCY_BASE
```

---

### SYMBOL_CURRENCY_MARGIN
Margin currency

```mql5
SYMBOL_CURRENCY_MARGIN
```

---

### SYMBOL_CURRENCY_PROFIT
Profit currency

```mql5
SYMBOL_CURRENCY_PROFIT
```

---

### SYMBOL_DESCRIPTION
Symbol description

```mql5
SYMBOL_DESCRIPTION
```

---

### SYMBOL_DIGITS
Digits after a decimal point

```mql5
SYMBOL_DIGITS
```

---

### SYMBOL_EXPIRATION_DAY
The order is valid till the end of the day

```mql5
SYMBOL_EXPIRATION_DAY
```

---

### SYMBOL_EXPIRATION_GTC
The order is valid during the unlimited time period, until it is explicitly canceled

```mql5
SYMBOL_EXPIRATION_GTC
```

---

### SYMBOL_EXPIRATION_MODE
Flags of allowed order expiration modes

```mql5
SYMBOL_EXPIRATION_MODE
```

---

### SYMBOL_EXPIRATION_SPECIFIED
The expiration time is specified in the order

```mql5
SYMBOL_EXPIRATION_SPECIFIED
```

---

### SYMBOL_EXPIRATION_SPECIFIED_DAY
The expiration date is specified in the order

```mql5
SYMBOL_EXPIRATION_SPECIFIED_DAY
```

---

### SYMBOL_EXPIRATION_TIME
Date of the symbol trade end (usually used for futures)

```mql5
SYMBOL_EXPIRATION_TIME
```

---

### SYMBOL_FILLING_FOK
This policy means that a deal can be executed only with the specified volume. If the necessary amount of a financial instrument is currently unavailable in the market, the order will not be executed. The required volume can be filled using several offers available on the market at the moment.

```mql5
SYMBOL_FILLING_FOK
```

---

### SYMBOL_FILLING_IOC
In this case a trader agrees to execute a deal with the volume maximally available in the market within that indicated in the order. In case the order cannot be filled completely, the available volume of the order will be filled, and the remaining volume will be canceled. The possibility of using IOC orders is determined at the trade server.

```mql5
SYMBOL_FILLING_IOC
```

---

### SYMBOL_FILLING_MODE
Flags of allowed order filling modes

```mql5
SYMBOL_FILLING_MODE
```

---

### SYMBOL_ISIN
The name of a symbol in the ISIN system (International Securities Identification Number). The International Securities Identification Number is a 12-digit alphanumeric code that uniquely identifies a security. The presence of this symbol property is determined on the side of a trade server.

```mql5
SYMBOL_ISIN
```

---

### SYMBOL_LAST
Price of the last deal

```mql5
SYMBOL_LAST
```

---

### SYMBOL_LASTHIGH
Maximal Last of the day

```mql5
SYMBOL_LASTHIGH
```

---

### SYMBOL_LASTLOW
Minimal Last of the day

```mql5
SYMBOL_LASTLOW
```

---

### SYMBOL_MARGIN_INITIAL
Initial margin means the amount in the margin currency required for opening a position with the volume of one lot. It is used for checking a client's assets when he or she enters the market.

```mql5
SYMBOL_MARGIN_INITIAL
```

---

### SYMBOL_MARGIN_MAINTENANCE
The maintenance margin. If it is set, it sets the margin amount in the margin currency of the symbol, charged from one lot. It is used for checking a client's assets when his/her account state changes. If the maintenance margin is equal to 0, the initial margin is used.

```mql5
SYMBOL_MARGIN_MAINTENANCE
```

---

### SYMBOL_OPTION_MODE
Option type

```mql5
SYMBOL_OPTION_MODE
```

---

### SYMBOL_OPTION_MODE_EUROPEAN
European option may only be exercised on a specified date (expiration, execution date, delivery date)

```mql5
SYMBOL_OPTION_MODE_EUROPEAN
```

---

### SYMBOL_OPTION_MODE_AMERICAN
American option may be exercised on any trading day on or before expiry. The period within which a buyer can exercise the option is specified for it

```mql5
SYMBOL_OPTION_MODE_AMERICAN
```

---

### SYMBOL_OPTION_RIGHT
Option right (Call/Put)

```mql5
SYMBOL_OPTION_RIGHT
```

---

### SYMBOL_OPTION_RIGHT_CALL
A call option gives you the right to buy an asset at a specified price

```mql5
SYMBOL_OPTION_RIGHT_CALL
```

---

### SYMBOL_OPTION_RIGHT_PUT
A put option gives you the right to sell an asset at a specified price

```mql5
SYMBOL_OPTION_RIGHT_PUT
```

---

### SYMBOL_OPTION_STRIKE
The strike price of an option. The price at which an option buyer can buy (in a Call option) or sell (in a Put option) the underlying asset, and the option seller is obliged to sell or buy the appropriate amount of the underlying asset.

```mql5
SYMBOL_OPTION_STRIKE
```

---

### SYMBOL_ORDER_LIMIT
Limit orders are allowed (Buy Limit and Sell Limit)

```mql5
SYMBOL_ORDER_LIMIT
```

---

### SYMBOL_ORDER_MARKET
Market orders are allowed (Buy and Sell)

```mql5
SYMBOL_ORDER_MARKET
```

---

### SYMBOL_ORDER_MODE
Flags of allowed order types

```mql5
SYMBOL_ORDER_MODE
```

---

### SYMBOL_ORDER_SL
Stop Loss is allowed

```mql5
SYMBOL_ORDER_SL
```

---

### SYMBOL_ORDER_STOP
Stop orders are allowed (Buy Stop and Sell Stop)

```mql5
SYMBOL_ORDER_STOP
```

---

### SYMBOL_ORDER_STOP_LIMIT
Stop-limit orders are allowed (Buy Stop Limit and Sell Stop Limit)

```mql5
SYMBOL_ORDER_STOP_LIMIT
```

---

### SYMBOL_ORDER_TP
Take Profit is allowed

```mql5
SYMBOL_ORDER_TP
```

---

### SYMBOL_PATH
Path in the symbol tree

```mql5
SYMBOL_PATH
```

---

### SYMBOL_POINT
Symbol point value

```mql5
SYMBOL_POINT
```

---

### SYMBOL_SELECT
Symbol is selected in Market Watch

```mql5
SYMBOL_SELECT
```

---

### SYMBOL_SESSION_AW
Average weighted price of the current session

```mql5
SYMBOL_SESSION_AW
```

---

### SYMBOL_SESSION_BUY_ORDERS
Number of Buy orders at the moment

```mql5
SYMBOL_SESSION_BUY_ORDERS
```

---

### SYMBOL_SESSION_BUY_ORDERS_VOLUME
Current volume of Buy orders

```mql5
SYMBOL_SESSION_BUY_ORDERS_VOLUME
```

---

### SYMBOL_SESSION_CLOSE
Close price of the current session

```mql5
SYMBOL_SESSION_CLOSE
```

---

### SYMBOL_SESSION_DEALS
Number of deals in the current session

```mql5
SYMBOL_SESSION_DEALS
```

---

### SYMBOL_SESSION_INTEREST
Summary open interest

```mql5
SYMBOL_SESSION_INTEREST
```

---

### SYMBOL_SESSION_OPEN
Open price of the current session

```mql5
SYMBOL_SESSION_OPEN
```

---

### SYMBOL_SESSION_PRICE_LIMIT_MAX
Maximal price of the current session

```mql5
SYMBOL_SESSION_PRICE_LIMIT_MAX
```

---

### SYMBOL_SESSION_PRICE_LIMIT_MIN
Minimal price of the current session

```mql5
SYMBOL_SESSION_PRICE_LIMIT_MIN
```

---

### SYMBOL_SESSION_PRICE_SETTLEMENT
Settlement price of the current session

```mql5
SYMBOL_SESSION_PRICE_SETTLEMENT
```

---

### SYMBOL_SESSION_SELL_ORDERS
Number of Sell orders at the moment

```mql5
SYMBOL_SESSION_SELL_ORDERS
```

---

### SYMBOL_SESSION_SELL_ORDERS_VOLUME
Current volume of Sell orders

```mql5
SYMBOL_SESSION_SELL_ORDERS_VOLUME
```

---

### SYMBOL_SESSION_TURNOVER
Summary turnover of the current session

```mql5
SYMBOL_SESSION_TURNOVER
```

---

### SYMBOL_SESSION_VOLUME
Summary volume of current session deals

```mql5
SYMBOL_SESSION_VOLUME
```

---

### SYMBOL_SPREAD
Spread value in points

```mql5
SYMBOL_SPREAD
```

---

### SYMBOL_SPREAD_FLOAT
Indication of a floating spread

```mql5
SYMBOL_SPREAD_FLOAT
```

---

### SYMBOL_START_TIME
Date of the symbol trade beginning (usually used for futures)

```mql5
SYMBOL_START_TIME
```

---

### SYMBOL_SWAP_LONG
Long swap value

```mql5
SYMBOL_SWAP_LONG
```

---

### SYMBOL_SWAP_MODE
Swap calculation model

```mql5
SYMBOL_SWAP_MODE
```

---

### SYMBOL_SWAP_MODE_CURRENCY_DEPOSIT
Swaps are charged in money, in client deposit currency

```mql5
SYMBOL_SWAP_MODE_CURRENCY_DEPOSIT
```

---

### SYMBOL_SWAP_MODE_CURRENCY_MARGIN
Swaps are charged in money in margin currency of the symbol

```mql5
SYMBOL_SWAP_MODE_CURRENCY_MARGIN
```

---

### SYMBOL_SWAP_MODE_CURRENCY_SYMBOL
Swaps are charged in money in base currency of the symbol

```mql5
SYMBOL_SWAP_MODE_CURRENCY_SYMBOL
```

---

### SYMBOL_SWAP_MODE_DISABLED
Swaps disabled (no swaps)

```mql5
SYMBOL_SWAP_MODE_DISABLED
```

---

### SYMBOL_SWAP_MODE_INTEREST_CURRENT
Swaps are charged as the specified annual interest from the instrument price at calculation of swap (standard bank year is 360 days)

```mql5
SYMBOL_SWAP_MODE_INTEREST_CURRENT
```

---

### SYMBOL_SWAP_MODE_INTEREST_OPEN
Swaps are charged as the specified annual interest from the open price of position (standard bank year is 360 days)

```mql5
SYMBOL_SWAP_MODE_INTEREST_OPEN
```

---

### SYMBOL_SWAP_MODE_POINTS
Swaps are charged in points

```mql5
SYMBOL_SWAP_MODE_POINTS
```

---

### SYMBOL_SWAP_MODE_REOPEN_BID
Swaps are charged by reopening positions. At the end of a trading day the position is closed. Next day it is reopened by the current Bid price +/- specified number of points (parameters SYMBOL_SWAP_LONG and SYMBOL_SWAP_SHORT)

```mql5
SYMBOL_SWAP_MODE_REOPEN_BID
```

---

### SYMBOL_SWAP_MODE_REOPEN_CURRENT
Swaps are charged by reopening positions. At the end of a trading day the position is closed. Next day it is reopened by the close price +/- specified number of points (parameters SYMBOL_SWAP_LONG and SYMBOL_SWAP_SHORT)

```mql5
SYMBOL_SWAP_MODE_REOPEN_CURRENT
```

---

### SYMBOL_SWAP_ROLLOVER3DAYS
Day of week to charge 3 days swap rollover

```mql5
SYMBOL_SWAP_ROLLOVER3DAYS
```

---

### SYMBOL_SWAP_SHORT
Short swap value

```mql5
SYMBOL_SWAP_SHORT
```

---

### SYMBOL_TICKS_BOOKDEPTH
Maximal number of requests shown in Depth of Market. For symbols that have no queue of requests, the value is equal to zero.

```mql5
SYMBOL_TICKS_BOOKDEPTH
```

---

### SYMBOL_TIME
Time of the last quote

```mql5
SYMBOL_TIME
```

---

### SYMBOL_TRADE_CALC_MODE
Contract price calculation mode

```mql5
SYMBOL_TRADE_CALC_MODE
```

---

### SYMBOL_TRADE_CONTRACT_SIZE
Trade contract size

```mql5
SYMBOL_TRADE_CONTRACT_SIZE
```

---

### SYMBOL_TRADE_EXECUTION_EXCHANGE
Exchange execution

```mql5
SYMBOL_TRADE_EXECUTION_EXCHANGE
```

---

### SYMBOL_TRADE_EXECUTION_INSTANT
Instant execution

```mql5
SYMBOL_TRADE_EXECUTION_INSTANT
```

---

### SYMBOL_TRADE_EXECUTION_MARKET
Market execution

```mql5
SYMBOL_TRADE_EXECUTION_MARKET
```

---

### SYMBOL_TRADE_EXECUTION_REQUEST
Execution by request

```mql5
SYMBOL_TRADE_EXECUTION_REQUEST
```

---

### SYMBOL_TRADE_EXEMODE
Deal execution mode

```mql5
SYMBOL_TRADE_EXEMODE
```

---

### SYMBOL_TRADE_FREEZE_LEVEL
Distance to freeze trade operations in points

```mql5
SYMBOL_TRADE_FREEZE_LEVEL
```

---

### SYMBOL_TRADE_MODE
Order execution type

```mql5
SYMBOL_TRADE_MODE
```

---

### SYMBOL_TRADE_MODE_CLOSEONLY
Allowed only position close operations

```mql5
SYMBOL_TRADE_MODE_CLOSEONLY
```

---

### SYMBOL_TRADE_MODE_DISABLED
Trade is disabled for the symbol

```mql5
SYMBOL_TRADE_MODE_DISABLED
```

---

### SYMBOL_TRADE_MODE_FULL
No trade restrictions

```mql5
SYMBOL_TRADE_MODE_FULL
```

---

### SYMBOL_TRADE_MODE_LONGONLY
Allowed only long positions

```mql5
SYMBOL_TRADE_MODE_LONGONLY
```

---

### SYMBOL_TRADE_MODE_SHORTONLY
Allowed only short positions

```mql5
SYMBOL_TRADE_MODE_SHORTONLY
```

---

### SYMBOL_TRADE_STOPS_LEVEL
Minimal indention in points from the current close price to place Stop orders

```mql5
SYMBOL_TRADE_STOPS_LEVEL
```

---

### SYMBOL_TRADE_TICK_SIZE
Minimal price change

```mql5
SYMBOL_TRADE_TICK_SIZE
```

---

### SYMBOL_TRADE_TICK_VALUE
Value of SYMBOL_TRADE_TICK_VALUE_PROFIT

```mql5
SYMBOL_TRADE_TICK_VALUE
```

---

### SYMBOL_TRADE_TICK_VALUE_LOSS
Calculated tick price for a losing position

```mql5
SYMBOL_TRADE_TICK_VALUE_LOSS
```

---

### SYMBOL_TRADE_TICK_VALUE_PROFIT
Calculated tick price for a profitable position

```mql5
SYMBOL_TRADE_TICK_VALUE_PROFIT
```

---

### SYMBOL_VOLUME
Volume of the last deal

```mql5
SYMBOL_VOLUME
```

---

### SYMBOL_VOLUME_LIMIT
Maximum allowed aggregate volume of an open position and pending orders in one direction (buy or sell) for the symbol. For example, with the limitation of 5 lots, you can have an open buy position with the volume of 5 lots and place a pending order Sell Limit with the volume of 5 lots. But in this case you cannot place a Buy Limit pending order (since the total volume in one direction will exceed the limitation) or place Sell Limit with the volume more than 5 lots.

```mql5
SYMBOL_VOLUME_LIMIT
```

---

### SYMBOL_VOLUME_MAX
Maximal volume for a deal

```mql5
SYMBOL_VOLUME_MAX
```

---

### SYMBOL_VOLUME_MIN
Minimal volume for a deal

```mql5
SYMBOL_VOLUME_MIN
```

---

### SYMBOL_VOLUME_STEP
Minimal volume change step for deal execution

```mql5
SYMBOL_VOLUME_STEP
```

---

### SYMBOL_VOLUMEHIGH
Maximal day volume

```mql5
SYMBOL_VOLUMEHIGH
```

---

### SYMBOL_VOLUMELOW
Minimal day volume

```mql5
SYMBOL_VOLUMELOW
```

---

### TENKANSEN_LINE
Tenkan-sen line

```mql5
TENKANSEN_LINE
```

---

### TERMINAL_BUILD
The client terminal build number

```mql5
TERMINAL_BUILD
```

---

### TERMINAL_CODEPAGE
Number of the code page of the language installed in the client terminal

```mql5
TERMINAL_CODEPAGE
```

---

### TERMINAL_COMMONDATA_PATH
Common path for all of the terminals installed on a computer

```mql5
TERMINAL_COMMONDATA_PATH
```

---

### TERMINAL_COMMUNITY_ACCOUNT
The flag indicates the presence of MQL5.community authorization data in the terminal

```mql5
TERMINAL_COMMUNITY_ACCOUNT
```

---

### TERMINAL_COMMUNITY_BALANCE
Balance in MQL5.community

```mql5
TERMINAL_COMMUNITY_BALANCE
```

---

### TERMINAL_COMMUNITY_CONNECTION
Connection to MQL5.community

```mql5
TERMINAL_COMMUNITY_CONNECTION
```

---

### TERMINAL_COMPANY
Company name

```mql5
TERMINAL_COMPANY
```

---

### TERMINAL_CONNECTED
Connection to a trade server

```mql5
TERMINAL_CONNECTED
```

---

### TERMINAL_CPU_CORES
The number of CPU cores in the system

```mql5
TERMINAL_CPU_CORES
```

---

### TERMINAL_DATA_PATH
Folder in which terminal data are stored

```mql5
TERMINAL_DATA_PATH
```

---

### TERMINAL_DISK_SPACE
Free disk space for the MQL5\Files folder of the terminal (agent), MB

```mql5
TERMINAL_DISK_SPACE
```

---

### TERMINAL_DLLS_ALLOWED
Permission to use DLL

```mql5
TERMINAL_DLLS_ALLOWED
```

---

### TERMINAL_EMAIL_ENABLED
Permission to send e-mails using SMTP-server and login, specified in the terminal settings

```mql5
TERMINAL_EMAIL_ENABLED
```

---

### TERMINAL_FTP_ENABLED
Permission to send reports using FTP-server and login, specified in the terminal settings

```mql5
TERMINAL_FTP_ENABLED
```

---

### TERMINAL_LANGUAGE
Language of the terminal

```mql5
TERMINAL_LANGUAGE
```

---

### TERMINAL_MAXBARS
The maximal bars count on the chart

```mql5
TERMINAL_MAXBARS
```

---

### TERMINAL_MEMORY_AVAILABLE
Free memory of the terminal (agent) process, MB

```mql5
TERMINAL_MEMORY_AVAILABLE
```

---

### TERMINAL_MEMORY_PHYSICAL
Physical memory in the system, MB

```mql5
TERMINAL_MEMORY_PHYSICAL
```

---

### TERMINAL_MEMORY_TOTAL
Memory available to the process of the terminal (agent), MB

```mql5
TERMINAL_MEMORY_TOTAL
```

---

### TERMINAL_MEMORY_USED
Memory used by the terminal (agent), MB

```mql5
TERMINAL_MEMORY_USED
```

---

### TERMINAL_MQID
The flag indicates the presence of MetaQuotes ID data for Push notifications

```mql5
TERMINAL_MQID
```

---

### TERMINAL_NAME
Terminal name

```mql5
TERMINAL_NAME
```

---

### TERMINAL_NOTIFICATIONS_ENABLED
Permission to send notifications to smartphone

```mql5
TERMINAL_NOTIFICATIONS_ENABLED
```

---

### TERMINAL_OPENCL_SUPPORT
The version of the supported OpenCL in the format of 0x00010002 = 1.2.  "0" means that OpenCL is not supported

```mql5
TERMINAL_OPENCL_SUPPORT
```

---

### TERMINAL_PATH
Folder from which the terminal is started

```mql5
TERMINAL_PATH
```

---

### TERMINAL_PING_LAST
The last known value of a ping to a trade server in microseconds. One second comprises of one million microseconds

```mql5
TERMINAL_PING_LAST
```

---

### TERMINAL_SCREEN_DPI
The resolution of information display on the screen is measured as number of Dots in a line per Inch (DPI).

```mql5
TERMINAL_SCREEN_DPI
```

---

### TERMINAL_TRADE_ALLOWED
Permission to trade

```mql5
TERMINAL_TRADE_ALLOWED
```

---

### TERMINAL_X64
Indication of the "64-bit terminal"

```mql5
TERMINAL_X64
```

---

### THURSDAY
Thursday

```mql5
THURSDAY
```

---

### TRADE_ACTION_DEAL
Place a trade order for an immediate execution with the specified parameters (market order)

```mql5
TRADE_ACTION_DEAL
```

---

### TRADE_ACTION_MODIFY
Modify the parameters of the order placed previously

```mql5
TRADE_ACTION_MODIFY
```

---

### TRADE_ACTION_PENDING
Place a trade order for the execution under specified conditions (pending order)

```mql5
TRADE_ACTION_PENDING
```

---

### TRADE_ACTION_REMOVE
Delete the pending order placed previously

```mql5
TRADE_ACTION_REMOVE
```

---

### TRADE_ACTION_SLTP
Modify Stop Loss and Take Profit values of an opened position

```mql5
TRADE_ACTION_SLTP
```

---

### TRADE_RETCODE_CANCEL
Request canceled by trader

```mql5
TRADE_RETCODE_CANCEL
```

---

### TRADE_RETCODE_CLIENT_DISABLES_AT
Autotrading disabled by client terminal

```mql5
TRADE_RETCODE_CLIENT_DISABLES_AT
```

---

### TRADE_RETCODE_CONNECTION
No connection with the trade server

```mql5
TRADE_RETCODE_CONNECTION
```

---

### TRADE_RETCODE_DONE
Request completed

```mql5
TRADE_RETCODE_DONE
```

---

### TRADE_RETCODE_DONE_PARTIAL
Only part of the request was completed

```mql5
TRADE_RETCODE_DONE_PARTIAL
```

---

### TRADE_RETCODE_ERROR
Request processing error

```mql5
TRADE_RETCODE_ERROR
```

---

### TRADE_RETCODE_FROZEN
Order or position frozen

```mql5
TRADE_RETCODE_FROZEN
```

---

### TRADE_RETCODE_INVALID
Invalid request

```mql5
TRADE_RETCODE_INVALID
```

---

### TRADE_RETCODE_INVALID_EXPIRATION
Invalid order expiration date in the request

```mql5
TRADE_RETCODE_INVALID_EXPIRATION
```

---

### TRADE_RETCODE_INVALID_FILL
Invalid order filling type

```mql5
TRADE_RETCODE_INVALID_FILL
```

---

### TRADE_RETCODE_INVALID_ORDER
Incorrect or prohibited order type

```mql5
TRADE_RETCODE_INVALID_ORDER
```

---

### TRADE_RETCODE_INVALID_PRICE
Invalid price in the request

```mql5
TRADE_RETCODE_INVALID_PRICE
```

---

### TRADE_RETCODE_INVALID_STOPS
Invalid stops in the request

```mql5
TRADE_RETCODE_INVALID_STOPS
```

---

### TRADE_RETCODE_INVALID_VOLUME
Invalid volume in the request

```mql5
TRADE_RETCODE_INVALID_VOLUME
```

---

### TRADE_RETCODE_LIMIT_ORDERS
The number of pending orders has reached the limit

```mql5
TRADE_RETCODE_LIMIT_ORDERS
```

---

### TRADE_RETCODE_LIMIT_VOLUME
The volume of orders and positions for the symbol has reached the limit

```mql5
TRADE_RETCODE_LIMIT_VOLUME
```

---

### TRADE_RETCODE_LOCKED
Request locked for processing

```mql5
TRADE_RETCODE_LOCKED
```

---

### TRADE_RETCODE_MARKET_CLOSED
Market is closed

```mql5
TRADE_RETCODE_MARKET_CLOSED
```

---

### TRADE_RETCODE_NO_CHANGES
No changes in request

```mql5
TRADE_RETCODE_NO_CHANGES
```

---

### TRADE_RETCODE_NO_MONEY
There is not enough money to complete the request

```mql5
TRADE_RETCODE_NO_MONEY
```

---

### TRADE_RETCODE_ONLY_REAL
Operation is allowed only for live accounts

```mql5
TRADE_RETCODE_ONLY_REAL
```

---

### TRADE_RETCODE_ORDER_CHANGED
Order state changed

```mql5
TRADE_RETCODE_ORDER_CHANGED
```

---

### TRADE_RETCODE_PLACED
Order placed

```mql5
TRADE_RETCODE_PLACED
```

---

### TRADE_RETCODE_POSITION_CLOSED
Position with the specified POSITION_IDENTIFIER has already been closed

```mql5
TRADE_RETCODE_POSITION_CLOSED
```

---

### TRADE_RETCODE_PRICE_CHANGED
Prices changed

```mql5
TRADE_RETCODE_PRICE_CHANGED
```

---

### TRADE_RETCODE_PRICE_OFF
There are no quotes to process the request

```mql5
TRADE_RETCODE_PRICE_OFF
```

---

### TRADE_RETCODE_REJECT
Request rejected

```mql5
TRADE_RETCODE_REJECT
```

---

### TRADE_RETCODE_REQUOTE
Requote

```mql5
TRADE_RETCODE_REQUOTE
```

---

### TRADE_RETCODE_SERVER_DISABLES_AT
Autotrading disabled by server

```mql5
TRADE_RETCODE_SERVER_DISABLES_AT
```

---

### TRADE_RETCODE_TIMEOUT
Request canceled by timeout

```mql5
TRADE_RETCODE_TIMEOUT
```

---

### TRADE_RETCODE_TOO_MANY_REQUESTS
Too frequent requests

```mql5
TRADE_RETCODE_TOO_MANY_REQUESTS
```

---

### TRADE_RETCODE_TRADE_DISABLED
Trade is disabled

```mql5
TRADE_RETCODE_TRADE_DISABLED
```

---

### TRADE_TRANSACTION_DEAL_ADD
Adding a deal to the history. The action is performed as a result of an order execution or performing operations with an account balance.

```mql5
TRADE_TRANSACTION_DEAL_ADD
```

---

### TRADE_TRANSACTION_DEAL_DELETE
Deleting a deal from the history. There may be cases when a previously executed deal is deleted from a server. For example, a deal has been deleted in an external trading system (exchange) where it was previously transferred by a broker.

```mql5
TRADE_TRANSACTION_DEAL_DELETE
```

---

### TRADE_TRANSACTION_DEAL_UPDATE
Updating a deal in the history. There may be cases when a previously executed deal is changed on a server. For example, a deal has been changed in an external trading system (exchange) where it was previously transferred by a broker.

```mql5
TRADE_TRANSACTION_DEAL_UPDATE
```

---

### TRADE_TRANSACTION_HISTORY_ADD
Adding an order to the history as a result of execution or cancellation.

```mql5
TRADE_TRANSACTION_HISTORY_ADD
```

---

### TRADE_TRANSACTION_HISTORY_DELETE
Deleting an order from the orders history. This type is provided for enhancing functionality on a trade server side.

```mql5
TRADE_TRANSACTION_HISTORY_DELETE
```

---

### TRADE_TRANSACTION_HISTORY_UPDATE
Changing an order located in the orders history. This type is provided for enhancing functionality on a trade server side.

```mql5
TRADE_TRANSACTION_HISTORY_UPDATE
```

---

### TRADE_TRANSACTION_ORDER_ADD
Adding a new open order.

```mql5
TRADE_TRANSACTION_ORDER_ADD
```

---

### TRADE_TRANSACTION_ORDER_DELETE
Removing an order from the list of the open ones. An order can be deleted from the open ones as a result of setting an appropriate request or execution (filling) and moving to the history.

```mql5
TRADE_TRANSACTION_ORDER_DELETE
```

---

### TRADE_TRANSACTION_ORDER_UPDATE
Updating an open order. The updates include not only evident changes from the client terminal or a trade server sides but also changes of an order state when setting it (for example, transition from ORDER_STATE_STARTED to ORDER_STATE_PLACED or from ORDER_STATE_PLACED to ORDER_STATE_PARTIAL, etc.).

```mql5
TRADE_TRANSACTION_ORDER_UPDATE
```

---

### TRADE_TRANSACTION_POSITION
Changing a position not related to a deal execution. This type of transaction shows that a position has been changed on a trade server side. Position volume, open price, Stop Loss and Take Profit levels can be changed. Data on changes are submitted in MqlTradeTransaction structure via OnTradeTransaction handler. Position change (adding, changing or closing), as a result of a deal execution, does not lead to the occurrence of TRADE_TRANSACTION_POSITION transaction.

```mql5
TRADE_TRANSACTION_POSITION
```

---

### TRADE_TRANSACTION_REQUEST
Notification of the fact that a trade request has been processed by a server and processing result has been received. Only type field (trade transaction type) must be analyzed for such transactions in MqlTradeTransaction structure. The second and third parameters of OnTradeTransaction (request and result) must be analyzed for additional data.

```mql5
TRADE_TRANSACTION_REQUEST
```

---

### TUESDAY
Tuesday

```mql5
TUESDAY
```

---

### TYPE_BOOL
bool

```mql5
TYPE_BOOL
```

---

### TYPE_CHAR
char

```mql5
TYPE_CHAR
```

---

### TYPE_COLOR
color

```mql5
TYPE_COLOR
```

---

### TYPE_DATETIME
datetime

```mql5
TYPE_DATETIME
```

---

### TYPE_DOUBLE
double

```mql5
TYPE_DOUBLE
```

---

### TYPE_FLOAT
float

```mql5
TYPE_FLOAT
```

---

### TYPE_INT
int

```mql5
TYPE_INT
```

---

### TYPE_LONG
long

```mql5
TYPE_LONG
```

---

### TYPE_SHORT
short

```mql5
TYPE_SHORT
```

---

### TYPE_STRING
string

```mql5
TYPE_STRING
```

---

### TYPE_UCHAR
uchar

```mql5
TYPE_UCHAR
```

---

### TYPE_UINT
uint

```mql5
TYPE_UINT
```

---

### TYPE_ULONG
ulong

```mql5
TYPE_ULONG
```

---

### TYPE_USHORT
ushort

```mql5
TYPE_USHORT
```

---

### UCHAR_MAX
Maximal value, which can be represented by uchar type

```mql5
UCHAR_MAX
```

---

### UINT_MAX
Maximal value, which can be represented by uint type

```mql5
UINT_MAX
```

---

### ULONG_MAX
Maximal value, which can be represented by ulong type

```mql5
ULONG_MAX
```

---

### UPPER_BAND
Upper limit

```mql5
UPPER_BAND
```

---

### UPPER_HISTOGRAM
Upper histogram

```mql5
UPPER_HISTOGRAM
```

---

### UPPER_LINE
Upper line

```mql5
UPPER_LINE
```

---

### USHORT_MAX
Maximal value, which can be represented by ushort type

```mql5
USHORT_MAX
```

---

### VOLUME_REAL
Trade volume

```mql5
VOLUME_REAL
```

---

### VOLUME_TICK
Tick volume

```mql5
VOLUME_TICK
```

---

### WEDNESDAY
Wednesday

```mql5
WEDNESDAY
```

---

### WHOLE_ARRAY
Means the number of items remaining until the end of the array, i.e., the entire array will be processed

```mql5
WHOLE_ARRAY
```

---

### WRONG_VALUE
The constant can be implicitly cast to any enumeration type

```mql5
WRONG_VALUE
```

---

### class
class

```mql5
class
```

---

### union
Union is a special data type consisting of several variables sharing the same memory area.

```mql5
union
```

---

### char
The char type takes 1 byte of memory (8 bits) and allows expressing in the binary notation 2^8=256 values. The char type can contain both positive and negative values. The range of values is from -128 to 127.

```mql5
char
```

---

### uchar
The uchar integer type also occupies 1 byte of memory, as well as the char type, but unlike it uchar is intended only for positive values. The minimum value is zero, the maximum value is 255. The first letter u in the name of the uchar type is the abbreviation for unsigned.

```mql5
uchar
```

---

### short
The size of the short type is 2 bytes (16 bits) and, accordingly, it allows expressing the range of values equal to 2 to the power 16: 2^16 = 65 536.Since the short type is a signed one, and contains both positive and negative values, the range of values is between -32 768 and 32 767.

```mql5
short
```

---

### ushort
The unsigned short type is the type ushort, which also has a size of 2 bytes. The minimum value is 0, the maximum value is 65 535.

```mql5
ushort
```

---

### int
The size of the int type is 4 bytes (32 bits). The minimal value is -2 147 483 648, the maximal one is 2 147 483 647.

```mql5
int
```

---

### uint
The unsigned integer type is uint. It takes 4 bytes of memory and allows expressing integers from 0 to 4 294 967 295.

```mql5
uint
```

---

### long
The size of the long type is 8 bytes (64 bits). The minimum value is -9 223 372 036 854 775 808, the maximum value is 9 223 372 036 854 775 807.

```mql5
long
```

---

### ulong
The ulong type also occupies 8 bytes and can store values from 0 to 18 446 744 073 709 551 615.

```mql5
ulong
```

---

### datetime
The datetime type is intended for storing the date and time as the number of seconds elapsed since January 01, 1970. This type occupies 8 bytes of memory.

```mql5
datetime
```

---

### color
The color type is intended for storing information about color and occupies 4 bytes in memory. The first byte is ignored, the remaining 3 bytes contain the RGB-components.

```mql5
color
```

---

### bool
The bool type is intended to store the logical values of true or false, numeric representation of them is 1 or 0, respectively.

```mql5
bool
```

---

### enum
Data of the enum type belong to a certain limited set of data.

```mql5
enum
```

---

### double
Floating point data type. The name double means that these numbers are twice as accurate as float numbers.

```mql5
double
```

---

### float
The float type is the smallest floating point type in the range +/- 3.4E-38 to 3.4E+38. It occupies 4 bytes (32 bits) in memory

```mql5
float
```

---

### string
The string type is used for storing text strings. A text string is a sequence of characters in the Unicode format with the final zero at the end of it.

```mql5
string
```

---

### struct
A structure is a set of elements of any type (except for the void type). Thus, the structure combines logically related data of different types.

```mql5
struct
```

---

### void
Syntactically the void type is a fundamental type along with types of char, uchar, bool, short, ushort, int, uint, color, long, ulong, datetime, float, double and string. This type is used either to indicate that the function does not return any value, or as a function parameter it denotes the absence of parameters.

```mql5
void
```

---

### const
The const specifier declares a variable as a constant, and does not allow to change this variable during runtime.

```mql5
const
```

---

### private
allows access to variables and class methods only from methods of the same class.

```mql5
private
```

---

### virtual
applies only to class methods (but not to methods of structures) and tells the compiler that this method should be placed in the table of virtual functions of the class.

```mql5
virtual
```

---

### protected
allows access from methods of this class, as well as from methods of publicly inherited classes. Other access is impossible

```mql5
protected
```

---

### override
The 'override' modifier means that the declared function must override the method of a parent class.

```mql5
override
```

---

### public
allows unrestricted access to the variable or class method

```mql5
public
```

---

### typedef
The typedef keyword in C++ allows creating user-defined data types. To do this, simply specify a new data type name for an already existing data type.

```mql5
typedef
```

---

### typename
Keyword

```mql5
typename
```

---

### return
The return operator terminates the current function execution and returns control to the calling program.

```mql5
return
```

---

### if
The IF - ELSE operator is used when a choice must be made.

```mql5
if
```

---

### else
The IF - ELSE operator is used when a choice must be made.

```mql5
else
```

---

### switch
Compares the expression value with constants in all the case variants and passes control to the operator that corresponds to the expression value.

```mql5
switch(expression)
	{
		case constant: operators; break;
		case constant: operators; break;

		default: operators; break;
	}
```

---

### while
The while operator consists of a checked expression and the operator, which must be fulfilled.

```mql5
while
```

---

### for
The for operator consists of three expressions and an executable operator

```mql5
for (int i = 0; i < count; i++)
	{
		
	}
```

---

### break
The break operator terminates the execution of the nearest nested outward switch, while, do-while or for operator.

```mql5
break
```

---

### continue
The continue operator passes control to the beginning of the nearest outward loop while, do-while or for operator, the next iteration being called.

```mql5
continue
```

---

### new
The new operator automatically creates an object of a corresponding size, calls the object constructor and returns a descriptor of created object.

```mql5
new
```

---

### delete
The delete operator deletes an object created by the new operator, calls the corresponding class destructor and frees up memory occupied by the object.

```mql5
delete
```

---

### dynamic_cast
When using the dynamic_cast operator, the compiler does not check the data type used for the conversion.

```mql5
dynamic_cast
```

---

### sizeof
Using the sizeof operation, the memory size corresponding to an identifier or type can be defined.

```mql5
sizeof
```

---

### do
Checks the condition of termination at the end, after each loop iteration.

```mql5
do
```

---

### default
Operators marked by the default label are executed if none of the constants in case operators is equal to the expression value. The default variant should not be necessarily declared and should not be necessarily the last one.

```mql5
default
```

---

### case
Keyword.

```mql5
case
```

---

### pack
The special pack attribute allows setting the alignment of structure or class fields.

```mql5
pack
```

---

### offsetof 
offsetof is a special command directly related to the pack attribute. It allows us to obtain a member offset from the beginning of the structure.

```mql5
offsetof 
```

---

### operator
Overloading operator

```mql5
operator
```

---

### define
The #define directive can be used to assign mnemonic names to constants.

```mql5
#define 
```

---

### undef
The #undef directive cancels declaration of the macro substitution, defined before.

```mql5
#undef 
```

---

### property
The compiler will write declared values in the configuration of the module executed.

```mql5
#property 
```

---

### icon
Path to the file of an image that will be used as an icon of the EX5 program. Path specification rules are the same as for resources. The property must be specified in the main module with the MQL5 source code. The icon file must be in the ICO format.

```mql5
icon
```

---

### link
Link to the company website

```mql5
link
```

---

### copyright
The company name

```mql5
copyright
```

---

### version
Program version, maximum 31 characters

```mql5
version
```

---

### description
Brief text description of a mql5-program. Several description can be present, each of them describes one line of the text. The total length of all description can not exceed 511 characters including line feed.

```mql5
description
```

---

### stacksize
MQL5 program stack size. The stack of sufficient size is necessary when executing function recursive calls.
When launching a script or an Expert Advisor on the chart, the stack of at least 8 MB is allocated. In case of indicators, the stack size is always fixed and equal to 1 MB.
When a program is launched in the strategy tester, the stack of 16 MB is always allocated for it.

```mql5
stacksize
```

---

### library
A library; no start function is assigned, functions with the export modifier can be imported in other mql5-programs

```mql5
library
```

---

### indicator_applied_price
Specifies the default value for the "Apply to" field. You can specify one of the values of ENUM_APPLIED_PRICE. If the property is not specified, the default value is PRICE_CLOSE

```mql5
indicator_applied_price
```

---

### indicator_chart_window
Show the indicator in the chart window

```mql5
indicator_chart_window
```

---

### indicator_separate_window
Show the indicator in a separate window

```mql5
indicator_separate_window
```

---

### indicator_height
Fixed height of the indicator subwindow in pixels (property INDICATOR_HEIGHT)

```mql5
indicator_height
```

---

### indicator_buffers
Number of buffers for indicator calculation

```mql5
indicator_buffers
```

---

### indicator_plots
Number of graphic series in the indicator

```mql5
indicator_plots
```

---

### indicator_minimum
The bottom scaling limit for a separate indicator window

```mql5
indicator_minimum
```

---

### indicator_maximum
The top scaling limit for a separate indicator window

```mql5
indicator_maximum
```

---

### indicator_labelN
Sets a label for the N-th graphic series displayed in DataWindow. For graphic series requiring multiple indicator buffers (DRAW_CANDLES, DRAW_FILLING and others), the label names are defined using the separator ';'.

```mql5
indicator_labelN
```

---

### indicator_colorN
The color for displaying line N, where N is the number of graphic series; numbering starts from 1

```mql5
indicator_colorN
```

---

### indicator_widthN
Line thickness in graphic series, where N is the number of graphic series; numbering starts from 1

```mql5
indicator_widthN
```

---

### indicator_styleN
Line style in graphic series, specified by the values of ENUM_LINE_STYLE. N is the number of graphic series; numbering starts from 1

```mql5
indicator_styleN
```

---

### indicator_typeN
Type of graphical plotting, specified by the values of ENUM_DRAW_TYPE. N is the number of graphic series; numbering starts from 1

```mql5
indicator_typeN
```

---

### indicator_levelN
Horizontal level of N in a separate indicator window

```mql5
indicator_levelN
```

---

### indicator_levelcolor
Color of horizontal levels of the indicator

```mql5
indicator_levelcolor
```

---

### indicator_levelwidth
Thickness of horizontal levels of the indicator

```mql5
indicator_levelwidth
```

---

### indicator_levelstyle
Style of horizontal levels of the indicator

```mql5
indicator_levelstyle
```

---

### script_show_confirm
Display a confirmation window before running the script

```mql5
script_show_confirm
```

---

### script_show_inputs
Display a window with the properties before running the script and disable this confirmation window

```mql5
script_show_inputs
```

---

### tester_indicator
Name of a custom indicator in the format of "indicator_name.ex5". Indicators that require testing are defined automatically from the call of the iCustom() function, if the corresponding parameter is set through a constant string. For all other cases (use of the IndicatorCreate() function or use of a non-constant string in the parameter that sets the indicator name) this property is required

```mql5
tester_indicator
```

---

### tester_file
File name for a tester with the indication of extension, in double quotes (as a constant string). The specified file will be passed to tester. Input files to be tested, if there are necessary ones, must always be specified.

```mql5
tester_file
```

---

### tester_library
Library name with the extension, in double quotes. A library can have 'dll' or 'ex5' as file extension. Libraries that require testing are defined automatically. However, if any of libraries is used by a custom indicator, this property is required

```mql5
tester_library
```

---

### tester_set
Name of the set file with the values ​​and the step of the input parameters. The file is passed to tester before testing and optimization. The file name is specified with an extension and double quotes as a constant string. 
 
If you specify the EA name and the version number as "<expert_name>_<number>.set" in a set file name, then it is automatically added to the parameter versions download menu under the <number> version number. For example, the name "MACD Sample_4.set" means that this is a set file for the "MACD Sample.mq5" EA with the version number equal to 4.
 
To study the format, we recommend that you manually save the test/optimization settings in the strategy tester and then open the set file created in this way.

```mql5
tester_set
```

---

### tester_no_cache
When performing optimization, the strategy tester saves all results of executed passes to the optimization cache, in which the test result is saved for each set of the input parameters. This allows using the ready-made results during re-optimization on the same parameters without wasting time on re-calculation. 
 
But in some tasks (for example, in math calculations), it may be necessary to carry out calculations regardless of the availability of ready-made results in the optimization cache. In this case, the file should include the tester_no_cache property. The test results are still stored in the cache, so that you can see all the data on performed passes in the strategy tester.

```mql5
tester_no_cache
```

---

### tester_everytick_calculate
In the Strategy Tester, indicators are only calculated when their data are accessed, i.e. when the values of indicator buffers are requested. This provides a significantly faster testing and optimization speed, if you do not need to obtain indicator values on each tick.
 
By specifying the tester_everytick_calculate property, you can enable the forced calculation of the indicator on every tick. 
 
Indicators in the Strategy Tester are also forcibly calculated on every tick in the following cases:

when testing in the visual mode;
if the indicator has any of the following functions: EventChartCustom, OnChartEvent, OnTimer;
if the indicator was created using the compiler with build number below 1916.

 
This feature only applies in the Strategy Tester, while in the terminal indicators are always calculated on each received tick.

```mql5
tester_everytick_calculate
```

---

### optimization_chart_mode
Specifies the chart type and the names of two input parameters which will be used for the visualization of optimization results.

```mql5
optimization_chart_mode
```

---

### resource
The #resource command tells the compiler that the resource at the specified path path_to_resource_file should be included into the executable EX4/EX5 file.

```mql5
#resource 
```

---

### include
Tells the preprocessor to include the contents of the specified file at the point where the directive is displayed.

```mql5
#include 
```

---

### import
Functions are imported from compiled MQL5 modules (*.ex5 files) and from operating system modules (*.dll files).

```mql5
#import "file_name"
	func1 define;
	func1 define;
#import
```

---

### ifdef
The code is compiled if the identifier has already been defined for the preprocessor in #define directive.

```mql5
#ifdef identifier
	
#endif
```

---

### ifndef
The code is compiled if the identifier is not currently defined by #define preprocessor directive.

```mql5
#ifndef identifier
	
#endif
```

---

### endif
```mql5
#endif
```

---

### this
The reserved word this is intended for obtaining the reference of the object to itself, which is available inside class or structure methods.

```mql5
this
```

---

### true
<bool> 'True', numeric representation = '1'

```mql5
true
```

---

### false
<bool> 'False', numeric representation = '0'

```mql5
false
```

---

### template
Keyword.

```mql5
template
```

---

### group
Keyword.

```mql5
group
```

---

### namespase
A namespace is a specially declared area, within which various IDs are defined: variables, functions, classes, etc.

```mql5
namespase
```

---

### extern
The extern keyword is used for declaring variable identifiers as identifiers of the static storage class with global lifetime.

```mql5
extern
```

---

### input
The input storage class defines the external variable. The input modifier is indicated before the data type.

```mql5
input
```

---

### static
The storage class of static defines a static variable. The static modifier is indicated before the data type.

```mql5
static
```

---

