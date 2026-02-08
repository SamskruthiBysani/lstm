# 📈 Google Stock Price Prediction using LSTM

## Overview
This project uses a Long Short-Term Memory (LSTM) neural network to predict Google (GOOGL) stock prices based on historical market data. The model captures temporal patterns in time-series data to forecast future closing prices.

---

## Problem Statement
Stock price movements are sequential and non-linear in nature. Traditional models often fail to capture long-term dependencies. This project applies an LSTM-based deep learning approach to model these dependencies and predict future prices.

---

## Dataset
- Source: Yahoo Finance  
- Ticker: GOOGLE  
- Features:
  - Open
  - High
  - Low
  - Close
  - Volume  
- Time Period: (add start and end date)

---

## Methodology
- Data cleaning and preprocessing  
- Feature scaling using MinMaxScaler  
- Time-series sequence generation using a sliding window  
- LSTM model training  
- Performance evaluation and visualization  

---

## Model Architecture
- LSTM layers with dropout  
- Dense output layer  
- Optimizer: Adam  
- Loss Function: Mean Squared Error (MSE)

---

## Results
- The model successfully captures overall price trends  
- Evaluation metrics:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

Predicted vs actual stock price plots are included.

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

