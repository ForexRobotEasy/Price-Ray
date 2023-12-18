# Price Ray Forex Software

This is a code for the Price Ray Forex software, developed by the Forex Robot Easy Team. The software is designed to provide real-time price information and enhance trading strategies in the Forex market.

## Features

The Price Ray Forex software comes with the following features:

### Customizability

- Traders can select the text to be displayed above or below the price ray.
- Options such as Bid, Ask, or Last Price can be chosen for the displayed text.
- The software provides the current spread information.
- It displays the range and body size for a defined time-frame candle in pips/points.
- The time left for a candle close is updated in real-time.

### Real-Time Trading

- The software implements a line ray that extends till the current candle, last visible chart candle, or the first candle.
- The line ray can be customized in terms of extension, style, width, and color.
- Traders have the option to enable or disable the line ray.

## How It Works

The code consists of various functions that enable the customizability and real-time trading features of the Price Ray Forex software.

### Customizability Functions

- `SetText(string text)`: Sets the text to be displayed above or below the price ray.
- `SetPriceType(int priceType)`: Selects the type of price to be displayed.
- `DisplaySpread()`: Displays the current spread information.
- `DisplayCandleInformation(int timeFrame)`: Displays the range and body size for a defined time-frame candle.
- `UpdateTimeLeft()`: Updates the time left for a candle close in real-time.

### Real-Time Trading Functions

- `ImplementLineRay(int extension, int style, int width, color rayColor)`: Implements the line ray with customizability options.
- `EnableLineRay(bool enable)`: Enables or disables the line ray.

The `start()` function is the main function that starts the Price Ray Forex software.

## Product Description

Price Ray Forex Software is a powerful tool designed to provide real-time price information and enhance trading strategies in the Forex market. It allows traders to customize the display of price information and provides valuable insights into market conditions.

With Price Ray, traders can select the text to be displayed above or below the price ray and choose from options such as Bid, Ask, or Last Price. The software also provides real-time spread information, helping traders make informed decisions.

Additionally, Price Ray displays the range and body size for a defined time-frame candle, allowing traders to analyze candlestick patterns and identify potential trading opportunities. The time left for a candle close is updated in real-time, enabling traders to time their entries and exits more effectively.

Price Ray also includes a line ray feature that extends to the current candle, last visible chart candle, or the first candle. Traders can customize the line ray's extension, style, width, and color, giving them greater flexibility in their trading strategies. The line ray can be easily enabled or disabled as needed.

Please note that ForexRobotEasy is not the official developer of this product. We are showcasing sample code that can work as described in this product. To find the official developer of Price Ray Forex Software, please visit the MQL5 website.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/price-ray-forex-software-enhance-trading-with-real-results/).
