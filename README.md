# Telco-Churn-Prediction
Customer churn prediction using machine learning and cross-validation

## Overview
This project focuses on predicting customer churn and identifying the key factors that influence customer attrition.  
The goal is to support data-driven decision-making for customer retention strategies.

## Dataset
The project uses the public **Telco Customer Churn** dataset (IBM sample dataset).

## Problem Statement
Customer churn has a significant impact on business revenue.  
The objective of this project is to build a reliable machine learning model that can predict churn and provide insights into the most influential features.

## Approach
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Cross-validation across multiple train-test splits

## Model Selection
Multiple models were evaluated during development.  
**Logistic Regression** was selected as the final model because it demonstrated:
- Higher mean accuracy across cross-validation folds
- Lower variance compared to more complex models
- Better interpretability for business use cases

## Results
The final workflow provides a stable and interpretable churn prediction pipeline.  
The model can be used to identify high-risk customers and support targeted retention efforts.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## Repository Structure
