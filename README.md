# Stock-price-prediction

Train a simple stock price prediction model. Use the series prediction algorithms discussed in the lecture (at least two, for example, the Holt-Winters model and SARIMA). More complex series prediction algorithms can also be used.

1. Find data on the price of any exchange-traded asset The data must contain the value of the asset price for at least each day and the duration for at least a year. You can find the data on kaggle or use the FAANG dataset from the 1st laboratory

2. Preprocess Data. The time series is difficult to predict by day. Make a row by week or month. Delete the trend from the series, if there is one. Use other techniques discussed in the lecture

3. Train Model. Train Models on 80% of Time Series. Predict the remaining 20% (at least 3 points) of the series using models. Plot Models Prediction and True Data

4. Calculate the metric. The metric should reflect the difference between predicted and true data. You can choose the MAPE measure, you can offer your own
