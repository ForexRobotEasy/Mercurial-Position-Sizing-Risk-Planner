# Mercurial Position Sizing Risk Planner

This code is a sample implementation of the Mercurial Position Sizing Risk Planner, which is a powerful tool designed to help traders manage their risk and execute trades effectively. This code provides functions for risk management, automated position sizing, order execution, and break-even protection.

## Risk Management

The `CalculatePositionSize` function calculates the appropriate position size based on the user's desired risk percentage and stop loss level. It ensures that the user never risks more than 1% of their account balance, regardless of leverage.

## Automated Position Sizing

The `CalculatePositionSizeWithRiskTolerance` function takes into account the user's risk tolerance level in addition to the stop loss level. It calculates the maximum risk amount based on the risk tolerance and then calculates the position size using the same formula as in the risk management function.

## Order Execution

The code provides two functions for executing orders: `ExecuteMarketOrder` and `ExecutePendingOrder`. The `ExecuteMarketOrder` function executes a market order to buy a specified symbol with a given volume, stop loss, and take profit level. The `ExecutePendingOrder` function executes a pending order to buy a specified symbol with a given volume, stop loss, take profit level, and price.

## Break Even Protection

The `MoveStopLossToEntryPrice` function moves the stop loss of a specified order to the entry price when the price moves against the user's position. This helps to protect profits and minimize losses.

## Usage Example

The `OnStart` function provides an example of how to use the above functions. It demonstrates the usage of risk management, automated position sizing, order execution (both market and pending orders), and break-even protection.

Please note that this code is a sample implementation and is not the official product. It is provided by Forex Robot Easy for educational purposes and to demonstrate the functionality of the Mercurial Position Sizing Risk Planner. For detailed reviews and trading results of the official product, please visit [here](https://forexroboteasy.com/forex-robot-review/review-mercurial-position-sizing-risk-planner-a-powerful-tool-to-overcome-prop-firm-challenges/). To find the official developer of this product and obtain the actual code, please refer to MQL5.

For detailed reviews and trading results of this product - [https://forexroboteasy.com/forex-robot-review/review-mercurial-position-sizing-risk-planner-a-powerful-tool-to-overcome-prop-firm-challenges/](https://forexroboteasy.com/forex-robot-review/review-mercurial-position-sizing-risk-planner-a-powerful-tool-to-overcome-prop-firm-challenges/)

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
