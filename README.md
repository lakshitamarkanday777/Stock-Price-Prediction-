# Stock-Price-Prediction-

# 📈 Stock Price Prediction using Prophet

This project demonstrates how to use Facebook's Prophet library to predict stock prices. It uses historical stock data from Yahoo Finance and visualizes future trends using time series forecasting techniques.

## 🧠 Project Overview

- **Objective:** Predict future stock prices using time series forecasting.
- **Tool Used:** Facebook Prophet
- **Data Source:** Yahoo Finance (e.g., Reliance stock)
- **Notebook Name:** `Lakshita_Prophet_to_predict_stocks.ipynb`

## 📂 Project Structure

- `Lakshita_Prophet_to_predict_stocks.ipynb`: The main Jupyter Notebook for fetching, cleaning, visualizing, and forecasting stock data.

## 🚀 Features

- ✅ Fetches historical stock data using `yfinance`
- ✅ Prepares data for Prophet model (using 'Date' and 'Close' columns)
- ✅ Forecasts future prices with Prophet
- ✅ Visualizes:
  - Historical stock trends
  - Forecasted future trends
  - Prophet’s trend and seasonality components

## 🔧 Requirements

You can install all the required libraries using:

```bash
pip install yfinance prophet matplotlib pandas
