# **project-06-data-description-prediction**
Predictive Finance Dashboard NASDAQ 100


# ANALYSIS AXIS

Our dataset is an AAPL stock extract from US Stock Market Data & Technical Indicators (https://www.kaggle.com/datasets/nikhilkohli/us-stock-market-data-60-extracted-features),
which is detailled in the following Kaggle link : https://www.kaggle.com/code/nikhilkohli/stock-prediction-using-linear-regression-starter/notebook

## Definitions :
* **MA** = moving average
* **EMA** = Estimated Moving Average
* **t-1 / t-2 / t-3 / t-4 / t-5** = In order to clear the transfer of a security from a seller to a buyer, it must go through a settlement process, which creates a delay between the time a trade is made ('T') and when it settles.
                                  Historically, a stock trade could take as many as five business days (T+5) to settle a trade.
                                  Today, with the advances in technology and electronic trading, most stock trades settle in just two business days (T+2).
* **MA5, MA10, MA20, etc...** = The time period for a moving average can be customized. So you can see the moving average for the past 5 days (MA5), 10 days (MA10), 20 days (MA20), 30 days (MA30), 60 days (MA60) and 120 days (MA120), etc... That said, most traders tend to study the 20-day, 60-day and 120-day trends based on their trading objectives.
* **MACD** = Moving average convergence/divergence (MACD, or MAC-D) is a trend-following momentum indicator that shows the relationship between two exponential moving averages (EMAs) of a security's price.
* **ATR** = Average True Range (ATR) is the average of true ranges over the specified period. ATR measures volatility, taking into account any gaps in the price movement. Typically, the ATR calculation is based on 14 periods, which can be intraday, daily, weekly, or monthly.
* **ADX** = Trading in the direction of a strong trend reduces risk and increases profit potential. The average directional index (ADX) is used to determine when the price is trending strongly. In many cases, it is the ultimate trend indicator.
* **CCI** = The Commodity Channel Index (CCI) measures the current price level relative to an average price level over a given period of time. CCI is relatively high when prices are far above their average.
* **ROC** = The Rate-of-Change (ROC) indicator, which is also referred to as simply Momentum, is a pure momentum oscillator. The ROC calculation compares the current price with the price "n" periods ago.
* **RSI** = The Relative Strength Index (RSI), developed by J. Welles Wilder, is a momentum oscillator that measures the speed and change of price movements. The RSI oscillates between zero and 100. Traditionally the RSI is considered overbought when above 70 and oversold when below 30.
* **Williams %R** is a momentum indicator that is the inverse of the Fast Stochastic Oscillator.
* **STD5** = standard deviation, but why "5" ??

* **SO** = Southern Company is an American gas and electric utility holding company based in the southern United States (??)
* **DIJA** = Dow Jones Industrial Average Stock Prices

## Chart/Widgets ideas:

#### Descriptive :

* The Close values of differents indicators (SnP, QQQ, S, DIJA, Close + CloseForecast)
* Indexes per time series (filters include per year, per quarter, per month, per week, per day + compared to AAPL stock)
* comparison of stock price/volume end of timeperiod vs beginning of timeperiod ( filter through month, quarter, year)
* comparison average for leap years vs non leap years (price/volume)
* comparison between the different MAs (5, 10, 20, 50, 200)
* comparisons between EMAs (10, 20, 50, 100, 200)

#### Predictive :

* Volatility of AAPL stock ( RSI, STD, EMA)
* do a gauge chart for RSI for AAPL stock (with tresholds 30 (overbought) and 70 (overbought) ) with timeline selector.
* see linear regression code in Kaggle & adapt to our purpose : https://www.kaggle.com/code/nikhilkohli/stock-prediction-using-linear-regression-starter/notebook