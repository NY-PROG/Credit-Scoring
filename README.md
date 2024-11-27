# Credit Scoring for Subprime Mortgages
This project develops a machine learning-based credit risk model for ABC Bank Ltd., aimed at optimizing lending decisions for subprime mortgages.

Business Context
---

    ABC Bank's objective is to make informed lending decisions using an in-house risk model.
    Profit/Loss Details:
    Profit: $100 from a good customer (loan paid off).
    Loss: $500 from a bad customer (bad loan).
    There are 30 variables including bankruptcy indicator, finance inquires over 24 months, number trade lines 30 or 60 days over 24 months, 
    time since last inquiry and customer ID etc with 3000 observations in the dataset.

Risk Model Approach
---
    The dataset includes labeled historical data on credit outcomes.
    Data split:
    80% used as the training set to build the model.
    20% used as the test set for validating the model's performance.

Features of the Project
---
    Data Preprocessing: Includes feature engineering, handling missing values, and standardizing data.
    Model Training: Implements machine learning algorithms to classify borrowers as "good" or "bad."
    Performance Metrics: Assesses model accuracy, precision, recall, and profitability.
    Export Predictions: Saves model predictions to .csv or .xlsx formats.

Tools and Libraries
---
    pandas: Data manipulation and processing.
    scikit-learn: Model training and evaluation.
    openpyxl: Exporting predictions in Excel format.
