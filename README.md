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
# FB Prophet

### Installation in R
Prophet is a CRAN package so you can use install.packages.
```
install.packages('prophet')
```
After installation, you can get started!

Experimental backend - cmdstanr
You can also choose an experimental alternative stan backend called cmdstanr. Once you've installed prophet, follow these instructions to use cmdstanr instead of rstan as the backend:


### We recommend running this in a fresh R session or restarting your current session
```
install.packages(c("cmdstanr", "posterior"), repos = c("https://mc-stan.org/r-packages/", getOption("repos")))
```
## If you haven't installed cmdstan before, run:
```
cmdstanr::install_cmdstan()
```
## Otherwise, you can point cmdstanr to your cmdstan path:
```
cmdstanr::set_cmdstan_path(path = <your existing cmdstan>)
```
### Set the R_STAN_BACKEND environment variable
```
Sys.setenv(R_STAN_BACKEND = "CMDSTANR")
```
### Windows
On Windows, R requires a compiler so you'll need to follow the instructions provided by rstan. The key step is installing Rtools before attempting to install the package.

If you have custom Stan compiler settings, install from source rather than the CRAN binary.

### Installation in Python - PyPI release
Prophet is on PyPI, so you can use pip to install it.
```
python -m pip install prophet
```
From v0.6 onwards, Python 2 is no longer supported.
As of v1.0, the package name on PyPI is "prophet"; prior to v1.0 it was "fbprophet".
As of v1.1, the minimum supported Python version is 3.7.
After installation, you can get started!

### Anaconda
Prophet can also be installed through conda-forge: conda install -c conda-forge prophet.

Installation in Python - Development version
To get the latest code changes as they are merged, you can clone this repo and build from source manually. This is not guaranteed to be stable.
```
git clone https://github.com/facebook/prophet.git
cd prophet/python
python -m pip install -e .
```
By default, Prophet will use a fixed version of cmdstan (downloading and installing it if necessary) to compile the model executables. If this is undesired and you would like to use your own existing cmdstan installation, you can set the environment variable PROPHET_REPACKAGE_CMDSTAN to False:
```
export PROPHET_REPACKAGE_CMDSTAN=False; python -m pip install -e .
```
### Linux
Make sure compilers (gcc, g++, build-essential) and Python development tools (python-dev, python3-dev) are installed. In Red Hat systems, install the packages gcc64 and gcc64-c++. If you are using a VM, be aware that you will need at least 4GB of memory to install prophet, and at least 2GB of memory to use prophet.

### Windows
Using cmdstanpy with Windows requires a Unix-compatible C compiler such as mingw-gcc. If cmdstanpy is installed first, one can be installed via the 
```
cmdstanpy.install_cxx_toolchain command.
```
