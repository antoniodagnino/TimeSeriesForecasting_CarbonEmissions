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


# 2. Carbon Capture - NBEATS Model Scale data before processing
- Exploratory Data Analysis
    - Data Overview
    - Feature Engineering
    - Pre-Processing (Includes data SCALING)
- Data Modeling
- Forecasting with TEST dataset
