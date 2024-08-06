# Telco Customer Churn Prediction

## Project Overview

This project is part of the Data Mining course and focuses on predicting customer churn for a telecommunications company. Customer churn, or customer attrition, refers to the phenomenon where customers stop doing business with a company. By accurately predicting which customers are at risk of churning, the company can take proactive measures to retain them.

## Objectives

1. Analyze the telco company's customer dataset to identify patterns and factors contributing to churn.
2. Develop and compare multiple machine learning models to predict customer churn.
3. Provide actionable insights to reduce customer churn based on the analysis and model results.

## Dataset

The project uses a dataset from a telecommunications company containing various customer attributes, including:

- Customer demographics (age, gender, etc.)
- Account information (contract type, payment method, etc.)
- Services used (phone, internet, streaming, etc.)
- Usage patterns
- Churn status (target variable)

## Methodology

1. Data Preprocessing:
   - Handle missing values
   - Encode categorical variables
   - Feature scaling

2. Exploratory Data Analysis (EDA):
   - Visualize relationships between features and churn
   - Identify key factors influencing customer churn

3. Feature Engineering:
   - Create new features based on domain knowledge and EDA insights

4. Model Development:
   - Split data into training and testing sets
   - Implement and compare multiple algorithms, such as:
     - Logistic Regression
     - Random Forest
     - Gradient Boosting
     - Support Vector Machines

5. Model Evaluation:
   - Use metrics like accuracy, precision, recall, and F1-score
   - Perform cross-validation to ensure model robustness

6. Interpretation and Insights:
   - Analyze feature importance
   - Provide actionable recommendations based on model results

## Getting Started

1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run Jupyter notebooks `project.ipynb` to see the analysis and modeling process
