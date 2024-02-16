# Module 20 - Evaluate a model based on loan risk
---
##  Analysis Overview

* This analysis is designed for any `financial institution` to  manage loans that are at risk of default, and mitigate possible losses. `

* The financial information was based on data gathered on over 77,000 loans. The task is to predict which loans are at risk of default. The `7 measures`  below are:
  - loan_size
  - interest_rate
  - borrower_income
  - debt_to_income
  - num_of_accounts
  - derogatory_marks
  - total_debt

* There were several stages of machine learning processes as the analysis was prepared. They included: splitting data into training and testing sets, and two `LogisticRegression` models were performed: the original data, and that data resampled.
---
## Results

* Machine Learning Model 1: Logistic Regression Model with the Original Data:
  * Accuracy: 0.99
  * Precision: 0.99
  * Recall: 0.99

* Machine Learning Model 2: Predict a Logistic Regression Model with Resampled Training Data
  * Accuracy: 0.99
  * Precision: 0.99
  * Recall: 0.99
---
## Summary

The summary results do not provide enough granularity in using a weighted average for the accuracy.The data suggest that the original data's model predicted 1% more accurately in regards to high-risk loans. This metric is the deciding factor for determining which model to use. Having that additional reduction in bad loans is material.

--- 
Author: Adrian Santos 
Updated: 2024-02-15