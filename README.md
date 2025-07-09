📊 SMA Crossover Strategy Jupyter Notebook

This repository contains a Jupyter Notebook that demonstrates a Simple Moving Average (SMA) Crossover Strategy used for analyzing and backtesting stock price trends.

📁 File Included

`sma-crossover.ipynb` — Main notebook implementing the SMA Crossover Strategy using Python and libraries such as `pandas`, `matplotlib`, and `yfinance`.

📌 What is SMA Crossover?

SMA Crossover is a technical analysis strategy that uses two different time-frame moving averages to identify buy and sell signals in a stock’s price.

Short-Term SMA (e.g., 20-day): Captures recent price trends.
Long-Term SMA (e.g., 50-day): Captures longer-term price movement.
A Buy signal is generated when the Short SMA crosses above the Long SMA (Golden Cross).
A Sell signal is generated when the Short SMA crosses below the Long SMA (Death Cross).

⚙️ Features

Fetch historical stock data using Yahoo Finance API via `yfinance`.
Calculate and plot:
  -Short-term and long-term SMAs
  -Actual stock prices
  -Buy/Sell crossover signals
  -Visualize strategy performance on real stock data
