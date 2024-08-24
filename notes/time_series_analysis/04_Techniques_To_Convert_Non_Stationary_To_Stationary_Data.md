# Techniques to convert Non-Stationary to Stationary Data

## Differencing

Differencing technique helps to remove the trend and seasonality from time series data. 

Differencing is performed by subtracting the previous observation from the current observation.

The differenced data will contain one less data point than original data. So differencing actually reduces the number of observations and stabilize the mean of a time series.

> Difference = previous observation - current observation

After performing the differencing it's recommended to plot the data and visualize the change. In case there is not sufficient improvement you can perform **second order differencing** or even **third order differencing**.

## Transformation

A simple but often effective way to stabilize the variance across time is to apply a power transformation to the time series.

Log, square root, cube root are most commonly used transformation techniques. Most of the time you can pick the type of growth of the time series and accordingly choose the transformation method.

For. e.g. A time series that has a quadratic growth trend can be made linear by taking the square root. In case differencing don't work, you may first want to use one of above transformation technique to remove the variation from the series.

![](https://raw.githubusercontent.com/satishgunjal/images/master/Log_Transformation.png)


## Moving Average

In moving averages technique, a new series is created by taking the averages of data points from original series. In this technique we can use two or more raw data points to calculate the average. This is also called as '**window width (w)**'. Once window width is decided, averages are calculated from start to the end for each set of w consecutive values, hence the name moving averages. It can also be used for time series forecasting.

![](https://raw.githubusercontent.com/satishgunjal/images/master/Moving_Average.png)

# Resource

https://www.kaggle.com/code/satishgunjal/tutorial-time-series-analysis-and-forecasting