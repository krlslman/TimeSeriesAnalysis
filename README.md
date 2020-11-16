# TimeSeriesAnalysis
Time Series Analysis Modelling (ARMA and ARIMA models and Auto ARIMA is trained.)

Data is obtained from one of my lectures at Gazi University. (Sales of 8 products for each day between certain time range from an e-commerce website is taken). I don't have any information regarding the correctness or existance of data in real life. (statsmodels and pmdarima packages are used for time series functions.)

Main points during the project;

- Stationarity of sales is examined.
- Data transformation methods are discussed.
- ACF, PACF plots are created and AR & MA components are discussed.
- ARMA and ARIMA models are created via checking ACF and PACF plots.
- Auto ARIMA function is deployed to find best model.
- Best model is decided via minimizing AIC score.
- Predictions are created for each product.
