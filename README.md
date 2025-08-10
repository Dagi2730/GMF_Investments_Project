Task 3: Forecast Future Market Trends

This task focuses on forecasting Tesla’s future stock prices using the time series model developed in Task 2. The main goal is to generate 6-month ahead price predictions, analyze the forecast results, and provide insights on potential market trends and risks.

## Overview

- Utilized the ARIMA model trained on historical Tesla stock data to generate a 6-month forecast.
- Visualized the forecast alongside historical closing prices, including confidence intervals to show prediction uncertainty.
- Conducted trend analysis to identify long-term movements and possible anomalies.
- Evaluated forecast uncertainty by analyzing the width and progression of confidence intervals.
- Discussed potential market opportunities and risks based on forecast trends and volatility.

## Key Findings

- The forecast suggests a [upward/downward/stable] trend in Tesla’s stock price over the next six months.
- Confidence intervals widen over time, indicating increasing uncertainty in long-term predictions.
- Market opportunities exist where expected price increases align with an upward trend.
- Risks include potential volatility and uncertainty highlighted by the confidence interval expansion.

## Usage

Run the Jupyter notebook `task_3_forecast_future_market_trends.ipynb` to reproduce the forecast, visualizations, and analyses.
=======
# GMF Investments Project

This project is part of the GMF Investments Challenge, designed to leverage advanced data science techniques for financial forecasting and portfolio management. The focus is on analyzing historical asset prices, predicting future market movements, and constructing optimized investment portfolios to help clients maximize returns while managing risk effectively.

## Project Goals

1. Time Series Forecasting:  
   Utilize state-of-the-art forecasting models such as ARIMA, Prophet, and LSTM to analyze historical stock prices and predict future price trends. These models help capture patterns, seasonality, and volatility inherent in financial time series data.

2. Portfolio Optimization:  
   Apply portfolio optimization techniques including Mean-Variance Optimization and Sharpe Ratio maximization to construct portfolios that balance risk and return. By integrating forecasted returns with historical covariance, the project aims to recommend optimal asset allocations.

3. Data Visualization and Reporting:  
   Create clear, insightful visualizations and comprehensive summaries of findings to support decision-making. This includes trend analysis, risk assessment, and performance evaluation presented in an accessible format for stakeholders.

## Project Structure

- `data/`  
  Contains raw downloaded financial datasets as well as cleaned and processed data ready for analysis.

- `notebooks/`  
  Jupyter notebooks used for exploratory data analysis (EDA), model development, experimentation, and visualization.

- `scripts/`  
  Standalone Python scripts designed for tasks such as data preprocessing, model training, evaluation, and automation of workflows.

- `outputs/`  
  Stores generated results including plots, model outputs, reports, and other deliverables.

## Technologies

- Programming Language: Python  
- Data Manipulation: Pandas, NumPy  
- Machine Learning & Statistical Modeling: Scikit-learn, Statsmodels, Prophet, TensorFlow/Keras (for LSTM)  
- Visualization: Matplotlib, Seaborn, Plotly  
- Development Environment: Jupyter Notebook, VS Code or similar IDE

