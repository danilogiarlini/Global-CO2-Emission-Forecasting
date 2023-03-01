# GlobalCO2EmissionPrediction

## Project overview

#### Team
Ajay Krishna & Danilo Giarlini

#### Source
"Emission by Country" from Kaggle: https://www.kaggle.com/datasets/thedevastator/global-fossil-co2-emissions-by-country-2002-2022

#### Dataset structure
11 columns and 63000 rows (reduced to around 3000 for our purpose). Columns are: time, total emission, emission from coal, emission from gas etc.

#### Problem type
Multivariate Time series 

#### Framework used
Vector Autoregression (VAR)

## Goal

Design a multivariable time-series model that predicts the total and emissions per energy sector for a selected number of countries.

## (Preliminary) Motivation step

Visualize the total emission based on input features (using Python or Tableau).

## Problem statement 

Pick 10 categories (3 developed countries, 3 developing countries, 3 under developed countries and 1 global). 

1. Design a multivariable time-series model.
2. Use VAR to predict the total and emissions per energy sector.

## Timeline

### 28.02.23

1. Explore the data.
2. Select the data for 10 categories mentioned above.

### 01.03.23

1. Check if the dataset satisfies the prerequired tests of VAR (Granger’s Causality Test and Cointegration test). If the tests are failing, try dropping some columns or try trimming the data (as an example). And then, run the tests again.
3. Implement VAR in python for one country (one of the subdatasets).

### 02.03.23

1. Write a for loop and check if the VAR approach works for all the selected countries. 
2. Plot the results. 
3. Compare the accuracy in prediction (for the test set) for different countries.

### 03.03.23

1. Prediction using VAR for unseen time point, i.e., for the data set, predict the emissions from 2023 to 2030.
2. Plot the prediction.
3. Check if a mathematical relation between the total emissions and the sector-based emissions can be extracted from VAR. If yes, then

   3a. evaluate which sector contributes the most to the total emission and
   
   3b. think of a way whether sectors can be prioritized (e.g., feature importance concept using Lasso, Ridge). 

### 06.03.23

1. Further improvements and learning

### 07.03.23

1. Further improvements and learning


### 08.03.23

1. Visualization on Tableau/Python to motivate the problem.
2. Presentation

    2a. Make the structure and skeleton
    
    2b. Brainstorm what we want to show
    
### 09.03.23

1. Presentation final

