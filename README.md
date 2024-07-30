# Stock-Market-Predictor

This project aims to predict daily price movements of the S&P 500 index using machine learning techniques. It utilizes historical data and various derived features to train a Random Forest Classifier model.

## Features

- Downloads S&P 500 historical data using yfinance
- Incorporates VIX (Volatility Index) data for enhanced prediction
- Implements feature engineering including rolling averages, price ratios, and correlations
- Uses a Random Forest Classifier for prediction
- Includes a backtesting framework to evaluate model performance

## Key Components

1. Data acquisition and preprocessing
2. Feature engineering
3. Model training and prediction
4. Backtesting and performance evaluation

## Results

The model's performance is evaluated using precision score, which measures the accuracy of positive predictions. In this implementation, the model achieved a precision score of 57.7%, indicating that when it predicts an upward movement, it is correct 57.7% of the time
