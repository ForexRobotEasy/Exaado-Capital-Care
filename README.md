# Exaado Capital Care

Exaado Capital Care is a trading program developed by the Forex Robot Easy Team. This program is designed to help traders control their drawdown and manage their trades based on specified profit and loss values.

## Functions

The program includes the following functions:

### Close_Profit_Pips

This function closes all trades when the current profit in pips reaches a specified value. It first retrieves the current profit in pips using the GetProfitInPips() function. If the current profit is greater than or equal to the specified value, it closes all trades and prints a log message.

### Close_Profit_Money

This function closes all trades when the current profit in monetary terms reaches a specified value. It first retrieves the current profit in monetary terms using the GetProfitInMoney() function. If the current profit is greater than or equal to the specified value, it closes all trades and prints a log message.

### Close_Profit_Percentage

This function closes all trades when the current profit percentage reaches a specified value. It first retrieves the current profit percentage using the GetProfitPercentage() function. If the current profit percentage is greater than or equal to the specified value, it closes all trades and prints a log message.

### Cut_Loss_Pips

This function cuts losses and closes all trades when the current loss in pips reaches a specified value. It first retrieves the current loss in pips using the GetLossInPips() function. If the current loss is greater than or equal to the specified value, it closes all trades and prints a log message.

### Cut_Loss_Money

This function cuts losses and closes all trades when the current loss in monetary terms reaches a specified value. It first retrieves the current loss in monetary terms using the GetLossInMoney() function. If the current loss is greater than or equal to the specified value, it closes all trades and prints a log message.

### Cut_Loss_P

This function cuts losses and closes all trades when the current loss percentage reaches a specified value. It first retrieves the current loss percentage using the GetLossPercentage() function. If the current loss percentage is greater than or equal to the specified value, it closes all trades and prints a log message.

### OnTick

The main function of the program. It is executed on every tick and calls the trading functions with customizable values. This is where the trader can specify the profit and loss values at which they want to close or cut trades.

## Product Description

Exaado Capital Care is a powerful trading program developed by the Forex Robot Easy Team. It is designed to help traders effectively manage their trades and control drawdown.

With Exaado Capital Care, traders can set specific profit and loss values at which they want to close or cut their trades. This allows for precise control over their trading strategy and helps to minimize potential losses.

The program offers several functions, including closing trades based on profit in pips, profit in monetary terms, and profit percentage. It also provides the ability to cut losses based on loss in pips, loss in monetary terms, and loss percentage.

Exaado Capital Care is a reliable and efficient tool for traders who want to take control of their trading and optimize their profitability. It is easy to use and customizable, allowing traders to tailor it to their specific trading needs.

Please note that ForexRobotEasy is not the official developer of this product. We are showcasing this sample code to demonstrate how the program works. For detailed reviews and trading results of this product, please visit the official developer's site at [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/exaado-capital-care-review-your-solution-for-drawdown-control/). To find the official developer of this product, we recommend using MQL5.
