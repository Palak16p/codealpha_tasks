# Credit Scoring Model

## Project Overview

This project predicts an individual's creditworthiness using financial data and Machine Learning classification algorithms.

## Objective

To predict whether a customer is creditworthy based on financial features such as income, debt, payment history, and credit utilization.

## Dataset

A small sample dataset was created for this project.

### Features
- Income
- Debt
- Payment History
- Credit Utilization
- Debt-to-Income Ratio

### Target
- `1` = Creditworthy
- `0` = Not Creditworthy

## Feature Engineering

A new feature called `debt_to_income` was created using:

`debt_to_income = debt / income`

## Machine Learning Models

- Logistic Regression
- Decision Tree Classifier

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Results

Both models correctly classified the test samples in this experiment, with all five evaluation metrics equal to 1.0 on the test set.

## Limitations

The dataset contains only 10 sample records, with 2 records in the test set. Therefore, the results should not be considered representative of real-world credit scoring performance.

A larger and more diverse dataset would be required for reliable evaluation.