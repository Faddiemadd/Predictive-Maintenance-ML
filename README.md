# Predictive-Maintenance-ML

A machine learning system that predicts equipment failures within a
24-hour window from sensor readings, helping reduce unexpected
downtime and maintenance costs.

## Problem
Three prediction tasks on industrial machine data:
1. Will the machine fail within 24 hours? (classification)
2. What type of failure will it be? (classification)
3. What will the repair cost be? (regression)

## Dataset
24,000+ operational records with features such as vibration,
motor temperature, current, pressure, RPM, hours since maintenance
and ambient temperature.

## Approach
- Exploratory data analysis (distributions, correlations, outliers)
- Data cleaning: missing values and outliers handled per machine type
- Trained and compared multiple models for each task

## Results
| Task | Best Model | Score |
|------|-----------|-------|
| Failure within 24h | XGBoost | 97.7% accuracy |
| Failure type | XGBoost | 97.9% accuracy |
| Repair cost | Random Forest | R² = 0.80 |

Models compared:
- Classification: Random Forest, XGBoost, SVM, Logistic Regression
- Regression: Random Forest, XGBoost, Bagging, Linear Regression, SVR

## Tech Stack
Python, Pandas, Scikit-Learn, XGBoost, Matplotlib

## Files
- predictive_maintenance.ipynb: full analysis and modeling
- predictive_maintenance_v3.csv: dataset

## How to Run
1. Clone the repo
2. Install: pip install pandas scikit-learn xgboost matplotlib
3. Open the notebook in Jupyter or Google Colab and run all cells

## Team
[Fadi Emad](https://www.linkedin.com/in/fadi-emad), [Hussen Magdy](https://www.linkedin.com/in/hussen-magdy/?isSelfProfile=false), [Fatma Samy](https://www.linkedin.com/in/fatma-samy-02ab48345/), [Mohamed Ibrahim](https://www.linkedin.com/in/mohamed-ibrahim-mousa), [Ahmed Nasser](https://www.linkedin.com/in/ahmed-nasser-06a65832a?utm_source=share_via&utm_content=profile&utm_medium=member_android), [Mohamed Seif](https://www.linkedin.com/in/mohamed-seif-/)

Built as the final project of the Machine Learning Summer Training
at NTI (2026).
