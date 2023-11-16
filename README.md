# Credit Risk Prediction Project

## Overview

This project focuses on credit risk prediction using machine learning models based on historical lending activity data from a peer-to-peer lending services company. The primary goal is to identify the creditworthiness of borrowers and predict whether a loan is healthy or has a high risk of default.

## Dataset

The dataset used in this project contains financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The target variable is the "loan_status" column, where 0 indicates a healthy loan and 1 indicates a high-risk loan.

## Analysis Stages

1. **Data Loading and Exploration:** Reading the dataset, separating features and labels, and exploring label balance.
2. **Model Training (Original Data):** Building a logistic regression model with the original data and evaluating its performance.
3. **Resampling (Random Oversampling):** Using the imbalanced-learn library to resample the training data for better model performance.
4. **Model Training (Resampled Data):** Building a logistic regression model with the resampled data and evaluating its performance.

## Recommendations

The logistic regression model trained on resampled data performs better in terms of balanced accuracy, precision, and recall compared to the model trained on the original data. The choice of the model depends on the problem context, and stakeholders should consider business objectives and priorities.

