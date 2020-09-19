# Dual-Moving-Average-Crossover-Python
The famous and simple Dual Moving Average crossover strategy implemented in Python, and then backtesting it on 2 years of AAPL stock.

Playaround - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rbhatia46/Dual-Moving-Average-Crossover-Python/master)

**Disclaimer - This is purely for educational and research purposes, I am in no way responsible for any monetary loss/gain you make using this, I highly encourage you to view this as a learning resource and not as a trading advice.**

Dual Moving Average Crossover is a famous and simple trading strategy employed by a lot of traders, as it is simple to undeerstand and outputs profitable trading signals many a times, this repository shows how you can code this simple strategy in Python and backtest the same, in this example, we apply this straegy to 2 yrs of AAPL stock, and this returns a **32% on your investment in 2 years**, not bad!

The basic concept behind the strategy is to use 2 moving averages, one short and one long, these are relative terms and depends on the span of trading, if you are a Swing trader, you might wanna change these values to a relatively shorter time frame, here I use 30 and 100 for 2 years of data, these numbers will change, but the gist of strategy remains the same - it gives a buy signal when the short term MA crosses the long term MA(this indicates that the momentum is shifting in the direction of short term average, and the price will likely go up), and a sell signal when vice-versa.

To read more about this strategy, you can visit [this](https://www.wisdomtrading.com/public-trading-systems/dual-moving-average-crossover-trading-system/#:~:text=Dual%20Moving%20Average%20Crossover%20System,crosses%20the%20long%20moving%20average.) link.

### Libraries Used - 

* numpy
* pandas
* plotly
* bokeh
* [backtesting.py](https://github.com/kernc/backtesting.py)
* yfinance [For fetching financial data](https://github.com/rbhatia46/Fetching-Financial-Data)

