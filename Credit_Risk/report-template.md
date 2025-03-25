# Module 12 Report Template

## Overview of the Analysis

For this project, I analyzed a dataset containing financial information to predict whether a loan would be approved (loan_status). The dataset included details such as loan size, interest rates, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

The main goal was to determine the best machine learning model for predicting loan approvals. To do this, I followed a structured process:

Data Preparation: Standardized the numerical features to ensure consistency.

Model Selection: Tested two models—Logistic Regression and Random Forest Classifier.

Evaluation: Compared the models using accuracy, precision, and recall scores to determine their effectiveness.

## Results

Logistic Regression Model
Accuracy: 99.47%

Precision: 87.25%

Recall: 97.79%

Random Forest Classifier
Accuracy: 99.26%

Precision: 87.02%

Recall: 90.34%

## Summary

Between the two models, Logistic Regression performed slightly better, especially in terms of recall. This means it was better at correctly identifying approved loans, making it a safer choice when false rejections need to be minimized.

On the other hand, if the goal was to minimize false positives (incorrectly approving a loan), then precision would be more important—but both models had similar precision scores.

Overall, I’d recommend Logistic Regression for this task because it does a great job of capturing approved loans while maintaining high accuracy.