# Predicting churn rate of customers


## Introduction:

The goal of the project is to predict the churn rate of Sparkify. The dataset provided is 12GB. In order to load and manipulate this large data set, we will have to use Amazon Web Services EMR.
 
## Table of Contents:

- [Code in Python]( https://github.com/Pooja16/Predicting-Offer-Success-for-Starbucks/blob/master/Starbucks_Capstone_notebook.ipynb)
This python file has all the code that was used to put through the entire analysis. 

- [Dataset]( s3n://udacity-dsnd/sparkify/sparkify_event_data.json)
This includes the dataset hosted on Amazon s3 that was used for the analysis.

## Summary of results of analysis:
	
The goal of my analysis is to find the customers who are most likely to cancel their membership and churn out. Predicting the customers who might cancel their membership will enable the company to send out special offers and make extra efforts in trying to retain their precious membership. Churn rate predictions generally saves the company millions of dollars.

I used multiple classifiers to predict response to an offer. The classifiers I used are Logistic Regression, Random Forest and Gradient Boosting Classifier. 

Out of these classifiers, Random Forest Classifier has the best performance in terms of both accuracy and area under ROC curve.

## Software:

Python Anaconda 3.7
Install anaconda [here](https://www.anaconda.com/distribution/)

## Installation:

Jupyter Notebook
Open Anaconda prompt and type the following:
```
conda install jupyter
jupyter notebook
```












