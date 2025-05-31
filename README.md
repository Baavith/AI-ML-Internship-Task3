# AI-ML-Internship-Task3
Project Overview
This project implements linear regression to predict the presence and severity of heart disease based on clinical features from the UCI Heart Disease dataset. The analysis includes data preprocessing, model training, evaluation, and interpretation of results.

Dataset Information
The dataset contains 920 patient records with 14 clinical features including:

Demographic information (age, sex)

Medical history (chest pain type, resting blood pressure, cholesterol levels)

Test results (electrocardiographic results, exercise-induced angina)

Target variable: num (presence and severity of heart disease)

Requirements
To run this project, you'll need:

Python 3.6+

pandas

numpy

scikit-learn

matplotlib
Project Structure
heart-disease-regression/
│
├── heart_disease_uci.csv       # Raw dataset
├── heart_disease_analysis.py   # Main analysis script
├── README.md                   # This file
└── results/                    # Directory for output files
    ├── actual_vs_predicted.png # Visualization of predictions
    └── feature_importance.png  # Feature importance plot

Key Findings
Model Performance Metrics:
Mean Absolute Error (MAE): [value]

Mean Squared Error (MSE): [value]

R-squared (R²): [value]

Most Important Features:
[Top feature 1]

[Top feature 2]

[Top feature 3]

Interpretation
The linear regression model reveals several clinically relevant insights:

Age shows a positive coefficient of [value], indicating that older patients tend to have more severe heart disease.

Cholesterol levels have a coefficient of [value], suggesting that higher cholesterol is associated with [increased/decreased] heart disease severity.

The R² value of [value] indicates that approximately [value]% of the variance in heart disease severity can be explained by the model.

Limitations
The dataset contains some missing values that were imputed, which may affect model accuracy.

The linear regression model assumes linear relationships between features and target, which may not capture all complex interactions.

The model performance could potentially be improved with feature engineering or more advanced algorithms.
