# Customer Churn Prediction

## Project Overview
This project predicts whether a customer is likely to churn using machine learning. The goal is to help businesses identify at-risk customers and improve customer retention.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- SHAP
- Jupyter Notebook

## Project Workflow
1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Feature engineering
4. Model training
5. Model evaluation
6. Model explainability using SHAP

## Models Compared
- Logistic Regression
- XGBoost

## Final Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 80.55% | 45.94% | 86.32% | 59.96% | 89.40% |
| XGBoost | 94.23% | 88.34% | 75.79% | 81.59% | 97.67% |

## Key Result
The XGBoost model performed best with 94.23% accuracy and 97.67% ROC-AUC.

## Visual Results
The project includes:
- ROC curve comparison
- Precision-recall curve comparison
- XGBoost confusion matrix
- SHAP feature importance
- SHAP summary plot
- SHAP waterfall explanation

## Business Impact
This project can help businesses identify customers who are likely to leave, allowing them to take action early and reduce customer churn.
