# BankAfrique Customer Churn Prediction

## Project Overview

This project analyzes customer data from BankAfrique to identify the key factors driving customer churn and develop machine learning models capable of predicting customers at risk of leaving the bank.

## Objective

The goal was to help the bank improve customer retention by:

* Identifying the main drivers of churn
* Building predictive models to detect high-risk customers
* Providing business recommendations based on data-driven insights

## Dataset & Preprocessing

* Removed non-informative identifier columns (Customer ID and Name)
* Performed exploratory data analysis (EDA)
* Applied feature scaling and one-hot encoding
* Addressed class imbalance using SMOTE
* Built preprocessing pipelines using Scikit-learn

## Models Evaluated

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

## Results

XGBoost achieved the best overall performance with approximately 85% accuracy and the strongest balance between precision and recall for churn prediction.

## Key Findings

* Age was a major predictor of churn, particularly among customers aged 50–59.
* Customers with multiple banking products showed higher churn rates.
* Customer geography significantly influenced churn behavior.
* Inactive customers were more likely to leave the bank.

## Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Imbalanced-learn (SMOTE)

## Business Recommendations

The analysis suggests focusing retention efforts on:

* Customers aged 40–59
* Customers with multiple products
* Inactive customers
* High-risk geographic segments

Targeted engagement campaigns, loyalty programs, and personalized offers could help reduce customer churn.
