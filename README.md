# Stock Market Analysis and Forecasting Using Deep Learning

This project involves analyzing historical stock market data and building a deep learning model to forecast future stock prices. The core focus is on applying a GRU (Gated Recurrent Unit) neural network using PyTorch to handle time series data effectively.

## Overview

The stock market is a critical component of the global economy. Investors, analysts, and institutions rely on accurate forecasting models to make informed trading and investment decisions. This project demonstrates how machine learning and deep learning can be used to gain insights from historical data and forecast stock price trends.

We divide the project into two main parts:
1. **Exploratory Data Analysis (EDA)** – To understand trends, patterns, and relationships in historical stock data.
2. **Forecasting** – To use deep learning models to predict future stock prices.

## Objectives

- Analyze stock price trends for major companies.
- Identify growth patterns and anomalies.
- Use a GRU-based neural network to forecast stock prices.
- Evaluate model performance.

## Technologies Used

- **Python**
- **Jupyter Notebook**
- **PyTorch** – For building the GRU model.
- **Pandas** – For data manipulation.
- **Matplotlib & Seaborn** – For data visualization.
- **Scikit-learn** – For preprocessing and metrics.
- **Plotly** – For interactive plots (optional).

## Dataset

The dataset consists of historical stock price data for the following companies:
- Google
- Microsoft
- IBM
- Amazon

It includes fields like `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, etc.

## Model Description

### GRU (Gated Recurrent Unit)

The GRU is a type of Recurrent Neural Network (RNN) that is effective for capturing long-term dependencies in time series data. It uses gating mechanisms to control the flow of information, making it more efficient and less computationally expensive than LSTM.

## Forecasting Strategy

The model is trained on sequential stock price data using a sliding window approach. It learns the temporal structure of the data and predicts the next price based on previous values.

## Results

The GRU model was able to learn underlying trends in stock data and produced reasonable forecasts for future prices. While not perfect, it demonstrates the potential of deep learning for time series forecasting in financial markets.

