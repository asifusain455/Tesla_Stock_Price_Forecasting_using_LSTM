# Tesla Stock Price Forecasting Using LSTM

## Overview

This project predicts **Tesla (TSLA) stock closing prices** using a **Long Short-Term Memory (LSTM)** neural network. LSTM is a type of Recurrent Neural Network (RNN) specifically designed for time-series forecasting and sequential data analysis.

Historical stock price data is downloaded using the **Yahoo Finance API (yfinance)**, preprocessed, and used to train an LSTM model that predicts future closing prices.

---

## Features

* Download historical Tesla stock data using Yahoo Finance.
* Data preprocessing and normalization using MinMaxScaler.
* Time-series sequence generation with a 60-day look-back window.
* Build and train an LSTM neural network using TensorFlow/Keras.
* Evaluate model performance using Root Mean Squared Error (RMSE).
* Visualize stock prices, training loss, validation loss, and predictions.
* Predict the next day's Tesla stock closing price.

---

## Technologies Used

* Python 3.x
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* yfinance

---


## Dataset

The project automatically downloads historical Tesla stock data from Yahoo Finance.

* Stock Symbol: **TSLA**
* Date Range: **2018–2025** (can be modified)

No manual dataset download is required.

---

## Workflow

1. Download Tesla historical stock prices.
2. Select the closing price column.
3. Normalize data using MinMaxScaler.
4. Create 60-day input sequences.
5. Split data into training and testing sets.
6. Build an LSTM model.
7. Train the model.
8. Evaluate model performance using RMSE.
9. Visualize predictions.
10. Forecast the next day's closing price.

---

#
## Future Improvements

* Predict multiple future trading days.
* Incorporate technical indicators such as RSI, MACD, and Moving Averages.
* Use Bidirectional LSTM or GRU models.
* Build a web application using Flask or Streamlit.
* Compare LSTM with ARIMA, XGBoost, and Transformer-based models.
* Perform hyperparameter tuning to improve accuracy.

---

## Learning Outcomes

Through this project, you will learn:

* Time-series forecasting
* Data preprocessing
* Sequence generation
* LSTM neural networks
* Deep learning using TensorFlow/Keras
* Model evaluation and visualization
* Financial data analysis


This project is developed for educational and learning purposes. You are free to modify and use it for academic or personal projects.
