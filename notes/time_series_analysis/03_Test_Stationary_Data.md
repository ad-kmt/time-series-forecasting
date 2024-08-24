# Tests to verify Stationary Data

> Easy way is to look at the plot and look for any obvious trend or seasonality.

While working on real world data we can also use more sophisticated methods to check stationarity of data:

- Rolling statistic
- Augmented Dickey Fuller test

## Rolling Statistics
In rolling statistics technique we define a size of window to calculate the mean and standard deviation throughout the series. For stationary series mean and standard deviation shouldn't change with time.

## Augmented Dickey Fuller (ADF) Test

We won't go into the details of how this test works.

We will concentrate more on how to interpret the result of this test to determine the stationarity of the series. ADF test will return 'p-value' and 'Test Statistics' output values.

- **p-value > 0.05**: non-stationary.
- **p-value <= 0.05**: stationary.
- **Test statistics**: More negative this value more likely we have stationary series. Also, this value should be smaller than critical values(1%, 5%, 10%). For e.g. If test statistic is smaller than the 5% critical values, then we can say with 95% confidence that this is a stationary series

# Resource

https://www.kaggle.com/code/satishgunjal/tutorial-time-series-analysis-and-forecasting