Created using C++ (MQL4)

ALGORITHIM TAKES IN 3 PARAMETERS double input lotsize = X; //Lot Size int input Max_profit = X; //Profit to close 50% (In Pips) int input Max_TP = X; //Maximum Profit to close all (in Pips)

The EA runs on the 1H time frame and executes and reopens trades based on 5 min timeframes. This can be altered in the file by just changing the '5 Min' Interval to choice of preferance.

EA moves x amount of pips in a certain direction, then executes a position in the same current trend to subsidize on the move up (BUY) or down (SELL). Once price reaches X amuont of pips in either continous direction it will then automatically proceed to close half the position opened and set the current position to breakeven.

With a Stop Loss of X amount of pips and a TP with X amount the EA is able to create a solid R:R ratio to capilaize on trades and therefore grow any trading account in a steady rate.

Backtesting data over 6 months (Jan-May;2022)

