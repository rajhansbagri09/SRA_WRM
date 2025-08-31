1. Project Title

SRA_WRM: Smart Reservoir Analytics for Water REsource Management.

2. Project Description

This project focuses on predicting Water Quality Index (WQI) using various physicochemical and biological parameters of water.

The goal is to help in efficient water resource management by automating water quality assessment using machine learning techniques.

3. Dataset

Dataset used: Results_MADE.csv

Features: Temperature, Dissolved Oxygen, pH, BOD, Nitrate, Conductivity, Faecal Coliform, etc.

Target: WQI (Water Quality Index)

4. Data Preprocessing

Handled missing values.

Performed log transformation for skewed features.

Removed outliers using IQR method.

Applied StandardScaler for normalization.

5. Model Development

Models trained:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Train-test split: 80-20.

Hyperparameter tuning with GridSearchCV / RandomizedSearchCV.

6. Model Evaluation

Metrics used:

R² Score

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

Best model achieved R² ≈ 0.9+ (example, you can replace after running).

7. Results & Insights

Important features influencing WQI: [example – Dissolved Oxygen, Nitrate, BOD].

Random Forest performed best with high accuracy and low error.

The model can assist government agencies & researchers in real-time water monitoring.

8. Tools & Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn

XGBoost
