# Task 5 – Backtesting & Benchmark Comparison

## Overview
This task focuses on evaluating the performance of our trading strategy through backtesting and comparing it against a benchmark index.  
The goal is to determine whether the strategy delivers superior risk-adjusted returns compared to a passive investment.

## Objectives
- Backtest the strategy using historical stock price data.
- Calculate key performance metrics:
  - **Cumulative Returns**
  - **Annualized Returns**
  - **Volatility**
  - **Sharpe Ratio**
  - **Maximum Drawdown**
- Compare results with a benchmark index (e.g., S&P 500).
- Visualize cumulative returns for **strategy vs. benchmark**.

## Methodology

### 1. Data Preparation
- Used historical stock price data for the target asset and benchmark.
- Aligned timeframes and handled missing values.

### 2. Strategy Backtesting
- Simulated trades using the strategy's initial optimal weights.
- Compounded returns over the testing period.

### 3. Performance Evaluation
- Computed both absolute and risk-adjusted metrics.
- Compared performance against the benchmark.

### 4. Visualization
- Plotted cumulative returns for a clear visual comparison.

## Results Summary
- Strategy **outperformed** the benchmark in terms of cumulative returns and Sharpe Ratio.
- Volatility was slightly higher than the benchmark but compensated by higher returns.
- The strategy demonstrated **lower drawdowns** during market downturns.

## Key Takeaways
- Backtesting confirmed the strategy’s potential for **consistent outperformance**.
- Further testing on different timeframes and assets is recommended.
- Incorporating **transaction costs** and **slippage** would make results more realistic.
