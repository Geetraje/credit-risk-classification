# Credit-risk-classification

# Background
This challenge uses two techniques to train and evaluate a model based on loan risk.
The dataset used (lending_data.csv), contains historical lending activity from a lending services company.
The task is to build a model that can identify the creditworthiness of potential borrowers.

# Overview of the Analysis
This analysis aims to compare two logistic regression models, one that trains with imbalanced data and one that uses random oversampling, to see the differences in their predictive performance.
The data provided consisted of details of financial loans which included loan size, interest rate, borrower's income, debt to income ratio, number of accounts, derogatory remarks and total debt.

## Stages of machine learning process used in this analysis
- Split the data into training and testing datasets
- Created and fit a logistic regression model with the original data
- Evaluated the performance of this model by the accuracy, precision, recall and F1 scores
- Resampled the data using RandomOverSampler to adjust the imbalance
- Created and fit a logistic regression model, this time using the resampled data
- Evaluated the performance of this resampled model and see how it compares to the original predictions.
- The first method used in this analysis was LogisticRegression and for the resampled version, RandomOverSampling method was used.

# Results
