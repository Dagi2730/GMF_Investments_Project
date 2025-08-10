<<<<<<< task-2
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
=======
# GMF Investments Project

This project is part of the GMF Investments Challenge, designed to leverage advanced data science techniques for financial forecasting and portfolio management. The focus is on analyzing historical asset prices, predicting future market movements, and constructing optimized investment portfolios to help clients maximize returns while managing risk effectively.

## Project Goals

1. **Time Series Forecasting:**  
   Utilize state-of-the-art forecasting models such as ARIMA, Prophet, and LSTM to analyze historical stock prices and predict future price trends. These models help capture patterns, seasonality, and volatility inherent in financial time series data.

2. **Portfolio Optimization:**  
   Apply portfolio optimization techniques including Mean-Variance Optimization and Sharpe Ratio maximization to construct portfolios that balance risk and return. By integrating forecasted returns with historical covariance, the project aims to recommend optimal asset allocations.

3. **Data Visualization and Reporting:**  
   Create clear, insightful visualizations and comprehensive summaries of findings to support decision-making. This includes trend analysis, risk assessment, and performance evaluation presented in an accessible format for stakeholders.

## Project Structure

- **`data/`**  
  Contains raw downloaded financial datasets as well as cleaned and processed data ready for analysis.

- **`notebooks/`**  
  Jupyter notebooks used for exploratory data analysis (EDA), model development, experimentation, and visualization.

- **`scripts/`**  
  Standalone Python scripts designed for tasks such as data preprocessing, model training, evaluation, and automation of workflows.

- **`outputs/`**  
  Stores generated results including plots, model outputs, reports, and other deliverables.

## Technologies

- **Programming Language:** Python  
- **Data Manipulation:** Pandas, NumPy  
- **Machine Learning & Statistical Modeling:** Scikit-learn, Statsmodels, Prophet, TensorFlow/Keras (for LSTM)  
- **Visualization:** Matplotlib, Seaborn, Plotly  
- **Development Environment:** Jupyter Notebook, VS Code or similar IDE
>>>>>>> main

---

