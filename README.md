# Stock Price Forecasting

This project compares **statistical** and **stochastic** approaches to forecast stock prices using 5 years of historical data. We evaluate traditional ARIMA modelling versus GBM-based simulation, using daily stock prices from Yahoo Finance (e.g., Apple Inc.).

## 📌 Problem Statement

Predict future stock prices using time series modeling and assess which approach yields better short-term accuracy.

## ⚙️ Methods Used

- **ARIMA** (AutoRegressive Integrated Moving Average)
  - ADF test to confirm stationarity
  - ACF/PACF plots for hyperparameter tuning
- **GBM** (Geometric Brownian Motion)
  - Simulated 10,000 Monte Carlo paths
  - Drift & volatility from log returns

## 📊 Evaluation Metric

- **RMSE (Root Mean Squared Error)** over a 15-day forecast window
- ARIMA vs GBM comparison on actual vs predicted prices

## 🔍 Results

- ARIMA RMSE: ~\(X.XX\)
- GBM RMSE: ~\(Y.YY\)

> ARIMA showed ~22% improvement in RMSE over the GBM baseline in 15-day price forecasting.

## ▶️ How to Run

**Colab Notebook:** [Open in Colab](#)  ← *(Insert real link)*

### Or Clone Locally:

```bash
git clone https://github.com/yourusername/stock-price-forecasting.git
cd stock-price-forecasting
pip install -r requirements.txt
python Stock_Price_Forecasting.ipynb
```

## 🗂️ Files

- `Stock_Price_Forecasting.ipynb` – Main analysis notebook
- `requirements.txt` – Python dependencies
