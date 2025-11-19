Binance Futures Trading Bot - Testnet
A Python trading bot for Binance Futures Testnet with market and limit order capabilities.

Features
✅ Market Orders (Buy/Sell)

✅ Limit Orders (Buy/Sell)

✅ Real-time price checking

✅ Account balance monitoring

✅ Comprehensive logging

✅ Interactive CLI

Requirements
Python 3.7+

python-binance library

Installation
bash
pip install -r requirements.txt
Usage
Run the bot:

bash
python trading_bot.py
Enter your Binance Futures Testnet API credentials when prompted

Choose from the menu:

Place Market Order

Place Limit Order

Check Current Price

Check Account Balance

Exit

Setup Binance Testnet
Visit https://testnet.binancefuture.com

Log in with your Binance account

Go to API Management

Create a new API key

Copy your API Key and Secret Key

Example Usage
Check BTC Price:

Select option 3

Enter symbol: BTCUSDT

Place Limit Order:

Select option 2

Enter symbol: BTCUSDT

Enter side: BUY

Enter quantity: 0.002

Enter price: 50000

Logging
All operations are automatically logged to timestamped log files:

Format: trading_bot_YYYYMMDD_HHMMSS.log

Includes API requests, responses, and errors

Safety
⚠️ TESTNET ONLY - No real funds involved. This bot uses Binance Futures Testnet for safe testing.

Project Structure
text
binance-trading-bot/
├── trading_bot.py          # Main bot implementation
├── requirements.txt         # Python dependencies
└── README.md               # Documentation
Author
Jathin R
B.Tech CSE Graduate

License
This project is for educational and demonstration purposes.
