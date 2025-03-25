# Bitcoin Price Prediction Project

## Overview
The **Bitcoin Price Prediction** project utilizes **time series forecasting** techniques to predict the future price of Bitcoin. This project explores various methodologies, including moving averages and deep learning approaches, to analyze historical Bitcoin price trends and make future predictions.

## Features
- **Historical Bitcoin Data Analysis**: Uses past Bitcoin price trends for forecasting.
- **Time Series Forecasting**: Implements different forecasting techniques.
- **Data Preprocessing**: Handles missing values and normalizes price data.
- **Visualization**: Graphical analysis of historical prices and predictions.
- **Google Colab Integration**: Runs efficiently with GPU support.

## Dataset
The project uses publicly available Bitcoin price data, which includes:
- **Date/Time**
- **Opening Price**
- **Closing Price**
- **High/Low Prices**
- **Trading Volume**

## Prediction Techniques
The notebook explores multiple techniques for Bitcoin price forecasting, including:
1. **Moving Average**: Computes the rolling mean to identify price trends.
2. **Exponential Smoothing**: Uses weighted averages for trend detection.
3. **Deep Learning Models**: RNN, LSTM(with window=7 and Horizon=1),LSTM(window=30,Horizon=7),N-Beats Algorithm and ensemble model  for sequence prediction.

## Results
- **Visualization of Trends**: Displays Bitcoin price trends over time.
- **Forecasting Outputs**: Generates future price predictions.
- **Evaluation Metrics**: Compares predicted vs. actual prices.

## Future Improvements
- **Incorporate Machine Learning Models**: Add regression or deep learning models for better accuracy.
- **Feature Engineering**: Introduce additional financial indicators for improved predictions.
- **API Integration**: Use real-time Bitcoin price data for live forecasting.

---



