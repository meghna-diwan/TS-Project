# Sales Forecasting for Corporación La Favorita

This is the repository for the final project for MSCA Time Series Analysis and Forecasting Course. 
In this project, we tried to forecast the daily sales for the different stores and item across the many Corporación La Favorita stores in Ecuador using linear regression, prophet and heirarchical time series methods.

## Getting Started

* The __final__ folder contains the final R code for this project
* The __notebook__ folder contains the intermediary R code
* The __results__ folder contains the HTML outputs from the R Markdowns in final folder

## Running the Code

All our finalized notebooks are in the "final" folder.

1. Run __01_eda_1.Rmd__, __01_eda_2.ipynb__, __01_eda_3.ipynb__ - 
   This notebook contains the EDA.

2. Run __02_prep_holidays.Rmd__ - 
   This notebook contains the pre-processing for holiday events.

3. Run __03_prep_oil_prices.Rmd__ - 
   This notebook contains the pre-processing for oil prices.
   
4. Run __04_prep_data.Rmd__ - 
   This notebook contains the pre-processing for train dataset to subset to select city, type and items.
   
5. Run __05_linear_regression.Rmd__ - 
   This notebook contains the various variations of the linear regression model.
   
6. Run __06_prophet_model.Rmd__ - 
   This notebook contains the various variations of Facebook's prophet.
   
7. Run __07_hts_model.Rmd__ - 
   This notebook contains the various variations of hierarchical time series.


 ## Results
 
 The results for each model can be found in the "results" folder. 
 The hierarchical time series with combination method was the best performing model giving an SMAPE of 0.91 on a 20-day forecast.
