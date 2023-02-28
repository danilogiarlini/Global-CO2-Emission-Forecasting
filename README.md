# GlobalCO2EmissionPrediction

## Dataset preview
"Emission by Country" from Kaggle: https://www.kaggle.com/datasets/thedevastator/global-fossil-co2-emissions-by-country-2002-2022

- 11 columns and 63000 rows (reduced to around 3000 for our purpose)
- Time series analysis

## Goal

To design a time-series based regression model that predicts the total emissions for differnt countries in the next 10 years.

## (Preliminary) Motivation step

Visualize the total emission based on input features (one is time) for two countries using Tableau.

## Problem statement 

Pick 10 categories (3 developed countries, 3 developing countries, 3 under developed countries and 1 global).

1. Design a time-series based linear regression model.
2. Optimize the model for feature importance (e.g., by using Lasso, Ridge).
3. Predict the total emissions for the next 10 years.

## Timeline

### 28.02.23

1. Explore the data.
2. Select the data for 10 categories mentioned above.
3. Explore ARIMA model. Check whether the dataset fits the assumptions required in ARIMA.
4. Look into LSTM for forecasting if the ARIMA assumptions are not satisfied.

### 01.03.23

1. Implementing toy examples for ARIMA/LSTM using python.
2. Explore more into the concept of ARIMA/LSTM if needed.
3. Tableau visualization mentioned in the motivation step.
