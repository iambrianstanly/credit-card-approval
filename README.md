# Credit Card Approval

## Overview

Utilize machine learning approaches to predict credit card approval based on customer information.

## Dataset

Publically availabel dataset.

Features are as follows:

- **Ind_ID**: Client ID
- **Gender**: Gender information
- **Car_owner**: Having car or not
- **Propert_owner**: Having property or not
- **Children**: Count of children
- **Annual_income**: Annual income
- **Type_Income**: Income type
- **Education**: Education level
- **Marital_status**: Marital_status
- **Housing_type**: Living style
- **Birthday_count**: Use backward count from current day (0), -1 means yesterday.
- **Employed_days**: Start date of employment. Use backward count from current day (0). Positive value means, individual is currently unemployed.
- **Mobile_phone**: Any mobile phone
- **Work_phone**: Any work phone
- **Phone**: Any phone number
- **EMAIL_ID**: Any email ID
- **Type_Occupation**: Occupation
- **Family_Members**: Family size

## SQL

Used sql queries to analyse the data, try to find answers. Uisng python packgae like (duckdb).

## Pipeline

- **EDA**: Visualizing data for better understanding. Uisng techniques like Univariant and Bivariant Analysis. Correation for considering the features (feature selection).
- **Imputing**: Treating missing values. Using technique like smote to handle the imbalance in data.
- **Model**: Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine modles are  used and compared.
- **Training**:  Hyperparamter tuning techniques used for leveraging the performance for each models.

## Model Evaluation

The models are evaluated upon taking confusion matrix and comparing the accuracy, precision. Random Forest model performed well as accuracy of 92% was aquired.
