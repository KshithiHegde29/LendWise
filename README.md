# Overview

This is a machine learning project that predicts the eligible loan amount for a customer based on personal and financial details. The prediction model uses a Random Forest Regressor, chosen for its superior performance among multiple models tested.

# Dataset

Source: Kaggle

Size: ~30,000 records

# Data Preprocessing

Handling missing values (NaN removal)

Outlier detection and removal using z-score

Typecasting features to correct formats

Reducing skewness in numerical attributes

Feature scaling using StandardScaler

Additional transformations (e.g., converting property age to years)

# Model Development

Five models were trained and evaluated:

Gradient Boosting Regressor

Random Forest Regressor

Linear Regression

PCA-based Linear Regression

Neural Network (PyTorch)

Random Forest Regressor achieved the best performance (MSE: 0.04). The final model and scaler were serialized using Pickle for deployment.

# Technologies

Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, PyTorch

Model Serialization: Pickle, Joblib
