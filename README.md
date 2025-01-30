# Time-Series-Forecasting
## Forecasting Italian CPI MoM using SARIMAX model
The aim of my project is to derive a time series model from **historical data of Italian Consumer price index (CPI)** on the training sample, thus forecast on hold-out sample to evaluate forecast capability of the model.
My data set is on monthly basis in 10 years, from 01-01-2010 to 01-12-2020 from Federal Reserve Economics Data (FRED). The data set is split into train set and test set (or hold-out sample). The train set is used to find the appropriate regression model. The test set is used to fit the chosen model to forecast, then compare the forecasted CPI from the model and the actual data.

The model I use to forecast is **Seasonal Autoregressive Moving Average model (SARIMA model)**, a time series model which explains dependent variables on its own lagging values (Autoregressive) and lagging residuals (Moving Average). I use SARIMA instead of ARIMA since I recognized seasonal effect in the historical data. I will present more details in the further parts. My project includes the key parts as the following:
- Summary of data trend
- Unit root test and data transformation
- Model fitting
- Forecasting and forecast evaluation
- Conclusion
