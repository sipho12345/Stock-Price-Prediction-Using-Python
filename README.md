# Stock-Price-Prediction-Using-Python
This File can be opened by jupytar Notebook or Google Collab.
The project is aimed at comparing two Machine Learning models, Long Short-Term Memory(LSTM) and Linear Regression model(OLS)  
Steps followed to achieve results:
  - In this Project we extract closing prices data of a particular stock from Yahoo Finance APIs using Python.
  - Used data from 1 January 2020 for AAPL stock.   
  - Cleaned the data and before fitting it into the model.
  - After Data Cleaning, Scaling and removing the NaN values, was only able to use 785 closing data values, which 628 were used to train the model and 157    used to test the model. 
  - Used Data Visualization Graphs to show historical perfomance of stocks.
  - I used the data to train/test the two models on a 70/30 percent data splits for both LSTM and Linear Regression Models.
  - The result for both models were impressive in predicting the stock price and the trends the stocks follows.
  - The linear Regression Model achieved superior results of more than 90% accuracy to beat LSTM model.
  


#Historical Performance for AAPL
<img width="855" alt="Screenshot 2023-02-19 at 11 09 26" src="https://user-images.githubusercontent.com/61363539/219939163-58df4f00-006c-439f-9ce2-57d5e5ee1dd2.png">

#Results

#Training Data
<img width="975" alt="Screenshot 2023-02-19 at 11 11 52" src="https://user-images.githubusercontent.com/61363539/219939282-5dc9800c-b7e7-4290-922b-831e2f301eb6.png">

#Testing Data
<img width="995" alt="Screenshot 2023-02-19 at 11 13 00" src="https://user-images.githubusercontent.com/61363539/219939329-a7816892-a3b5-4487-939f-c84595d4639a.png">



#Linear Regression Prediction Results
<img width="914" alt="Screenshot 2023-02-19 at 11 14 35" src="https://user-images.githubusercontent.com/61363539/219939398-2f1b36c8-8790-4b13-b57c-5e8259c4650a.png">


#Long Short Term Memory Algorithm Prediction Results
<img width="928" alt="Screenshot 2023-02-19 at 11 16 54" src="https://user-images.githubusercontent.com/61363539/219939502-d7146b83-66ed-49a4-9c10-cf0951159bcf.png">

