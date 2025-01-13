# BankChurners_Analyst

## Overview
This project aims to analyze and predict customer attrition (churn) in the banking sector. By leveraging machine learning models, we investigate key factors contributing to customer churn and provide insights that can help financial institutions improve customer retention strategies. The dataset includes various customer attributes such as demographic data, transaction history, and account features.

## Dataset Overview
The dataset used in this project contains customer data from a bank, with information on account characteristics, transactional behavior, and demographic details. The target variable is the Attrition_Flag, which indicates whether a customer has churned (left) or is still an active customer.

## Key Questions:
What are the key factors influencing customer attrition in the banking sector?
Can we predict customer churn based on their behavior and demographic data?
How does customer engagement (e.g., contact count, transaction history) correlate with attrition?
Approach

## Data Analysis
We performed exploratory data analysis (EDA) to identify the characteristics of customers who churn. The analysis includes:

Descriptive statistics of customer features.
Distribution of numerical features such as Customer_Age, Total_Trans_Amt, Avg_Utilization_Ratio, etc.
Visualizations to understand the relationships between features and customer churn (e.g., boxplots, barplots, countplots).
Feature Importance
We utilized machine learning models like Random Forest to assess the importance of different features in predicting customer churn. This helped us identify which factors were the most critical in determining whether a customer is likely to churn.

## Visualizations
We used Seaborn and Matplotlib to generate visualizations such as:
- Distribution of customer Age, Income Category, and Transaction Amount for customers who churned vs. those who stayed.
- Correlation heatmaps to show relationships between numerical features.
