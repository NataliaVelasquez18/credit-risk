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


1. High Risk Loan Application
2. 
<img src= "https://github.com/NataliaVelasquez18/credit-risk/blob/main/Resources/summary.png" width="750" height="350" />


2. Low-Risk Application Loan

add

### LOGISTIC REGRESSION


#### RESAMPLING: 

Class imbalance is a common problem in classification. It occurs when one class is much larger than the other class.  In this scenario, a large number of credit card aplications are of low risk of default, and only a small number are high risk. For example, let's say that out of 100,000 credit card loan applications, 50 default and the rest are repaid. The pronounced imbalance between the two classes (high risk of default and low risk default) can cause machine learning models to be biased toward the majority class. The following techniques address this issue.

##### Oversampling

* Naive Random Oversampling: 

In random oversampling, instances of the minority class are randomly selected and added to the training set until the majority and minority classes are balanced. The data is trained using Logistic Regression.


As we can see the precision and recall are very different and might seem contradictory.


The precision of the model is almost zero.  From the loan applications that our model predicted high risk how likely is that the model is right. It fails at its job with a success rate of 0%. 

The recall is 0.74 a indicates that from every application that was actually high risk, the model was accurate 74% of the time. 

To balance precision and recall, F1-Score is used.  An F-1 score of 0.02 is considered low.  Therefore, there is a pronounced imbalance between sensitivity and precision.
Accuracy score is 65%


The F1 score or harmonic mean is used as a summary statistic of precision and sensitivity.


Even though the accuracy score of 65% this metric is not always the best metric. 



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

xxddd






## Summary
