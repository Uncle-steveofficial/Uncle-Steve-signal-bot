# Uncle-Steve-signal-bot

UNCLESTEVECHARTS Breakout Signal Engine - A web-based trading signal generator.

## Features

- Generate random BUY/SELL trading signals
- Support for multiple trading pairs: XAUUSD, GBPUSD, EURUSD, GBPJPY, NAS100, BTCUSD
- Risk management with 1% or 2% risk options
- ATR-based Stop Loss and Take Profit calculations
- Automatic lot size calculation based on risk
- Modern dark-themed UI

## Usage

1. Open `index.html` in your web browser
2. Select your desired trading pair from the dropdown
3. Choose your risk percentage (1% or 2%)
4. Click "Generate Signal" to create a random trading signal

The signal will include:
- Direction (BUY or SELL)
- Entry price
- Stop Loss level
- Take Profit level
- Recommended Lot Size
- Total risk amount in dollars

## Technical Details

- Balance: $1000 (base calculation)
- Stop Loss: 1.5x ATR
- Take Profit: 2.2x ATR
- ATR range: 2-7 (randomly generated)
- Entry price range: 1000-1100 (randomly generated)

## Screenshots

![Initial Interface](https://github.com/user-attachments/assets/f9275dcc-1cd3-4338-98b1-a0b4a4a8f7d1)

![Signal Generated](https://github.com/user-attachments/assets/419e5487-4a46-4267-be30-9e8f68d37ef7)