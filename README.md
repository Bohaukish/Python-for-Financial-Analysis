# Python-for-Financial-Analysis

https://www.udemy.com/course/python-for-finance-and-trading-algorithms/learn/lecture/7533536#overview

## Tine Series with statsmodel.tsa

Data EXploration:

- ETS(Error-Trend-Seasonality) Decomposition:  
  
  build an understanding of its behaviour; a time series dataset will be broken down into several terms: an error term, a trend term and a seasonality term.

- EWMA(Expoentially Weighted Moving Averages) Model:

  describe some trend level behavior of a time series; better than SMA(simple moving averages) cuz it gives more weights to nearest dates.

ARIMA model

- The Augmented Dickey-Fuller unit root test: test for Stationarity.

- Difference or Seasonal Difference: make the time series data stationary.

- Figure out the best AR(p)x I(d) x MA(q) combination to build the model

  - Plot ACF and PACF charts 目测选参数，没搞懂，感觉选不准 先放着

  - Grid Search + Akaike's Information Criterion (AIC): Pick the combine which has the lowest AIC value. 

- Forecasting

https://blog.csdn.net/weixin_43178406/article/details/98480427
