# PREDICTING CREDIT RISK

Loans are an essential part of modern society.  Arround the world  people borrow money to buy a home, car, travel, open a business, etc.  Loans are an opportunity but at the same time a challenge for banks.  On one hand loans create revenue with the interest regenerated, on the other hand, they create risk that borrowers won't repay loans and banks will loose money.  


## Business Case

PureLending is a financial institution with more than 30 years in the market.  It relies in measures like income, credit scores, and collateral assets to asses lending risk.  Through the years, the company has experimented a rise in default loans.  In the previous year default loans added $34M. The company has decided to address the issue and have hired a consulting firm to recommend the best strategy moving forward.  The firm has recommended to explore using machine learning to asses credit risk.

## Purpose

The purpose of this study is to build several machine learning models employing different techniques and compare them to recommend whether PureLending should use them to predict credit risk.  


## Executive summary



## Overview of Approach

In the study, *credit card customer data* is used.   
Python and Scikit-learn library were used to predict credit risk.  
Logistic Regression and Decision Trees methods were used to train the model.
Resampling and ensemble techniques were used  to address imbalanced data when building the models.

For the resampling technique Credit card customer data is oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Also, a combinatorial approach is presented including over- and undersampling using the SMOTEENN algorithm. 

For the ensemble technique, the  BalancedRandomForestClassifier and EasyEnsembleClassifier were used.

Balanced Accuracy Score, recall, and precision are interpreted to compare among the six machine learning models and recommend wheter or not the can be used to predict credit risk.


## Results

### LOGISTIC REGRESSION MODEL

In the next graph we can see the performance result of each model.


Pic



#### RESAMPLING: 

Class imbalance is a common problem in classification. It occurs when one class is much larger than the other class. There are techniques to address this issue.  

##### Oversampling

* Naive Random Oversampling: 

fffff

* SMOTE Oversampling:

 xx

##### Undersampling

* ClusterCentroids:

 xxx

##### COMBINATION OF OVER AND UNDER SAMPLING

* SMOTEENN:
xxx

### DECISION TREES

#### ENSEMBLE

* BalancedRandomForestClassifier:
xx

* EasyEnsembleClassifier: 

xx






## Summary
