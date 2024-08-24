# Time Series Analysis Introduction

## What is Time Series Analysis?

Any data recorded with some fixed interval of time is called as time series data. This fixed interval can be hourly, daily, monthly or yearly.

e.g. hourly temp reading, daily changing fuel prices, monthly electricity bill, annual company profit report etc.

In time series data, time will always be independent variable and there can be one or many dependent variable.

### Example

Sales forecasting time series with shampoo sales for every month will look like this,

[![](https://raw.githubusercontent.com/satishgunjal/images/master/Shampoo_Sales.png)](https://www.kaggle.com/code/satishgunjal/tutorial-time-series-analysis-and-forecasting)

## Univariate vs Multivariate

**Univariate time series analysis**: only one variable dependent on time
**Multivariate time series analysis**: multiple variables dependent on time

## Time Series Characteristics
Mean, standard deviation and seasonality defines different characteristics of the time series.

![](https://raw.githubusercontent.com/satishgunjal/images/master/Time_Series_Characteristics.png)

### Trend

Trend represent the change in dependent variables with respect to time from start to end. In case of increasing trend dependent variable will increase with time and vice versa.

In short trend represent the varying mean of time series data.

![](https://raw.githubusercontent.com/satishgunjal/images/master/Trend.png)

### Seasonality

If observations or data variations repeat after fixed time interval then they are referred as seasonal observations. These seasonal changes in data can occur because of natural events or man-made events.

For example every year warm cloths sales increases just before winter.

![](https://raw.githubusercontent.com/satishgunjal/images/master/Seasonality.png)

### Irregularities
Strange dips and jump in the data are called as irregularities. This is also called as **noise**. These fluctuations are caused by uncontrollable events like earthquakes, wars, flood, pandemic etc.

For example because of COVID-19 pandemic there is huge demand for hand sanitizers and masks.

![](https://raw.githubusercontent.com/satishgunjal/images/master/Irregularities.png)

### Cyclicity
Cyclicity occurs when observations in the series repeats in random pattern. Note that if there is any fixed pattern then it becomes seasonality, in case of cyclicity observations may repeat after a week, months or may be after a year. These kinds of patterns are much harder to predict.

## Note
Time series data which has above characteristics is called as 'Non-Stationary Data'. For any analysis on time series data we must convert it to 'Stationary Data'

# Resources

https://www.kaggle.com/code/satishgunjal/tutorial-time-series-analysis-and-forecasting
