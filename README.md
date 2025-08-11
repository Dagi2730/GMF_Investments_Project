# Task 4: Portfolio Optimization Based on Forecast

## Overview
This task implements portfolio optimization using Modern Portfolio Theory (MPT) by combining forecasted returns for Tesla (TSLA) with historical data for bond (BND) and equity (SPY) assets.

The objective is to:
- Use the best-performing TSLA forecast from Task 2 (LSTM 30-day forecast) as expected return
- Use historical average returns for BND and SPY as proxies for their expected returns
- Compute the covariance matrix of asset returns
- Generate the Efficient Frontier through portfolio simulations
- Identify the Maximum Sharpe Ratio (Tangency) and Minimum Volatility portfolios
- Recommend an optimal portfolio based on risk-adjusted return

---

## File Description

**task_4_tesla_bnd_spy_eda.ipynb**  
This Jupyter Notebook performs:
- Loading and preprocessing forecasted TSLA prices and historical TSLA, BND, SPY data
- Calculating expected annual returns and covariance matrix
- Running Monte Carlo simulations to generate portfolio weights and metrics
- Plotting the Efficient Frontier with key portfolios highlighted
- Summarizing and saving optimal portfolio weights, returns, volatility, and Sharpe Ratios

---

## Usage Instructions

1. Ensure the file `tesla_lstm_30day_forecast.csv` is located in the working directory.
2. Execute the notebook cells sequentially.
3. Visualize the Efficient Frontier plot and review printed portfolio summaries.
4. The results are saved as `task4_optimal_portfolios_summary.csv`.

---

## Dependencies

- Python 3.x
- pandas
- numpy
- yfinance
- matplotlib

Install required packages using:
```bash
pip install pandas numpy yfinance matplotlib
