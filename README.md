1. Goal
Predict the price of the stock HPG from Hoa Phat Group in the manufacturing sector and listed on the Ho Chi Minh Stock Exchange (HOSE).
2. Data Collection
Source: Investing.com
Period: January 2, 2018, to March 31, 2023
Features: Trading date, closing price, opening price, highest price, lowest price, trading volume, and percentage change compared to the previous day.
How to get historical data: Go to investing.com, find the specific stock (HPG), click on Historical Data button, choose the right period and download data.
3. Requirement
* Carry out the EDA (Exploratory Data Analysis) task on the HPG stock.
  - Plot and interpret price and volume curves.
  - Explain the price change of HPG during the selected period.
* Forecast the stock price (Predictive Analytics) with different Quantitative, Machine Learning models.
  - Train: January 2nd 2018 - February 28th 2022
  - Predict/Test:  March 1st 2022 - March 31st 2023.
  - Two models need to be used: ARIMA (or its variants), LSTM (or its variants)
    + ARIMA (Autoregressive integrated moving average): An econometric model, use first-order differencing to make the series stationary.
    + LSTM (Long Short Term Memory): A deep learning model, do min-max scaling and standardize the data.
  - Use some Hyper-parameter tuning process to get the best parameters for each model.
* Metric results for each model: R square, MAPE, RMSE.
