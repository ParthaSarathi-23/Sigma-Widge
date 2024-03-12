# Sigma-Widge

# Stock Portfolio Optimization

This repository contains Python scripts and functions designed for optimizing stock portfolio values using various models and analyses. The scripts are structured to facilitate forecasting of stock prices, maximizing portfolio value, and providing recommendations for stock purchase based on user input.

## Extracting Data from Quantrocket

The provided data extraction script retrieves daily close prices for Apple stock (ticker symbol 'AAPL') for the year 2023 from Quantrocket.

## Model Fitting and Analysis

### Stock Price Model Inference

A Python class named `Model` is implemented to maximize portfolio value based on a simplistic trading strategy. It includes functionalities such as calculating returns, classifying market states, deriving transition distribution matrix, and maximizing portfolio value based on specified trading rules.

### Test For ARIMA

The ARIMA model is employed for time series forecasting, with tests conducted to examine the stationarity of the provided dataset. Both the KPSS and Dickey-Fuller tests are utilized for this purpose, with interpretations provided for the results.

### Inference based on Stationarity Tests after First-Order Differencing

Following the non-stationarity indication from initial tests, first-order differencing is applied to enhance the suitability of the data for time series analysis. Insights are drawn from the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots to aid parameter selection for time series models.

## ARIMA Forecasting Function

A Python function is provided for time series forecasting using the ARIMA model. The function includes steps for data preparation, model training, forecasting, date generation, and output generation. Parameters are determined based on the results of stationarity tests and analyses.

## Stock Portfolio Optimization Script

The main Python script orchestrates the optimization of stock portfolio values. It prompts the user to input a date, processes the date, forecasts future stock prices using the ARIMA model if necessary, maximizes portfolio value, and provides recommendations for stock purchase based on portfolio performance.

## How to Use

1. Clone the repository to your local machine.
2. Ensure all necessary dependencies are installed by referencing the `requirements.txt` file.
3. Run the provided scripts and functions according to your requirements.
4. Follow the prompts and instructions provided to input necessary data and obtain insights into stock portfolio optimization.



