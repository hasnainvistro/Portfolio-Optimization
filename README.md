# Portfolio Optimization

# Project Overview
This project demonstrates portfolio optimization using historical financial data from various stocks. The objective is to construct an optimal portfolio that maximizes returns while minimizing risk using quantitative methods. The project employs libraries such as pandas, numpy, matplotlib, seaborn, and yfinance for data collection, analysis, and visualization.

# Table of Contents
Project Motivation
Dataset Description
Steps
1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Portfolio Optimization Techniques
5. Model Evaluation
6. Results and Insights
Future Work

# Project Motivation
The primary goal of this project is to apply portfolio optimization techniques to historical stock data, helping investors make informed decisions. By analyzing stock prices, returns, and other financial metrics, we aim to build a robust portfolio that achieves an optimal balance between risk and return.

# Dataset Description
The dataset includes historical financial data for the following tickers: AAPL, MSFT, AMZN, GOOGL, ACN, NVDA, LLY, PFE, BRK-B, V, META. The data spans one year from the start date to the end date, and includes the following attributes:
Date
Open
High
Low
Close
Adj Close
Volume
Steps

1. Data Collection
Historical financial data is collected using the yfinance library.

2. Data Preprocessing
The collected data is melted and pivoted for easier analysis and visualization.

3. Exploratory Data Analysis (EDA)
Data visualization and exploration are conducted using matplotlib and seaborn.
Stock Price Trends: Line plots for closing prices of all tickers.
Moving Averages: Calculation and plotting of 20-day and 100-day moving averages.
Volume Analysis: Bar plots for trading volume.
Daily Return Distribution: Histogram plots for daily returns of each ticker.
Correlation Heatmap: Heatmap showing the correlation between the daily returns of different tickers.

4. Portfolio Optimization Techniques
The portfolio is optimized using the Sharpe Ratio, which balances returns and volatility.

5. Model Evaluation
The model's performance is evaluated based on the Sharpe Ratio and efficient frontier analysis.

6. Results and Insights
The portfolio with the maximum Sharpe Ratio has the following characteristics:

**Expected Return: 40.62%
Volatility: 17.01%
Sharpe Ratio: 2.39**

# The optimal portfolio weights are:
AAPL: 0.12%
ACN: 16.77%
AMZN: 20.24%
BRK-B: 3.13%
GOOGL: 2.15%
LLY: 9.51%
META: 20.92%
MSFT: 12.15%
NVDA: 11.82%
PFE: 3.16%
V: 0.02%

# Future Work
1. Incorporate additional financial instruments: Bonds, commodities, and ETFs.
2. Explore advanced optimization techniques: Machine learning and deep learning methods.
3. Real-time portfolio rebalancing: Implement strategies for dynamic adjustment based on market conditions.
