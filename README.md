# PREDICTING CREDIT RISK (WIP)

Loans are an essential part of modern society.  Arround the world  people borrow money to buy a home, car, travel, open a business, etc.  Loans are an opportunity but at the same time a challenge for banks.  On one hand loans create revenue with the interest regenerated, on the other hand, they create risk that borrowers won't repay loans and banks will loose money.  


## Business Case

PureLending is a financial institution with more than 30 years in the market.  It relies in measures like income, credit scores, and collateral assets to asses lending risk.  Through the years, the company has experimented a rise in default loans.  In the previous year default loans added $34M. The company has decided to address the issue and have hired a consulting firm to recommend the best strategy moving forward.  The firm has recommended to explore using machine learning to asses credit risk.

## Purpose

The purpose of this study is to build several machine learning models employing different techniques and compare them to recommend whether PureLending should use them to predict credit risk.  


## Overview of Approach

* Scikit-learn, a python library was used to built several classification models to help us predict credit risk. Then, the best performing one was selected.

* Ensemble and resample methods were used when building the models.

* Accuracy Score, recall, precision, and F1 socre are interpreted to compare among the six machine learning models and recommend whether or not we can use one to predict credit risk.


## Results
 
* Ada Boost is the model that performed the best.

* Eventhough, the accuracy score is 93%, the overall f1 score is low so this model is not recommended to to predict credit risk. It is recommended to use other methods to improve the model over time.

High Risk Loan Application

<img src= "https://github.com/NataliaVelasquez18/credit-risk/blob/main/Resources/summary.png" width="750" height="250" />


