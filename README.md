# Stock_Market-Predictor

# Introduction
Predict stock market using Long short-term memory (LSTM) AI algorithms. Predict long term forecast as the short-term forecast will be subjected to many inconsistencies and to predict short term variations, we need to take in account of all the news and current happenings. Overall, the outcome of this project will be to make an acceptable prediction of stock market.

We will be using time series data such as stocks (using y finance library for python) and predict the value as on the current track record and compare with Long short-term memory (LSTM).We will be applying following algorithms in python and will be using stats model for statistical comparison.Libraries which we will be using are, math, pandas_datareader, numpy, pandas and matplotlib.
Common Architecture of LSTM:
Forget Gate
Input Gate
Output Gate

# How to Use Application
First step to use this predictor is to install python based modules required by the application. In command prompt, write below line to install all the dependencies.
```
pip install requirements.txt
```
after successful installation of all file. open notebook with following command:
```
jupyter notebook
```
now set stock-ticker in cell and test_pr into notebook.
```python
ticker = 'TSLA' #here change ticker
test_pr = 0.2 # here change validation data percentage
```
after setting appropriate variable values. run complete notebook with shift+enter keys.

# Evaluation Methodology
To evaluate the accuracy of the predicted graph we can compare the predicted values with the actual data. We will feed data until 2019 and try to predict the stock till 2021 and compare it to actual data.

