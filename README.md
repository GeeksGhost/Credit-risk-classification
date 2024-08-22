# Credit-risk-classification

## Overview

This project involves building and evaluating a logistic regression model to predict loan statuses based on historical data. The model is trained to classify loans into two categories:
- **Healthy Loan (0)**
- **High-Risk Loan (1)**

The dataset used for training and evaluation includes various features related to loans and their statuses.

## Dataset

### Description

- **Dataset Name**: `lending_df`
- **Features**: Includes multiple attributes related to the loans (e.g., loan_size, debt_to_income, interest_rate).
- **Target Variable**: `loan_status` which indicates whether a loan is `0` (healthy) or `1` (high-risk).

### Data Splitting

- **Training Data**: Used to train the logistic regression model.
- **Test Data**: Used to evaluate the model's performance.

## Model

### Logistic Regression

- **Library Used**: `scikit-learn`
- **Random State**: 1 (for reproducibility)

### Performance Metrics

- **Class `0` (Healthy Loan)**
  - Precision: 1.00
  - Recall: 0.99
  - F1-Score: 1.00

- **Class `1` (High-Risk Loan)**
  - Precision: 0.85
  - Recall: 0.91
  - F1-Score: 0.88

- **Overall Accuracy**: 0.99

### Summary

The logistic regression model exhibits excellent performance, especially in predicting healthy loans. It accurately identifies 99% of healthy loans and 91% of high-risk loans, with slightly lower precision for high-risk loans. The model's overall accuracy is high, indicating strong performance.

## Usage

To replicate the analysis, follow these steps:
1. **Load the Data**: Import the dataset and preprocess it as needed.
2. **Train the Model**: Fit the logistic regression model using the training data.
3. **Evaluate the Model**: Use the test data to assess the model's performance with precision, recall, F1-score, and accuracy metrics.

