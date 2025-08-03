# tesla-stock-price-predction-using-various-machine-learning-models
# Stock Price Prediction using Machine Learning

This project uses historical Tesla stock data (TSLA) from Yahoo Finance to predict the next-day closing price using:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## Features Used

- Open, High, Low, Close, Volume
- Moving Averages (5-day, 20-day)
- Volatility (5-day std dev of returns)
- Volume change (%)

## Models Compared

Each model is evaluated using Mean Squared Error (MSE). Predictions are visualized against actual prices.

## Libraries Required

- `yfinance`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `xgboost`

## Run the Script

```bash
pip install -r requirements.txt
python stock_price_prediction.py

