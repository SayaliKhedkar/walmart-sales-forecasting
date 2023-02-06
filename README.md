# walmart-sales-forecasting
Complete project of walmart 
# walmart-sales-forecasting-with-Machine-Learning
- Complete Project of Data Analysis And  prediction on 'walmart sales forecasting' using Python Programming And Machine Learning.
- For Visuals we use the Python libraries like Matplotlib & Seaborn in Anaconda(Jupyter Notebook).

![5654e2642100003e005ab97f](https://user-images.githubusercontent.com/109957315/217051867-8ac0e2a2-973b-4067-88ca-1c995525953c.jpg)



## Introduction 
- Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets (also called supercenters), discount department stores, and grocery stores in the United States, headquartered in Bentonville, Arkansas.
- The company was founded by Sam Walton and James "Bud" Walton in nearby Rogers, Arkansas in 1962 and incorporated under Delaware General Corporation Law on October 31, 1969. It also owns and operates Sam's Club retail warehouses.
## Context
- Walmart Recruiting - Store Sales Forecasting downloaded from https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting
## Aim of Walmart Sales Forecasting
- Sales forecasting or predicting the future is very important for every business. 
- It is used for companies to making plans for high revenue, keep costs lower and high efficiency.
- Companies made short-term and long term future planning as per forecasting data.
- Based on past data with some assumption which predict future trends and draw their budget accordingly.
- There are many factors like Market changes, Product changes, Economic conditions, season changes, etc; which impact to forecast of sales. Companies can make a plane to meet future demands and make improvements in their sales by keeping in mind these various factors.
## Objective
- Predict the sales for each department using historical markdown data from the Walmart dataset containing data of 45 Walmart stores.
- The purpose of this project is to develop a predictive model and find out the sales of each product at a given Walmart store.
- Predict which departments are affected with the holiday markdown events and the extent of impact.
- Perform dimensionality reduction to improve prediction error by shrinkage in order to reduce overfitting.

## Dataset:
- This dataset consist of Records:421570 and Features:16

## Python Libraries used in Project
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- import warnings
  warnings.filterwarnings('ignore')

## Data Preparation/Cleaning
1) As the dataset from kaggle was not very suitable for data analysis, we had to change the format of some data in the dataset. We also had to do separate data preparation for exploratory analysis and machine learning.
2) Some of our data preparation were:
3) Change NaN values to the integer 0.
4) Cleaning the textual data into a form that would be suitable for Python's Jupyter Notebook.
5) Encoding the categorical variables so that it can be fit into the regression models later.
6) Separating the data into Predicted and Target variables.
7) Separating the data into training and testing sets (Training Sets: Testing Sets = 70% : 30%)

## Use of Regressor in the Machine Learning Models.
Regression is a supervised machine learning technique which is used to predict Continuous values. The ultimate goal of the regression algorithm is to plot a best-fit line or a curve between the data.
Machine Learning Regression is a technique for investigating the relationship between independent variables or features and a dependent variable or outcome. It's used as a method for predictive modelling in machine learning, in which an algorithm is used to predict continuous outcomes.
There is no categorical Values in the dataset so, will not use the Classifiers in the Machine Learning Models.
That's Why we use Regressor Model in this Dataset.

## ML Model Used in project:
1) Decision Tree =89.35%
2)	Random Forest	=94.34%
3)	XGBoost	=91.68%
4)	KNN	=59.24%
## Conclusion
Following inferences and conclusions can be drawn from the the analysis of the data:
- Type 'A' stores are more popular than 'B' and 'C' types.
- Type 'A' stores outclass the 'B' and 'C' types in terms of size and the avergae weekly sales.
- Weekly Sales are affected by the week of year. Holiday weeks witnessed more sales than the non-holiday weeks. Notables are Thanksgiving and Christmas weeks.
- Size of the store is a major contributing factor in the weekly sales.
- Sales are also dependent on the department of the store as different departments showed different levels of weekly sales.
- Among the trained models for predicting the future sales, Random Forest Machine with tuned hyperparameters performs the best.
