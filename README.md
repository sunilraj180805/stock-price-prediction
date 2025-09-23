Stock Price Prediction using LSTM

Project Overview
This project uses LSTM (Long Short-Term Memory) neural networks to predict Apple (AAPL) stock prices based on the last 10 years of historical data. The goal is to forecast future trends and evaluate the model’s performance using standard metrics.

Dataset
Source: Yahoo Finance(via yfinance library)
Data used: 2015–2025 Apple Stock (AAPL)
Features: Open, High, Low, Close, Volume, Adj Close

Tech Stack / Libraries
Python 3.11.9
yfinance → Fetch historical stock data
pandas, numpy → Data preprocessing
matplotlib → Data visualization
scikit-learn → Data scaling, evaluation metrics
TensorFlow/Keras → LSTM model building

Model
Model Type: LSTM (Long Short-Term Memory)
Sequence length: 60 days lookback
Layers: LSTM + Dense + Dropout
Optimizer: Adam
Loss: MSE

Results
MAE: 6.32
MSE: 64.89
RMSE: 8.06
R² Score: 0.88

The model explains 88% of the variance, showing strong predictive performance.
