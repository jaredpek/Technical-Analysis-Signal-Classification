# Trading Signals with Technical Indicators and Machine Learning

## About
This is a data science project using the Yahoo Finance AAPL Stock Price data from 1 January 2015 to 31 December 2019, and is best viewed using JupyterNotebook or VisualStudioCode the plotly charts are unable to render via github's online notebook view.

## Getting this Notebook
````
git clone https://github.com/jaredpek/Technical-Analysis-Signal-Classification
````

## Problem Definition
Build a machine learning model to classify buy and sell signals for AAPL stock using technical indicator data on SMA, EMA, MACD and RSI.

## Models Used
- Random Forest Classifier
- Decision Tree Classifier
- Stochastic Gradient Descent Classifier
- **Logistic Regression**

## Conclusion
- LogisticRegression was the best out of the 4 models to classify buy and sell signals based on provided technical indicators, with a very high prediction accuracy of 0.956.
- Tree-based models are more prone to overfitting, hence we must use hyperparameter tuning to mitigate it.
