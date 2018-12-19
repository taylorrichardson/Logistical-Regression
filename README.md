# Logistical Regression

Taylor Richardson

December 11, 2018

Logistical regression is a machine learning classification algorithm that predicts the probability of a categorical dependent variable

I scaled the data to normalize the features, setting the mean to 0 and a standard deviation of 1, and used a test size of 20%.


The outcome variable denoted a 0 if the student didn't perform better on the next test than on a previous test, and 1 if they did perform better than previously.


This indicates that there are two correlations with outcome, both method and prvperf. 

The model itself is somewhat accurate with a f1 score of 59%. Based on this, we can say that the model isn’t very effective at predicting outcome, but could be useful for forecasting
