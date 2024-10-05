
# Stock Price Prediction using LSTM

This repository contains a Jupyter notebook that predicts the closing stock prices of 10 companies using Long Short-Term Memory (LSTM) networks. The original research applied ARIMA, ANN, hybrid ARIMA, and Kalman filter methods for stock price prediction. This work recreates the same predictions using LSTM, providing a modern approach to time series forecasting.

## Introduction

Predicting stock prices is a challenging task due to the dynamic nature of financial markets. In this project, I have implemented LSTM-based models to predict the closing stock prices for 10 different companies, providing an alternative to traditional methods like ARIMA, ANN, hybrid ARIMA, and Kalman filter as seen in a previous research paper.

## Notebooks

This repository contains two notebooks. [The first one](https://github.com/Akif4362/lstm_research/blob/main/Prediction_of_Stock_Price_using_LSTM_(full_data).ipynb) uses the full data of the 10 companies to train and test. [The second notebook](https://github.com/Akif4362/lstm_research/blob/main/Prediction_of_Stock_Price_using_LSTM_(research_data).ipynb) uses only the portion of the data that was used in the original paper so that a better comparison can be attained.

## Dataset

The dataset used in this project consists of historical stock prices for 10 companies. Each stock's historical data includes features such as date, open price, high price, low price, closing price, and volume. You can download the data from [here](https://data.mendeley.com/datasets/23553sm4tn/3).

## Methodology

The LSTM network was chosen for its ability to capture long-term dependencies in sequential data, making it suitable for time series forecasting. The model was trained using the following steps:

    1. Data preprocessing 
    2. Train-test split
    3. Model architecture design (LSTM layers)
    4. Training the LSTM model on the stock price data
    5. Evaluating the model's performance

## Results

The LSTM model successfully predicted the closing stock prices for the 10 companies. The LSTM model achieved significantly lower loss and much better predictions when compared to the traditional methods.

## Acknowledgements

This project was inspired by the paper [A Comparative Study of ARIMA, Artificial Neural Networks, and Kalman Filter Models for Dhaka Stock Exchange Forecasting](https://www.banglajol.info/index.php/GANIT/article/view/73986) 




