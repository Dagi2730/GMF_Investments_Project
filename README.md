# Task 2: Tesla Stock Price Time Series Forecasting

This task involves building and comparing two time series forecasting models to predict Tesla’s stock prices for 2024-2025 using historical data from 2015-2023.

## Models Implemented

- **ARIMA**: A classical statistical model with parameters optimized via `auto_arima`.
- **LSTM**: A deep learning model capturing nonlinear patterns using two stacked LSTM layers.

## Dataset

- Historical daily closing prices of Tesla (TSLA) stock downloaded from Yahoo Finance.
- Train set: 2015-01-01 to 2023-12-31
- Test set: 2024-01-01 to 2025-01-01

## Workflow

1. Preprocessing: Time series creation and filling missing business days.
2. ARIMA model training and forecasting over the test period.
3. LSTM model training on scaled data and forecasting.
4. Performance evaluation using MAE, RMSE, and MAPE metrics.
5. Comparison and discussion of model performance.

## Results Summary

- LSTM outperformed ARIMA on all error metrics, capturing complex temporal dependencies better.
- ARIMA offered interpretability but was less accurate on this dataset.

## How to Run

- Install required packages (`yfinance`, `pmdarima`, `tensorflow`, etc.).
- Run the provided Python scripts or Jupyter notebook cells sequentially.
- View plots and printed evaluation metrics for insights.

---

