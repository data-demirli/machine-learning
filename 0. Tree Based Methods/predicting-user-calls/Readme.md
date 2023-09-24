# Predicting User Calls
* (Predicting whether or not user will call customer support within the next 14 days)

## Summary:
**Dataset:** Two datasets; train_set.csv contains user identifiers with features relating to their recent gameplay, customer_country.csv contains user identifiers with corresponding country location  
**Model:**  XGBoost classification model  
**Particulars:** Hyperparameter tuning, imbalanced dataset, ROC curves, developed function which allows n-fold cross validation with over/under sampling applied; sampling applied only to the training sets

## [Table of Contents:](https://github.com/data-demirli/machine-learning/blob/main/0.%20Tree%20Based%20Methods/predicting-user-calls/predicting_user_calls.ipynb)

* Section 1 - Exploring Datasets
* Section 2 - Useful Functions
* Section 3 - Data Preparation
* Section 4 - Feature Comparison
* Section 5 - Hyperparameter Tuning & Feature Selection
* Section 6 - Performance Metrics
* Section 7 - Final Model
* Section 8 - Feature Importance