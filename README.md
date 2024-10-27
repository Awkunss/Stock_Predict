# Stock_Predict_LSTM_CNN

This project involves analyzing and predicting stock market data, focusing primarily on Apple Inc. (AAPL) and several other major technology stocks. It utilizes historical stock data to answer specific analytical questions and applies deep learning models for stock price prediction.

## Files and Their Descriptions

### 1. `AAPL.csv`
This file contains historical stock price data specifically for Apple Inc. (AAPL). It includes various attributes such as date, opening price, closing price, high, low, and volume, allowing for a detailed analysis of the stock's performance over time.

### 2. `stock_data.csv`
This file holds historical stock price data for multiple technology companies, including:
- **AAPL** (Apple Inc.)
- **GOOG** (Alphabet Inc.)
- **MSFT** (Microsoft Corporation)
- **AMZN** (Amazon.com Inc.)

The data includes attributes similar to those in the `AAPL.csv` file and enables comparative analysis between these major stocks.

### 3. `stock_market_analysis.ipynb`
This Jupyter Notebook performs an in-depth analysis of the stock market data with the following questions addressed:
1. **What was the change in price of the stock over time?**
   - Analyzes price trends and fluctuations for each stock.
2. **What was the daily return of the stock on average?**
   - Calculates average daily returns to assess performance.
3. **What was the moving average of the various stocks?**
   - Computes moving averages to identify trends and smoothing effects in stock prices.
4. **What was the correlation between different stocks?**
   - Evaluates the correlation coefficients between the stocks to understand their relationships.
5. **How much value do we put at risk by investing in a particular stock?**
   - Analyzes risk by assessing volatility and value at risk (VaR) for each stock.

### 4. `prediction.ipynb`
This Jupyter Notebook focuses on predicting stock prices using two deep learning models:
- **1D Convolutional Neural Network (1D CNN)**
- **Long Short-Term Memory (LSTM)**

It includes the process of preparing the data for training, defining the models, training them on historical stock data, and evaluating their performance.

## Requirements

To run the analysis and prediction scripts, ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `datetime`
- `matplotlib`
- `seaborn`
- `pandas_datareader`
- `yfinance`
- `tensorflow` or `pytorch` (for model prediction)
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn pandas_datareader yfinance tensorflow scikit-learn
