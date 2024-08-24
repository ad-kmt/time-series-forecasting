# Prophet Introduction

## Introduction

Prophet is an open-source tool developed by Facebook for forecasting time series data.

It works especially well with data that changes over the day, week, or year (trends or seasonality) and can handle missing data or sudden changes in patterns (outliers).

You can use Prophet even if you're new to time series forecasting because it's designed to be easy to use while still giving accurate results.


### Official Description

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

# Key Concepts

## 1. Time Series Components (via chatgpt)
Prophet decomposes time series data into three main components:

1. **Trend**: Non-periodic changes in the value over time.
2. **Seasonality**: Periodic changes that repeat at regular intervals, such as yearly, weekly, or daily cycles.
3. **Holidays**: Effects of specific events or holidays that cause significant deviations from the trend and seasonality.

## 2. Model Parameters (via chatgpt)
Prophet provides various parameters to customize the forecasting model:

**Growth**: Specifies the type of trend. The default is 'linear', but 'logistic' growth is also supported when working with bounded data.
**Changepoints**: Prophet detects abrupt changes in the trend and introduces 'changepoints' to adjust the model.
**Seasonality Modes**: The model can switch between 'additive' and 'multiplicative' seasonality, depending on how the seasonal patterns influence the overall trend.

## 3. Uncertainty Intervals (via chatgpt)
Prophet allows the user to include uncertainty intervals in forecasts. These intervals account for the uncertainty in future predictions and can be adjusted using the **interval_width** parameter.


# Conclusion

The Prophet library simplifies the process of forecasting time series data, making it accessible for both data scientists and non-experts. Its flexibility to incorporate custom seasonalities, changepoints, and holidays allows for robust forecasting in various use cases. Its ease of use, combined with powerful functionalities, makes it a valuable tool for time series analysis.