# credit-risk-classification
Module 20 Challenge

## Overview of the Analysis

The purpose of this analysis was to develop and evaluate a machine learning model for predicting loan risk. The model aims to identify which loans are healthy (0) versus high-risk (1) based on various financial indicators. This kind of prediction is crucial for lending institutions to minimize risk and make informed lending decisions.

The data contained financial information about loans, and our task was to predict their risk level. We used a Logistic Regression model, which went through several key stages:

    1. Data preparation and splitting into training and testing sets
    2. Model training using LogisticRegression
    3. Making predictions on test data
    4. Evaluating model performance through various metrics

## Results

* Machine Learning Model:
    * Accuracy: The model showed high overall accuracy

    * Precision:
        * Healthy Loans (0): 100% precision
        * High-Risk Loans (1): 84% precision

    * Recall:
        * Healthy Loans (0): 99% recall
        * High-Risk Loans (1): 94% recall

## Summary

The logistic regression model performs exceptionally well for this loan prediction task. Its strength lies in perfect precision for healthy loans, a trong ability to identify high-risk loans (84% precision, 94% recall), and a high overall accuracy across both categories.

I would recommend this model for use because it demonstrates reliable performance in identifying both healthy and high-risk loans. The high recall rate (94%) for high-risk loans is particularly important as it means the model rarely misses problematic loans, which is crucial for risk management. While it may occasionally flag healthy loans as risky (as shown by the 84% precision for high-risk loans), this conservative approach is preferred in lending where missing a high-risk loan could be very costly.