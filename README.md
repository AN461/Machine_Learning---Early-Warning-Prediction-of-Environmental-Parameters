# Early Warning Prediction of Environmental Parameters Using Machine Learning Models

## problem Statement
The safety and productivity of underground mines heavily depend on environmental conditions. Predicting and classifying these conditions based on key parameters such as CO2, CO, NO levels, temperature, and humidity is crucial for ensuring worker safety and optimizing productivity.

## Objective
The objective of this project is to forecast environmental conditions in underground mines using machine learning models. Specifically, we aim to implement LSTM, ARIMA, SARIMA, and XGBoost models to predict CO2, CO, NO levels, temperature, and humidity. The project also involves analyzing the correlation between environmental parameters and extracting insights to improve safety measures.

## About Dataset
The dataset comprises DateTime and environmental parameters collected over a period of 40 days. It includes data on CO2, CO, NO levels, temperature, and humidity, which are essential for environmental condition analysis in underground mines.

## Implemented ML Models
We implemented four machine learning models:

--> Long Short-Term Memory (LSTM)
--> Seasonal AutoRegressive Integrated Moving Average (SARIMA)
--> eXtreme Gradient Boosting (XGBoost)
These models were chosen for their effectiveness in time series forecasting and their ability to capture complex patterns in the data.

## Comparison and Results:
We compared the performance of the implemented models based on metrics such as RMSE, MAE, and accuracy. The results showed that LSTM consistently outperformed the other models, demonstrating lower error values and higher accuracy in predicting environmental conditions.

## Conclusion
In conclusion, LSTM emerged as the most effective model for forecasting environmental conditions in underground mines. Its superior performance, coupled with its ability to capture complex temporal dependencies, makes it well-suited for this task. Further analysis and evaluation are necessary to validate the model's performance and ensure its practical use in early warning predictions for underground mines.
