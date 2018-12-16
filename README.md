# TradingSim


Demonstration of how to store stock data and 'trade' on it

This will be a small demonstration on how to use the Bloomberg API to access stock market data.
Then we will store it in a pandas dataframe, then you can process this data (not in live time, so complex calculations are not latency-dependent) and apply your own trading strategy, and reap a fake profit.


Data will NOT be on intra-day data, as it is much more difficult to actually obtain this data (you may need a Reuters/Bloomberg account/license). One quick fix I might try in the future is try and take the market data from the Bloomberg web-page, or write a 
program using Selenium to note-down stock market data as it comes into the Bloomberg web-page live.
Note if you manage to get your own intra-day data, the techniques will all still be applicable.

The content of this repo will be a demonstration on how to obtain your own daily stock market data, then create 2 different trading strategies (mean reversion and sentiment analysis), train them and apply them to real market data, and reap a fake profit.
