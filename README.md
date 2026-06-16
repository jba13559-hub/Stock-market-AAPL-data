# Stock Price Prediction Using Machine Learning

## Project Overview
This project predicts Apple's next-day closing stock price using historical stock market data and machine learning techniques.

## Dataset
Historical stock data was collected using the Yahoo Finance API through the yfinance library.

Features:
- Open
- High
- Low
- Volume

Target:
- Next Day Closing Price

## Data Collection
Data was downloaded using:

```python
import yfinance as yf
