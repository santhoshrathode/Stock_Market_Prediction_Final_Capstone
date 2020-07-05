# Stock_Market_Prediction_Final_Capstone_Project

Machine Learning Engineer Nanodegree
Capstone Project

Stock Price Prediction using Machine Learning

This project is about predicting the stock price using best Machine Learning Models and I am going to predict stock price of Starbucks and ATT.
Used Decision Tree Regression model for the benchmarking and Support Vector Regressor (SVR), Random Forest and Long Short-Term Memory (LSTM) as solution models.
I will compare these models and finalize the best model for future prediction. Used RMSE and R2 square as metrics to compare.

Datasets collection

Stock market historical data can be found from many places, but I choose to download from
https://finance.yahoo.com/. There are many web scraping API’s available to get the data based on
selected dates. I downloaded CSV files excluding recent 2020 data because of COVID-19 market crash. I
understand that model prediction is not based only on historical data, it also includes various factors like
news, sentiments and etc. So, I am going to analyze 8 years of historical data from 2011-12-30 to 2019-
12-30.

Metrics:
I am going to use two most popular metrics methods.
1. Root Mean Square Error (RMSE)
2. R-Squared (R2)

Project Design
      
      Project will be completed on the Jupyter Notebook with python language. This project requires pandas, numpy, scikit-learn, keras, matplotlib and seaborn libraries so I will be using importing this before I start. Development code will found in stock_prediction.ipynb notebook.

Machine Learning Work Flow:

      Data Collection, Exploration and Preprocessing

      Data visualization

      Feature selection/Technical indicator selection

      Normalize the data

      Split the data into Train, Test and Validation sets

      Implementing model prediction and evaluation

      Finally, compare the result with benchmark model.

Project structure:

      Machine Learning Engineer Nanodegree proposal is proposal.pdf

      Data can be found in data directory.

      Complete development code is in Final_Capstone_Stock_Prediction.ipynb notebook.

      Machine Learning Engineer Nanodegree Proejct Report is Report.pdf
      
 Example projects can be found in Udacity GitHub.
 
      https://github.com/udacity/sagemaker-deployment
      
      https://github.com/udacity/ML_SageMaker_Studies
      
