# Timeseries_ForecastCO2Emissions
Forecast Carbon Emissions with Time-Series data. This repository contains 2x Jupyter Notebooks that predict Carbon Emissions in the United States using Neural Basis Expansion Analysis for Time series (NBeats). The second notebook has an extra pre-processing step of data been scaled and inverse-transformed before final results.


# 1. Carbon Capture - NBEATS Model
- Exploratory Data Analysis
    - Data Overview
    - Feature Engineering
    - Pre-Processing
- Data Modeling
    - Create NBEATS instance (a generic model for all time-series)
    - Fit the model with all time-series in df
    - Save / load model for future use
    - Forecast on some locations and plot results
    - Create Predictions dataframe
    - Feature Engineering predictions dataframe
- Forecasting with TEST dataset
    - Import Test Dataset
    - Feature Engineering on test dataset
    - Match encoded location from df on test dataset
    - Join predictions based on location and date
    - Export Resuts
 
      
![Predictions_Rev01](https://github.com/antoniodagnino/TimeSeriesForecasting_CarbonEmissions/assets/76269794/6134876f-28a1-4ce8-8afc-2e2ef7a885b9)


# 2. Carbon Capture - NBEATS Model Scale data before processing
- Exploratory Data Analysis
    - Data Overview
    - Feature Engineering
    - Pre-Processing (Includes data SCALING)
- Data Modeling
- Forecasting with TEST dataset
  
  
![Predictions scaled model](https://github.com/antoniodagnino/TimeSeriesForecasting_CarbonEmissions/assets/76269794/1ebb8d8b-63fb-487f-8665-149b7b7a718f)
