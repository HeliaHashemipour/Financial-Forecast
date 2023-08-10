# Financial_Forecast
This Project demonstrates a market forecasting analysis using various technical indicators. 
The analysis is performed on cryptocurrency and forex market data using Python programming language.

## Prerequisites
Before running the notebook, ensure you have the following prerequisites:

## Description
> The notebook performs the following steps:
> Data Loading: Import necessary libraries and load three CSV datasets related to currency and cryptocurrency markets.

## Exploratory Data Analysis (EDA)
> Perform basic data exploration by displaying the first few rows of each dataset, checking the length, and displaying dataset information.

## Data Preprocessing
> Calculate price changes for the currency dataset.
> Calculate the label column based on the direction of price changes.
> Calculate the typical price and moving average (MA) for the currency dataset.
> Calculate the mean deviation (MD) for the MA indicator.
> Calculate the Commodity Channel Index (CCI) indicator.
> Calculate the Relative Strength Index (RSI) indicator.
> Calculate the tether-to-Toman exchange rate relative to the dollar.

## Feature Selection 
> Create a new DataFrame containing selected features for analysis.

## Data Cleaning
> Check for missing values in the new DataFrame.

## Correlation Analysis
> Compute the correlation matrix and sort the correlations with the label.

## Model Building

> Split the dataset into training and testing sets.
> Scale the features using StandardScaler.
> Build an Extra Tree Classifier model.
> Evaluate the model's performance using the F1 score on the testing set.

## Final Predictions
> Apply the trained model on the entire dataset to generate predictions.


