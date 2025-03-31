# Stock-price
Stock Market Prediction using LSTM, GRU, and Sentiment Analysis using FINBERT. Apply PGD adversinal training.

# Overview

This project focuses on predicting stock prices using machine learning models, specifically GRU and LSTM, while incorporating sentiment analysis from financial news. The dataset includes historical stock prices of Apple (AAPL) and Tesla (TSLA), along with technical indicators and sentiment scores extracted from Apple-related news.


# Data Collection

Historical stock prices for Apple (AAPL) and Tesla (TSLA).

Apple and tesla related financial news.

# Feature Engineering

Technical indicators added to stock data:

1. Exponential Moving Average (EMA_100)

2. Relative Strength Index (RSI)

3. Volatility_10 (10-day rolling standard deviation)
   
4. Daily Return
  
# Sentiment Analysis

Extracted sentiment scores from Apple news using FinBERT.

# Preprocessing

Applied Robust Scaling to normalize the data.

Combined stock market features with sentiment scores.

# Model Training & Testing

1. Training & Validation Data: Apple stock data

2. Testing Data: Tesla stock data

Implemented GRU and LSTM models.

GRU performed better than LSTM on this dataset.

# Adversarial Training

Applied Projected Gradient Descent (PGD) adversarial training.

Adversarial training weakened GRU performance instead of improving it.

# Results

GRU outperformed LSTM on the test data.
PGD adversarial training did not improve model performance, making the GRU model weaker.
