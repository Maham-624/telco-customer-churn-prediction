# Telco Customer Churn Prediction and Retention

## Project Overview

Customer churn is a major challenge for telecommunications companies because losing existing customers can reduce recurring revenue and increase customer acquisition costs.

This project develops an end-to-end machine learning workflow to analyze customer churn, identify important factors associated with customer attrition, and build predictive models that can help support customer retention strategies.

## Objectives

- Explore and understand customer behavior using exploratory data analysis.
- Identify important factors associated with customer churn.
- Clean and preprocess the dataset for machine learning.
- Perform feature engineering where appropriate.
- Train and compare multiple classification models.
- Evaluate model performance using suitable classification metrics.
- Identify actionable insights that may support customer retention.

## Project Workflow

1. Data loading and inspection
2. Data quality assessment
3. Exploratory Data Analysis (EDA)
4. Data preprocessing
5. Feature engineering
6. Model development
7. Model comparison and evaluation
8. Churn-risk analysis
9. Customer retention insights

## Machine Learning

Multiple classification approaches were explored to predict whether a customer is likely to churn.

Model performance was evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Model Performance

Four machine learning approaches were evaluated using cross-validation: Logistic Regression, Random Forest, XGBoost, and a Stacking Ensemble.

| Model | Recall | F1-Score | ROC-AUC | PR-AUC |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.5431 | 0.5923 | 0.8462 | 0.6617 |
| Random Forest | 0.4796 | 0.5429 | 0.8204 | 0.6134 |
| XGBoost | 0.5197 | 0.5796 | 0.8438 | 0.6618 |
| Stacking Ensemble | 0.5231 | 0.5877 | **0.8478** | **0.6672** |

The Stacking Ensemble achieved the highest mean ROC-AUC (0.8478) and PR-AUC (0.6672), while Logistic Regression achieved the highest mean recall (0.5431).

## Key Business Purpose

The project goes beyond simply predicting churn. The analysis aims to help identify customers with higher churn risk and understand the characteristics associated with customer attrition.

These insights can support targeted retention strategies and data-driven customer relationship management.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Machine Learning
- Exploratory Data Analysis
- Feature Engineering

## Project Notebook

The complete analysis, preprocessing, modeling, evaluation, and visualizations are available in:

`telco-customer-churn-prediction-and-retention.ipynb`

## Future Improvements

Future work may include additional hyperparameter optimization, advanced ensemble methods, model explainability techniques, and deployment of the churn prediction model as an interactive application.

## Author

**Maham-624**  
Mathematics | Data Analytics | Machine Learning | Cryptography
