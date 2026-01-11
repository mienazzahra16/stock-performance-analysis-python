# Stock Performance Analysis: AAPL vs MSFT

## Project Overview
This project provides a comparative analysis of *Apple (AAPL)* and *Microsoft (MSFT)* stock performance over the last 30 days. I focus on using statistical methods to interpret market trends.

## Features
* *Data Retrieval:* Automated data fetching from Yahoo Finance API using yfinance.
* *Data Cleaning:* Processing time-series data with Pandas.
* *Mathematical Normalization:* Implemented *Base-100 Normalization* to accurately compare growth percentages between stocks with different price scales.
* *Visualization:* Clear visual comparison using Matplotlib.

## Mathematical Approach
To ensure a fair comparison, I normalized the prices using the formula:
*Index_t = (Price_t / Price_initial) * 100*
This allows us to see the relative growth starting from a common baseline of 100.

## Key Insights
* *Microsoft (MSFT)* showed higher growth and better stability during this period compared to *Apple (AAPL)*.
* Apple experienced a significant drawdown of approximately 6% from its initial price.

## Tools Used
* *Language:* Python
* *Libraries:* Pandas, NumPy, Matplotlib, yfinance
