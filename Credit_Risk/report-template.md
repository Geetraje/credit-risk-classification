# Credit Risk Analysis

## Overview of the Analysis

- The purpose of the analysis is to compare the performance of 2 logistic regression machine learning models. Both were used to predict the credit risk associated with financial loans.
- The data provided consisted of details of financial loans which included loan size, interest rate, borrower's income, debt to income ratio, number of accounts, derogatory remarks and total debt.
- The objective is to predict the status of the loan either as a '0'(healthy loan) or as a '1' (high-risk loan).

Stages of machine learning process used in this process
1. Split the data into training and testing datasets
2. Create and fit a logistic regression model with the original data
3. Evaluate the performance of this model by the accuracy, precision, recall and F1 scores
4. Resampled the data using RandomOverSampler to adjust the imbalance
5. Create and fit a logistic regression model, this time using the resampled data
6. Evaluate the performance of this resampled model and see how it compares to the original predictions.
7. The first method used in this analysis was LogisticRegression and for the resampled version, RandomOverSampling method was used.

## Results

* Machine Learning Model 1: Logistic Regression on Original Data
* Description of Model 1 Accuracy, Precision and Recall Scores.
- While the overall accuracy is good at 0.99,
- the healthy loans (0) have a perfect precision, recall and F1-score of 1.00,
- the scores on the high-risk loans are lacking at 0.87, 0.89 and 0.88 respectively.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
- While the overall accuracy continues to be good at 0.99,
- the healthy loans (0) have a precision, recall and F1-score of 0.99,
- the scores on the high-risk loans have significantly improved at 0.99 each.

## Summary

In this above example, Logistic Regression model trained with resampled data (Model 2) is a better fit than the one trained with original data (Model 1), especially when it pertains to predicting high-risk loans. While Model 1 is very good at predicting healthy loans with low false positives and low false negatives, Model 2 has better precision and recall scores for high-risk loans which can be helpful in overcoming financial losses for the lender.

Oversampling the dataset greatly increased the accuracy of prediction for both the healthy and high-risk loans, making it a clear choice.
