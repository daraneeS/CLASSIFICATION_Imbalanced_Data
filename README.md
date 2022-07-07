# CLASSIFICATION: IMBALANCED DATA 

# Credit Card Fraud Detection

## Overview

* **Classification** project on **Imbalanced dataset**
* Credit card dataset from Kaggle, which has about 1.5 million rows
* Sampling 10% of the original dataset
* **Machine Learning Models** 
* Logistic Regression 
* Decision Tree Classification
* Random Forest Classification
* XGBoost Classification


## Visualization

![png](images/fraud1_category_most_use.png)

![png](images/fraud0_category_most_use.png)

![png](images/fraud1_across_states.png)

![png](images/fraud1_top10_states.png)

![png](images/states_fraud_distribution.png)

![png](images/states_fraud_distribution2.png)

![png](images/amount_boxplot.png)

![png](images/fraud1_transaction_date_amt.png)



![png](images/fraud1_merchants_most_use.png)

![png](images/merchants_latitude_longtitude.png)

![png](images/card_holders_latitude_longtitude.png)

![png](images/card_holder_age.png)

## Models Prediction
* Total Testing samples are 24,082 transactions
* True Fraud are 132 Transactions
* The rest are legit Transactions


## Logistic Regression
* 132 Frauds walk away: 2 clients get angry for stopping transactions.

![png](images/logistic_regression_base.png)

* 37 Frauds walk away: 413 clients get angry for stopping transactions.

![png](images/logistic_regression_weight1.png)

* 34 Frauds walk away: 1663 clients get angry for stopping transactions.

![png](images/logistic_regression_weight2.png)

* 3 Frauds walk away: 13,934 clients get angry for stopping transactions.

![png](images/logistic_regression_gridcv.png)


## Decision Tree

* 53 Frauds walk away: 29 clients get angry for stopping transactions.

![png](images/decision_tree_base.png)

* 54 Frauds walk away: 30 clients get angry for stopping transactions.

![png](images/decision_tree_balanced.png)

* 13 Frauds walk away: 1939 clients get angry for stopping transactions.

![png](images/decision_tree_balanced_maxdepth.png)


## Random Forest

* 64 Frauds walk away: 6 clients get angry for stopping transactions.

![png](images/random_forest_base.png)

* 67 Frauds walk away: 10 clients get angry for stopping transactions.

![png](images/random_forest1.png)

* 64 Frauds walk away: 8 clients get angry for stopping transactions.

![png](images/random_forest2.png)

* 34 Frauds walk away: 66 clients get angry for stopping transactions.

![png](images/random_forest2_gridcv.png)


## XGBoost

* 50 Frauds walk away: 9 clients get angry for stopping transactions.

![png](images/xgboost_base.png)

* 32 Frauds walk away: 40 clients get angry for stopping transactions.

![png](images/xgboost_weight100.png)

* 31 Frauds walk away: 61 clients get angry for stopping transactions.

![png](images/xgboost_weight1000.png)

## Futher Improvement
- Grid Search CV


