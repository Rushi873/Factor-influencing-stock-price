# Linear Regression Models for Economic Terms, Market Terms, and Foreign Trade

This repository contains Python code for building linear regression models to predict stock prices based on various economic, market, and foreign trade factors. Three separate models are implemented and described here: Economic Terms, Market Terms, and Foreign Trade.

## 1. Economic Terms Linear Regression Model

### Description:
This model predicts stock prices using economic indicators such as national debt growth, government debt as a percentage of GDP, inflation rate, GDP, unemployment rate, and more. It leverages the Ridge regression algorithm to train on historical data.

### Code Files:
- `Predictive_Model_economic_terms.py`: Contains the Python code for building and evaluating the LR model for Economic Terms.
- `Economic_terms`: Sample dataset containing historical economic indicators for US.

### Dependencies:
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, yahoo_fin, yfinance, sklearn

### How to Use:
1. Ensure all dependencies are installed.
2. Run `Predictive_Model_economic_terms.py` to train the model and generate predictions.
3. Adjust parameters or add more features as needed for further experimentation.

## 2. Market Terms Linear Regression Model

### Description:
This model predicts stock prices based on market-related factors such as Truck sales, Housing starts, Durable goods order, Retail sales and more. Similar to the Economic Terms model, it uses Ridge regression for training and prediction.

### Code Files:
- `Predictive_Model_Market_terms.py`: Contains the Python code for building and evaluating the LR model for Market Terms.
- `Market_terms`: Sample dataset containing historical market-related indicators for US.

### Dependencies:
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, yahoo_fin, yfinance, sklearn

### How to Use:
1. Ensure all dependencies are installed.
2. Run `Predictive_Model_Market_terms.py` to train the model and generate predictions.
3. Adjust parameters or add more features as needed for further experimentation.

## 3. Foreign Trade Linear Regression Model

### Description:
This model focuses on predicting stock prices using foreign trade indicators such as export, import, US foreign direct investment, Trade as percentage of GDP and more. It follows the same methodology as the other models, employing Ridge regression for training and prediction.

### Code Files:
- `Predictive_Model_foreign_trades.py`: Contains the Python code for building and evaluating the LR model for Foreign Trade.
- `Foreign_trade`: Sample dataset containing historical foreign trade indicators for US.

### Dependencies:
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, yahoo_fin, yfinance, sklearn

### How to Use:
1. Ensure all dependencies are installed.
2. Run `Predictive_Model_foreign_trades.py` to train the model and generate predictions.
3. Adjust parameters or add more features as needed for further experimentation.

## Conclusion:
These linear regression models serve as basic frameworks for predicting stock prices based on different sets of factors. They can be further refined, optimized, and customized based on specific requirements and domain knowledge. The main get away is that only using few terms, we can obtain how the stock price is moving.

