# Predicting-Stock-Prices
### Time series analysis
Time series analysis is a specific way of analyzing a sequence of data points collected over an interval of time. In time series analysis, analysts record data points at consistent intervals over a set period of time rather than just recording the data points intermittently or randomly. However, this type of analysis is not merely the act of collecting data over time. 

What sets time series data apart from other data is that the analysis can show how variables change over time. In other words, time is a crucial variable because it shows how the data adjusts over the course of the data points as well as the final results. It provides an additional source of information and a set order of dependencies between the data. 

Time series analysis typically requires a large number of data points to ensure consistency and reliability. An extensive data set ensures you have a representative sample size and that analysis can cut through noisy data. It also ensures that any trends or patterns discovered are not outliers and can account for seasonal variance. Additionally, time series data can be used for forecasting—predicting future data based on historical data.

### About
This project focuses on the prediction of the prices of Bitcoin, the most in-demand crypto-currency of today’s world. We predict the prices accurately by gathering data available at yahoo finance while taking various hyper-parameters into consideration which have affected the bitcoin prices until now.

### ML Models Used:
Regression Models
Linear Regression with various penalties
Polynomial Regression
Bayesian Regression
ARIMA Models
AR
ARMA
ARIMA
VAR Model
Python Dependencies:
pandas
numpy
requests
matplotlib
statsmodels

### Install Dependencies (requirements.txt)
```
pip install -r requirements.txt
```
OR
```
pipenv install --ignore
pipenv shell
How to Run
cd <PROJECT ROOT DIRECTORY>
python <filename>.py
```
