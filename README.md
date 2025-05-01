# Quantitative_Stock_Price_Prediction_Platform

This project analyzes Netflix's stock performance over a 4-year period using Python data science tools. The analysis includes:

1. Data Collection
Data is downloaded using Yahoo Finance (yfinance) and FRED (Federal Reserve API).

The stock data includes daily adjusted closing prices from January 1, 2020 to March 31, 2024.

2. Descriptive Statistics
Basic statistics like mean, skewness, kurtosis are calculated on Netflix's adjusted close prices.

Histograms and KDE plots show how prices are distributed.

3. Daily Returns & Moving Averages
Computes daily percentage returns.

Calculates 20-day and 50-day moving averages to track momentum and trends.

4. Visualizations
Line plots of adjusted closing price with moving averages.

Comparison with competitors: Amazon (AMZN), Disney (DIS), and Warner Bros Discovery (WBD).

All stock prices are normalized to visualize relative performance.

5. Feature Engineering
Adds technical indicators like:

Momentum = 20D MA – 50D MA

Volatility = 30-day rolling std. of returns
