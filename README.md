# Stock-Price-Prediction-Using-Python
This File can be opened by jupytar Notebook or Google Collab
The project aimed at comparing two Machine models, Long Short-Term Memory(LSTM) and Linear Regression model(OLS)  
Steps followed to achieve results:
  - In this Project we extract closing prices data of a particular stock from Yahoo Finance APIs using Python.
  - Used data from 1 January 2020.   
  - Cleaned the data and before fitting it into the model.
  - After Data Cleaning, Scaling and removing the NaN values, was only able to use 785 closing data values, which 628 were used to train the model and 157    used to test the model. 
  - Used Data Visualization Graphs show historical perfomance of stocks.
  - I used the data to train/test the two models on a 70/30 percent data splits for both LSTM and Linear Regression Models.
  - The result for both models were impressive in predicting the stock price and the trends the stocks follows.
  - The linear Regression Model achieved superior results of more than 90% accuracy to beat LSTM model.
