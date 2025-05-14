# 📈 Stock Market Data Analysis

A comprehensive data analysis project using historical stock market data for 10 companies. This project covers performance metrics, volatility, correlation, and long-term trends using Python and its data science ecosystem.

## 🔧 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📊 Project Overview

This project explores historical stock data and extracts key insights through data wrangling, statistical analysis, and visualizations.

### ✅ Key Features

- **Data Cleaning**: Converted date formats, renamed columns, and prepared data for analysis.
- **Performance Analysis**: Identified each stock's minimum and maximum adjusted close prices with dates.
- **Daily Return Analysis**:
  - Calculated average daily returns per stock
  - Visualized results using bar plots
- **Volatility**: Measured and ranked each stock by standard deviation of daily returns.
- **Correlation Matrix**: Created a heatmap to analyze inter-stock return correlations.
- **Significant Drop Detection**: Pinpointed the worst one-day drop across all stocks.
- **Volume Analysis**: Compared average trading volumes across companies.
- **Time-Series Trends**: Plotted yearly average adjusted closing prices for selected companies (e.g., AAPL, MSFT).

## 📌 Sample Visuals

- 📊 Bar plots for average returns and volatility  
- 🔥 Heatmap showing return correlations  
- 📉 Time series plots for long-term trends


The dataset includes fields:
- `Date`, `Ticker`, `Open`, `High`, `Low`, `Close`, `Adj Close`, `Volume`

> The dataset was processed into ~25,000 rows across 10 stocks and ~2,500 trading days.

## 🚀 Run the Notebook

👉 [Open in Google Colab](https://colab.research.google.com/your-link-here)  
*Make sure to upload `stockmarket.csv` to run the notebook.*


