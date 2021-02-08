# Predict_CLTV_with_linear_regression

## Introduction

### CLTV
**Customer Lifetime Value (CLTV)** represents the total amount of money a customer is expected to spend in a business during his/her lifetime. This is an important metric to monitor because it helps to make decisions about how much money to invest in acquiring new customers and retaining existing ones.

### Dataset
For this analysis I am using a public dataset from **UCI Machine Learning Repositiry**, which can found [here](http://archive.ics.uci.edu/ml/index.php). This dataset contains information on transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Motivation
As a data scientist working in marketing, I find it quite challenging to combine a few fields together like marketing, machine learning and statistics, and produce insights, which make sense. I want to show an application of machine learning in marketing, particularly, in defining and predicting CLTV. 

## Getting started
You need an installation of Python, plus the following libraries:
* numpy
* pandas
* matplotlib.pyplot
* seaborn
* sklearn

## Summary and key findings
* Based on the data analysis, we found that the repeat customers tend to make about 12 purchases or less within a year and the majority of repeat customers tend to make a purchase every 12 to 50 days
* We predicted 3 months CLTV for customers of the online retail using linear regression
* R-squared value for the test set is 0.71, which is not great but it is a good benchmark to try other regression models such as Epsilon-Support Vector Regression and Random Forest Regressor
* By knowing CLTV, we can develop positive ROI strategies and make decisions about how much money to invest in acquiring new customers and retaining existing ones.
