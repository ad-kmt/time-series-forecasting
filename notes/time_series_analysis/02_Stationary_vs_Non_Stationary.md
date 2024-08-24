# Stationary Data vs Non-Stationary Data

## Stationary Data
Time series data is said to be stationary when statistical properties like mean, standard deviation are constant and there is no seasonality and trend.
In other words statistical properties of the time series data should not be a function of time.

## Non Stationary Data
(Vice versa)
In a non-stationary time series, the statistical properties change over time, and there is a trend and seasonality component.

## Importance of Stationary Data

Analyzing stationary data is easier and more reliable than non-stationary data

**Why?**

In a stationary time series, the statistical properties of the data points are consistent and do not depend on the time at which they are observed. This means that the relationships and patterns observed in the data are reliable and can be used to make accurate forecasts.

In contrast, a non-stationary time series has statistical properties that change over time, which can make it difficult to draw reliable inferences or make accurate forecasts. As the statistical properties of the data keep changing, any model or analysis based on a non-stationary time series may not provide reliable results.

## Test for Stationarity

> Easy way is to look at the plot and look for any obvious trend or seasonality.

While working on real world data we can also use more sophisticated methods:

- Rolling statistic
- Augmented Dickey Fuller test

## Convert Non-Stationary Data to Stationary Data

In the process of converting to stationary data we transform data so that statistical properies like mean and variance becomes constant, and seasonality and trend is removed.

Below are the few technique used for the same:

- Differencing
- Transformation
- Moving Average


# Resources
https://medium.com/@ritusantra/stationarity-in-time-series-887eb42f62a9

https://www.kaggle.com/code/satishgunjal/tutorial-time-series-analysis-and-forecasting

