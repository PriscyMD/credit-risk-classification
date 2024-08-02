# Module 12 Report

## Overview of the Analysis

In this analysis, we aimed to evaluate the performance of a machine learning model in predicting loan status, specifically identifying healthy loans and high-risk loans. The data consisted of financial information related to loan applications, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. Our goal was to predict the loan status based on this information.

The loan status variable had two categories: healthy loans (0) and high-risk loans (1). The value_counts of the loan status variable showed an imbalance between the two categories, with healthy loans being the majority.

We went through the stages of data preprocessing, feature selection, and model training and evaluation. We employed a logistic regression algorithm to predict the loan status.

## Results

Here are the accuracy, precision, and recall scores of the machine learning model:

Machine Learning Model 1 (Logistic Regression):
Accuracy: Not provided
Precision: 99.0
- Healthy Loans (0): 1.00
- High-Risk Loans (1): 0.85
Recall:
- Healthy Loans (0): 0.99
- High-Risk Loans (1): 0.91

## Summary

Based on the results, the logistic regression model performs exceptionally well in predicting healthy loans, with a precision and recall of 1.00 and 0.99, respectively. However, its performance is not as strong for high-risk loans, with a precision of 0.85 and recall of 0.91.

Considering the problem we are trying to solve, it is more important to predict high-risk loans
