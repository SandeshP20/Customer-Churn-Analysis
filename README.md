# Customer Churn Prediction using Logistic Regression

## Project Overview

This project focuses on predicting customer churn using Logistic Regression. Churn refers to when a customer stops using a service. By analyzing customer data, we aim to build a machine learning model that can predict whether a customer is likely to churn or not.

## Problem Statement

Customer retention is a major challenge for companies. Predicting churn in advance allows businesses to take preventive actions and improve customer satisfaction. This project:
- Identifies key factors affecting churn.
- Uses logistic regression for binary classification.
- Evaluates the model using standard metrics.

## ML Algorithm Used

- Logistic Regression: A statistical model used for binary classification. It estimates the probability of a customer churning based on input features.

## Files in This Project

- `Customer Churn Logistic Regression.ipynb` – Jupyter notebook containing the full code and analysis.
- `customer_churn_dataset-training-master.csv` – Dataset used for training and evaluation.
- `customer_churn_dataset-testing-master.csv` – Additional test data (not used in this version).
- `About dataset.docx` – Document explaining the dataset and its features.
- `Explaination of used techniques.docx` – Description of the machine learning techniques applied.

## Dataset Description

The dataset includes various customer-related features:

| Feature                  | Description                             |
|--------------------------|-----------------------------------------|
| Age, Gender              | Demographic data                        |
| Tenure, Support Calls    | Service usage statistics                |
| Payment History, Spend   | Financial information                   |
| Subscription Type        | Type and duration of contract           |
| Churn                    | Target variable (Yes/No)                |

The training dataset contains both features and the churn label.

## Data Preprocessing Steps

1. Checked for and handled missing values.
2. Applied one-hot encoding to convert categorical variables into numerical form.
3. Scaled numerical features using StandardScaler.
4. Split the data into training and testing sets.

## Model Building and Evaluation

- Algorithm: Logistic Regression
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Score
- Overfitting check: Compared training and testing performance.

## Results

- The logistic regression model performed well on the training and testing sets.
- Evaluation metrics showed good accuracy and balance between precision and recall.
- ROC curve and classification report provided insights into model performance.

## Conclusion

- Logistic Regression is effective for churn prediction with proper preprocessing.
- Model performance can be enhanced further by:
  - Trying advanced algorithms (e.g., Random Forest, XGBoost)
  - Performing cross-validation
  - Hyperparameter tuning
