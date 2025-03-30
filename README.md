Forecasting Sales for Ecuador Grocery Chain Using ARIMA + XGBoost

We built a hybrid forecasting model to predict 15-day sales of a large Ecuadorian grocery store retailer.

Data: The training data includes dates, store and product information, whether that item was being promoted, as well as the sales numbers.
https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data

Model: A hybrid model was built to first predict sales using ARIMA to account for the seasonality in the sales forecast and then using XG Boost 
to predict the non-seasonal attributes of the sales forecast using the promotion and oil prices data.

Result: 13.6% MAPE on 15 day forecast
