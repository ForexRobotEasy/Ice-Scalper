# Ice Scalper ReadMe

Ice Scalper is a trading robot developed by Forex Robot Easy Team. It is designed to execute breakout strategy trades based on the previous high and low price levels. The robot automatically places pending buy and sell orders when the current price crosses these levels.

## Global Variables and Constants

- `previousHigh`: stores the price of the previous high.
- `previousLow`: stores the price of the previous low.
- `ticket`: stores the ticket number of the pending order.

## Custom Functions for Ice Scalper

### `PlaceBuyOrder()`

This function is used to place a pending buy order at the level of the previous high. It calculates the buy price and calls the `OrderSend()` function to send the order.

### `PlaceSellOrder()`

This function is used to place a pending sell order at the level of the previous low. It calculates the sell price and calls the `OrderSend()` function to send the order.

## Initialization Function

The `OnInit()` function is called when the robot is initialized. It initializes the `previousHigh` and `previousLow` variables with the values of the previous high and low prices.

## Deinitialization Function

The `OnDeinit()` function is called before the robot is deinitialized. It can be used to perform necessary cleanup actions.

## Start Function

The `OnTick()` function is called on every tick of the market. It checks if the current price crosses the previous high or low and executes the corresponding pending order. It also checks if any pending order is triggered and closes it at the market price.

## Product Description

Ice Scalper is a professional trading robot that utilizes a breakout strategy to generate profitable trades. It automatically places pending buy and sell orders based on the previous high and low price levels. The robot is designed to take advantage of price breakouts and capture market movements.

Key Features:
- Breakout strategy: Ice Scalper identifies potential breakout levels and places pending orders.
- Automatic order execution: The robot executes buy and sell orders when the price crosses the predefined levels.
- Quick response time: Ice Scalper reacts to market movements in real-time, ensuring timely order placement and execution.
- Easy to use: The robot is designed to be user-friendly and can be easily set up on the MetaTrader platform.
- Detailed reviews and trading results: For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-ice-scalper-a-professional-forex-traders-analysis-of-this-breakout-strategy-robot/).

Please note that ForexRobotEasy is not the official developer of Ice Scalper. We only provide this sample code to demonstrate how the product works. To find the official developer of this product, please refer to the MQL5 platform.
