# Forex Robot Easy - Support and Resistance Indicator

This code is a custom indicator for MetaTrader 5 (MQL5) that calculates and displays support and resistance levels on a chart. The indicator uses a specified number of previous bars to determine these levels, and the sensitivity parameter determines the distance between the levels and the price action.

## Indicator Parameters

- `lookbackBars`: Number of bars to consider for support and resistance calculations.
- `sensitivity`: Sensitivity to determine support and resistance levels.

## How it Works

1. The indicator checks if there are enough bars available for calculations. If not, it prints a message and exits.
2. The `OnInit()` function is called during indicator initialization. It calculates the initial support and resistance levels using the `CalculateSupportResistance()` function.
3. The `OnCalculate()` function is called for each new tick in the chart. It checks if new support and resistance levels have been detected using the `NewLevelsDetected()` function.
4. If new levels are detected, an alert is triggered and the `DisplaySupportResistance()` function is called to display the levels.
5. The `CalculateSupportResistance()` function calculates the support and resistance levels based on the highest high and lowest low of the specified number of previous bars.
6. The `NewLevelsDetected()` function compares the current highest high and lowest low with the previous values to check if new levels have been formed.
7. The `DisplaySupportResistance()` function displays the support and resistance levels in the chart's comments section.

## Product Description

Forex Robot Easy presents a revolutionary Forex software - Master Support Resistance Zones. This indicator, based on cutting-edge technology, accurately identifies support and resistance levels in real-time, providing traders with valuable information for making informed trading decisions.

Master Support Resistance Zones is a custom indicator developed for MetaTrader 5 (MQL5). It uses a sophisticated algorithm to analyze historical price data and identify key levels where the market tends to react. These support and resistance zones are essential tools for any trader looking to improve their trading strategies.

With Master Support Resistance Zones, traders can:

- Identify potential entry and exit points based on support and resistance levels.
- Improve accuracy in trade setups by aligning with significant price levels.
- Fine-tune risk management by setting stop-loss and take-profit levels based on these zones.
- Enhance overall trading performance by gaining a deeper understanding of market dynamics.

Forex Robot Easy is not the official developer of Master Support Resistance Zones. We provide this code as a sample, showcasing the functionality of the indicator. To find the official developer and access detailed reviews and trading results of this product, please visit [Forex Robot Easy - Revolutionary Forex Software: Master Support Resistance Zones](https://forexroboteasy.com/forex-robot-review/revolutionary-forex-software-master-support-resistance-zones/).

Disclaimer: Trading in the Forex market involves substantial risk and may not be suitable for all investors. The use of Master Support Resistance Zones is at your own risk, and Forex Robot Easy is not responsible for any losses incurred while using this indicator. Please trade responsibly and seek professional advice if needed.

For more information and other Forex trading resources, visit [forexroboteasy.com](https://forexroboteasy.com/).
