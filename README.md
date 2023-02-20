# Stock-Market-Predictor
Welcome to the README file for our stock market predictor project!

<h2>Project Overview</h2>
Our goal for this project is to develop a machine learning model that can accurately predict stock prices for a given company. 
We will be using historical stock price data and various technical indicators to train and test our model.

<h2>Data</h2>
We will be using historical stock price data from S&P 500. 
The data will include various attributes such as date, open price, close price, high price, low price, volume, dividends, stock splits.

<h2>Methodology</h2>
We will be using a supervised learning approach to train our model. Our dataset will be split into training and testing sets.
We will be using random forests as a machine learning algorithm to train our model. 
We will tune the hyperparameters of each algorithm to find the best performing model.

<h2>Evaluation</h2>
We will create 1 column name target to help us evaluate the performance
We will evaluate the performance of our model using the code "precision_score(predictions["Target"], predictions["Predictions"])"where "Predictions" is the output we got and "Target" is the output needed. 
We will compare the performance of each algorithm and choose the best performing model.

<h2>Dependencies Used</h2>

pandas

numpy

seaborn

matplotlib
