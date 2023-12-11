# Call of Night MT4

*Developed by Forex Robot Easy Team*  
*Website: [forexroboteasy.com](https://forexroboteasy.com)*

## Description

Call of Night MT4 is a trading robot that utilizes a custom indicator and price action filter to execute trades in the MetaTrader 4 platform. This code provides a sample implementation of the trading logic used in the Call of Night MT4 robot.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in the product. To find the official developer of this product, please refer to the MQL5 website.

For detailed reviews and trading results of the official Call of Night MT4 robot, please visit the [official product page](https://forexroboteasy.com/forex-robot-review/call-of-night-mt4-review-limited-199-forex-software-offer/).

## Indicator

The custom indicator in this code is used to generate a value based on specific market conditions. The indicator value is displayed on the chart using the `Comment` function. If the indicator value is greater than 0, an alert is triggered to notify the user.

## Price Action Filter

The price action filter in this code is used to analyze price patterns and generate specific signals. The price action signal is interpreted using a `switch` statement, and the corresponding message is displayed using the `Comment` function.

## Trade Execution

The trade execution logic in this code is based on the indicator and price action signals. If the indicator value is greater than 0 and the price action signal is 1, a buy trade is opened using the `OrderSend` function. The trade is then closed after a specified time using the `OrderClose` function.

## Usage

1. Install the Call of Night MT4 robot in your MetaTrader 4 platform.
2. Copy and paste this code into the MetaEditor in MetaTrader 4.
3. Compile the code and attach the resulting indicator to the desired chart.
4. Make sure to set the appropriate parameters for lot size, stop loss, and take profit.
5. The code will automatically execute trades based on the indicator and price action signals.

Please note that this is a sample code and may need modifications to work with the official Call of Night MT4 robot. It is recommended to refer to the official developer for specific usage instructions and support.

For detailed reviews and trading results of the official Call of Night MT4 robot, please visit the [official product page](https://forexroboteasy.com/forex-robot-review/call-of-night-mt4-review-limited-199-forex-software-offer/).
