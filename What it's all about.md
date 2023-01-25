This repository is created for the project in Macroeconometrics course at the University of Tartu.

The essence of the project is to compare the two models used for forecasting oil pice time series. These models are: ARIMA and Prophet. 

The repository includes 2 .ipynb files and one .xls file. The .xls file includes weekly crude oil Brent Europe prices. This document is needed to run the Python codes.

The data on oil prices is retrieved here: https://fred.stlouisfed.org/series/DCOILBRENTEU

If you want to obtain the same data, please follow these steps:
1. Specify time range: January 6th 2012 - January 6th 2023
2. Edit graph
  2.1. Modify frequency: Weekly, Ending Friday
  2.2. Aggregation method: End of Period

Arima_train.ipynb fits ARIMA model. macroeconomtrics_project_prophet.ipynb fits the Prophet model developed by Facebook.
