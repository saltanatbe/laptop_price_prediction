# Laptop Price Prediction Project

## Description
This project aims to predict the price of laptops based on the main features of the laptop.

## Dataset
The laptop price prediction model was trained on a dataset of laptop with following columns: 'Company', 'TypeName', 'Inches', 'ScreenResolution','Cpu', 'Ram', 'Memory', 'Gpu', 'OpSys', 'Weight', 'Price'.

## Exploratory Data Analysis
Some columns were separated in the process of the data analysis to different columns to prepare the data for the model training. Columns like ScreenResoltuion, CPU, RAM, Memory were processed to get valuable information.

## Model Training
Amongst models like Linear, Lasso, Ridge Regressions and Random Forest, Decision Tree Random Forest performed best.
Then the model was trained using a Random Forest and Decision Tree regression algorithm with hyperparameter tuning.

## Results
The trained Random Forest model achieved an accuracy of 85.64% on the test dataset.
