# Credit Risk Analysis: Utilizing machine learning to assess credit risk

## Overview

This project takes on the challenge of assessing **credit risk** by using machine learning algorithms on the `LoanStats_2019Q1.csv` data to determine whether individuals are at low or high risk for loans. For this project, these are the following machine learning models/algorithms used to predict credit risk.

To determine which is the most accurate model at predicting which loans are a high risk the data will be undersampled, oversampled and a combination of both. 

## Results

**Naive Random Oversampling**	
  - Balanced accuracy test score: **67%** | 67% accuracy of model
  - high_risk score: **0.01**
  - recall score: **61%** sensitivity 
  
**SMOTE**
  - Balanced accuracy test score: **66%** | 66% accuracy of model
  - high_risk score: **0.01**
  - recall score: **69%** sensitivity
  
**Undersampling**
  - Balanced accuracy test score: **66%** | 66% accuracy of model
  - high_risk score: **0.01** 
  - recall score: **40%** sensitivity
  
**Combination**	
  - Balanced accuracy test score: **54%** | 54% accuracy of model
  - high_risk score: **0.01**
  - recall score: **57%** sensitivity 

**Balanced Random Forest Classifier**	
  - Balanced accuracy test score: **76%** | 76% accuracy of model
  - high_risk score: **0.03**
  - recall score: **88%** sensitivity 

**Easy Ensemble AdaBoost Classifier**	
  - Balanced accuracy test score: **93%** | 93% accuracy of model
  - high_risk score:**0.09** 
  - recall score: **94%** sensitivity 

## Summary
Out of the six machine learning models used on the loan data for **credit risk**, the first four models are not as effective as the accuracy score is not as high in comparison to the **ensemble classifiers**. The most accurate model was **Easy Ensemble AdaBoost Classifier** as it is the most effective since it has the highest score for `high_risk` loans. 
