## Introduction

A time series is a list of dates, each of which is associated with a value and It is a structured
way of representing data. Plotting this kind of data can allow us to visually see the evolution
of a situation over the time. Time series forecasting is considered one of the most applied
data science techniques that are used in different industries such as finance, supply chain
management, production, and inventory planning. Stock prices forecasting, weather
forecasting, business planning are only a few of the many possible applications.
Time series forecasting means extending the historical values of the series into the future,
where measurements have not yet been made. Two main variables are defined for
forecasting: number of periods and prediction horizon. The number of periods represents
the level of aggregation of the data. Usually the data is by months, weeks or days, allowing
the necessary degree of disaggregation to be obtained in order to draw correct conclusions.
Every forecast has a scope associated with it, which can be short, medium or long term. In
general terms, the following summary table is presented, although the scope varies
according to the industry.

## Objetive

Our goal is to forecast the Gross Domestic Product per capita for all the countries we have
in our dataset for the 3 years ahead of the data and deploy our models into a Power BI App
so users can easily get insigths about the world.
Our data consist in a time series, so first we are going to use Python to pre-process the data
and build 4 time series forecast models with ARIMA, Auto-ARIMA, Prophet and Regression
to forecast the values of the upcoming years. Each of this models may be slightly different
from each other, so we would like to know wich one has the best fit by calculating the RMSE. 
