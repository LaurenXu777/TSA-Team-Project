## Summary

This repository includes the code, datasets (raw and processed), and output used for a project focused on forecasting U.S. gas prices using time series analysis.  

The project explores historical gas price trends, performs data cleaning and transformation, and applies statistical modeling techniques such as ARIMA and SARIMA to generate forecasts.  

This topic was chosen because geopolitical conflicts create significant uncertainty in gas prices, and better forecasting can help individuals and organizations prepare for such shocks.


## Team Members

<Lauren Shohan, Master of Environmental Management student at Duke University, lauren.shohan@duke.edu;
Lauren Xu, Master of Environmental Management student at Duke University, ruoran.xu@duke.edu;
Yeeun Kim, Master of Environmental Management student at Duke University, yeeun.kim@duke.edu;
Saemin Kim, Master of International Development Policy Program, saemin.kim@duke.edu>


## Keywords

Time Series Analysis; Gas Prices; ARIMA; Forecasting


## Database Information

Potential data sources include:

- Weekly U.S. Gasoline Prices (EIA)  
- Crude Oil Prices (WTI/Brent)  
- Weekly U.S. Gasoline Stocks (EIA)  
- Time Range: ~2018–2026 (TBD)


## Folder structure

This repository contains four main folders for raw data, processed data, code, and output.  

- Raw_Data/ contains original datasets  
- Processed_Data/ contains cleaned and transformed data  
- Code/ contains R scripts for analysis and modeling  
- Output/ contains results such as figures and tables  


## Metadata

The dataset includes key variables such as date and gas price, structured for time series analysis.  

Main Dataset:

Column Name | Description        | Data Type | Unit
------------|--------------------|-----------|----------------
Date        | Observation date   | Date      | YYYY-MM-DD
Price       | Gas price          | Numeric   | USD per gallon


## Methodology
- Exploratory Data Analysis (trend, shocks)
- Stationarity tests (ADF)
- Models:
  - ARIMA / SARIMA
  - ARIMAX
  - ETS
  - Prophet
- Evaluation: RMSE, MAE


## Scripts and code

All R scripts used for data processing and analysis are stored in the Code folder. These scripts use the following packages:

- tidyverse for data manipulation  
- ggplot2 for visualization  
- forecast for time series modeling  
- lubridate for date handling  

Script purposes:

- Data Cleaning: Preparing raw gas price data for analysis  
- Exploratory Analysis: Visualizing trends and seasonality  
- Time Series Modeling: Applying ARIMA/SARIMA models  
- Forecasting: Generating future gas price predictions  
