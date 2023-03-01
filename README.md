# GlobalCO2EmissionPrediction

## Project overview

#### Team
Ajay Krishna & Danilo Giarlini

#### Source
"Emission by Country" from Kaggle: https://www.kaggle.com/datasets/thedevastator/global-fossil-co2-emissions-by-country-2002-2022

#### Dataset structure
11 columns and 63000 rows (reduced to around 3000 for our purpose)

#### Problem type
Multivariate Time series 

#### Framework used
Vector Autoregression (VAR)

## Goal

Design a multivariable time-series model that predicts the total emissions for different countries in the next 10 years.

## (Preliminary) Motivation step

Visualize the total emission based on input features (one is time) for two countries using Tableau.

## Problem statement 

Pick 10 categories (3 developed countries, 3 developing countries, 3 under developed countries and 1 global).

1. Design a multivariable time-series model.
2. Use VAR to predict the total and emissions per energy source/industry sector.

## Timeline

### 28.02.23

1. Explore the data.
2. Select the data for 10 categories mentioned above.

### 01.03.23

1. Check if the dataset satisfies the prerequired tests of VAR.
2. Implement VAR in python for one country (one of the subdatasets).
3. Write a for loop and check if the approach work for all the selected countries
