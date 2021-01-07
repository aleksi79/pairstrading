# pairstrading
Pairs trading project

Pairs trading project that finds cointegrated pairs, runs simple optimization and then back- and forward-tests profitability using the best parameters from optimization. Program uses yfinance to download market data from Yahoo (https://pypi.org/project/yfinance/).

Program is still a work in progress so use it for educational purposes only.

Future plans:
- Using rolling linear regression (OLS) in hedge ratio and spread calculation
- Better back-tester with "real life" trades
- Better optimizer: profit factor etc.
- List of trades with open & close prices, trade sizes, dates, duration etc.
- Add commissions, fees and bid/ask-spread into backtesting
- Portfolio testing
- Live trading
