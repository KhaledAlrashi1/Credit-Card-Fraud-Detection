# Credit Card Fraud Detection

## Overview
The project uses machine learning to develop a model that extract patterns from credit card transactions, enabling it to distinguish between legitimate and fraud activities. 

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. 

It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, there are not provided the original features and more background information about the data.

## Models
- Various models were trained, including RandomForestClassifier, AdaBoostClassifier, CatBoostClassifier, SVM, LGB, XGB
- Cross-Validation was performed on the LGBM Classifier. 
