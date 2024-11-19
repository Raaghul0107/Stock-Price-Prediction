
# LSTM Stock Price Prediction
This project uses an LSTM (Long Short-Term Memory) neural network to predict the closing price of Tesla's (TSLA) stock based on historical stock price data from Yahoo Finance. The model is trained using the past 90 days of data to predict the stock's closing price for the following days.

## Overview
Stock price prediction is a challenging problem due to its volatile and non-linear nature. This project leverages LSTM, a type of recurrent neural network (RNN) capable of learning long-term dependencies, to forecast Tesla's stock prices. The model is built using TensorFlow/Keras and visualized using Matplotlib.

## Technologies Used
Programming Language: Python
Libraries:
TensorFlow/Keras
Pandas
NumPy
Matplotlib
Scikit-learn
Yahoo Finance API (yfinance)

## Dataset
The dataset is fetched directly using the Yahoo Finance API. It includes the historical stock prices for Tesla (TSLA) from January 1, 2017, to November 18, 2024.

## Columns:
Open: Opening price
High: Highest price
Low: Lowest price
Close: Closing price
Adj Close: Adjusted closing price

## Required Libraries
TensorFlow
Pandas
NumPy
Matplotlib
Scikit-learn
yfinance

## Usage
Open the script in a Python IDE or Jupyter Notebook.
Run the script to train the LSTM model and predict stock prices.
Visualize the predicted vs actual stock prices using Matplotlib.

## Results
The model predicts the closing stock prices for Tesla (TSLA) with reasonable accuracy. 
The graph below showcases the performance of the LSTM model:

![image](https://github.com/user-attachments/assets/46b05282-86a7-41cc-847c-04af02fd66b5)

## Limitations
The model doesn't account for external factors such as news, earnings reports, or market conditions.
Accuracy can be improved with further hyperparameter tuning and feature engineering.
