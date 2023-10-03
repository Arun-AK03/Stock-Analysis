# Nifty 50 Stock Price Prediction

## Overview

This repository contains code for predicting the stock prices of Nifty 50 using two different time series forecasting models: SARIMA (Seasonal Autoregressive Integrated Moving Average) and LSTM (Long Short-Term Memory) neural network. The models have been trained and evaluated to achieve an accuracy of approximately 87%.

## Project Structure

The project is organized as follows:

- `data/`: This directory contains the historical Nifty 50 stock price data in CSV format.

- `notebooks/`: This directory contains Jupyter notebooks that walk through the data preprocessing, SARIMA model implementation, ARIMA model implementation, and LSTM model implementation.

- `src/`: This directory contains Python source code files for utility functions, data preprocessing, model training, and evaluation.

## Data

The historical Nifty 50 stock price data is located in the `data/` directory. You can replace this dataset with your own data if needed.

## SARIMA Model

The SARIMA model is a time series forecasting method that takes into account seasonality, trends, and autocorrelation in the data. The steps involved in using SARIMA for stock price prediction are detailed in the SARIMA notebook in the `notebooks/` directory.

To run the SARIMA model:

1. Open the SARIMA notebook in Jupyter.
2. Follow the instructions in the notebook to load and preprocess the data.
3. Train the SARIMA model with the provided code.
4. Evaluate the model's performance and accuracy.

## LSTM Model

The LSTM (Long Short-Term Memory) model is a type of recurrent neural network (RNN) that is well-suited for time series forecasting. The LSTM notebook in the `notebooks/` directory provides a step-by-step guide to building and training an LSTM model for Nifty 50 stock price prediction.

To run the LSTM model:

1. Open the LSTM notebook in Jupyter.
2. Follow the instructions in the notebook to load and preprocess the data.
3. Build and train the LSTM model using the provided code.
4. Evaluate the model's performance and accuracy.

## Model Accuracy

Both the SARIMA and LSTM models have been tuned and trained to achieve an accuracy of approximately 87% on the Nifty 50 stock price data. However, it's important to note that stock price prediction is a challenging task, and actual market behavior can be influenced by many factors beyond the scope of these models.

## Conclusion

This project demonstrates two different approaches for predicting Nifty 50 stock prices using SARIMA and LSTM models. You can use these models as a starting point for your own stock price forecasting tasks and further improve their accuracy by experimenting with hyperparameters and additional features.

Feel free to reach out if you have any questions or need further assistance with using these models. Happy forecasting!
