# Task 1: Preprocess and Explore the Data

## Overview

This task involves loading, cleaning, and exploring historical financial data for three key assets:

- **TSLA:** High-growth, high-volatility stock.
- **BND:** Stable bond ETF with low risk.
- **SPY:** Diversified S&P 500 ETF representing the broader market.

The objective is to prepare the data for modeling by conducting thorough exploratory data analysis (EDA) and assessing key statistical properties.

## Steps Completed

- Extracted historical daily data (2015-07-01 to 2025-07-31) from Yahoo Finance using `yfinance`.
- Checked for missing values and duplicates; handled appropriately.
- Calculated basic statistics and visualized closing prices and daily returns.
- Analyzed volatility through rolling means and standard deviations.
- Detected outliers by identifying days with unusually large daily returns (> ±10%).
- Performed stationarity tests (Augmented Dickey-Fuller) on closing prices and returns.
- Calculated foundational risk metrics: 5% Value at Risk (VaR) and annualized Sharpe Ratio for each asset.

## Key Insights

- TSLA exhibits high volatility with several days of significant price swings.
- BND is stable with negligible extreme daily returns.
- SPY shows moderate volatility consistent with broad market behavior.
- Closing prices for all assets are non-stationary, but daily returns are stationary, supporting modeling with differencing.
- Risk metrics indicate TSLA has higher risk-adjusted returns, while BND offers low risk but lower returns.

## Next Steps

Building and evaluating time series forecasting models (ARIMA and LSTM) on TSLA stock prices for improved portfolio management.

---

