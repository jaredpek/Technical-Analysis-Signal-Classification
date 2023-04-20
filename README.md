# Trading Signals with Technical Indicators and Machine Learning

## Problem Definition
Build a machine learning model to classify buy and sell signals for AAPL stock using technical indicator data on SMA, EMA, MACD and RSI.

## Getting this Notebook
````
git clone https://github.com/jaredpek/Technical-Analysis-Signal-Classification
````

## Dataset Used
- Yahoo Finance daily AAPL stock price from 1 January 2015 to 31 December 2019
  - date = Date of trading day
  - open = Price of the first trade of the day
  - close = Price of the last trade of the day
  - adjclose = Final close price after accounting for corporate actions
  - low = Minimum trade price of the day
  - high = Maximum trade price of the day
  - volume = Number of shares transacted on the day
  - ticker = 'AAPL' ticker

## Models Used
- Random Forest Classifier
- Decision Tree Classifier
- Stochastic Gradient Descent Classifier
- **Logistic Regression**

## Conclusion
- LogisticRegression was the best out of the 4 models to classify buy and sell signals based on provided technical indicators, with a very high prediction accuracy of 0.956.
- Tree-based models are more prone to overfitting, hence we must use hyperparameter tuning to mitigate it.

## Disclaimer
This notebook is best viewed using JupyterNotebook or VisualStudioCode as plotly charts are unable to render via github's online notebook view.
