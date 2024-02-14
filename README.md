# Universal Breakout MT5 ReadMe

This ReadMe file provides an overview of the code for the Universal Breakout MT5 trading robot. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Description

The Universal Breakout MT5 trading robot is designed to place pending orders based on the breakout of a specific price range. It calculates the price range over a given time interval and then places pending orders at the levels of the maximum and minimum price.

## Code Requirements & Specifications

The code includes the following input parameters:

- `BreakoutHour`: The hour to place pending orders.
- `PendingOrderExpiration`: The expiration time for pending orders in hours.

## Required Trading Functions

The code includes the following functions:

### 1. CalculatePriceRange

This function calculates the price range over a specific time interval. It iterates through the time interval and calculates the high and low prices for each interval. It then determines the maximum and minimum prices within the interval and returns the price range.

### 2. PlacePendingOrders

This function places pending orders based on the maximum and minimum prices. It uses the `OrderSend` function to place a BUYSTOP order at the level of the maximum price and a SELLSTOP order at the level of the minimum price. It also sets the expiration time for the pending orders.

## Main Program

The main program executes the following steps:

1. Checks if it's time to place pending orders based on the specified `BreakoutHour`.
2. Calculates the price range over a specific time interval using the `CalculatePriceRange` function.
3. Places pending orders at the levels of the maximum and minimum price using the `PlacePendingOrders` function.

## Backlink and Trading Results

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Universal Breakout MT5 Review](https://forexroboteasy.com/forex-robot-review/universal-breakout-mt5-review-optimize-forex-trading/).

Please note that the backlink provided is for reference purposes only and does not imply any affiliation with ForexRobotEasy.
