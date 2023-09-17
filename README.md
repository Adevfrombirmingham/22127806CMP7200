# 22127806CMP7200
Final Year Project - TimeSeriesForecasting - 22127806 
Maximizing Profitability” Sales Prediction with Cutting-Edge Time Series Forecasting Models
Keywords: Time series forecasting, ARIMA, SARIMA, RNN LSTM, Facebook Prophet, Exponential Smoothing, XGBoost, MAE, MSE, RMSE, MAPE, Data stationarity, Ensemble forecasting, Model bias and variance, Corporación Favorita, Retail sales prediction.

The training data includes dates, store and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models.


Time Series Forecasting Models:
A comprehensive evaluation of diverse time series models is undertaken:

ARIMA (AutoRegressive Integrated Moving Average): A parametric model that leverages lagged values (autoregressions) and lagged forecast errors (moving averages). It is adept at handling non-seasonal patterns in the data.

SARIMA (Seasonal ARIMA): An augmented version of ARIMA, it introduces additional seasonal differencing and seasonal autoregressive and moving average terms, making it suitable for datasets exhibiting seasonality.

Exponential Smoothing: A state space model that gives differential weights to past observations. With its components—error, trend, and seasonality—it's tailored for data with evident temporal structures.

Prophet: A decomposable time series model that captures seasonality at multiple scales. Its ability to factor in holidays and special events makes it particularly suitable for retail sales forecasting.

LSTM (Long Short-Term Memory): An advanced variant of recurrent neural networks (RNNs), LSTM units incorporate memory cells that allow them to learn and remember over long sequences, making them adept at modeling time-dependent sequences with long-range dependencies.

Utilizing historical sales data from Corporación Favorita, these models will undergo systematic training and validation phases. 
The comparative performance metrics, juxtaposed against the XGBoost baseline, aim to elucidate the advantages of time series models
in effectively capturing the intricacies inherent in retail sales data, thereby promoting enhanced forecasting accuracy.

