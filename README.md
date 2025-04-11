# Turbine Emission Prediction using Regression Models

This project involves predicting NOx emissions from a gas turbine engine using various regression models. The goal is to build accurate models that help in forecasting turbine performance and improving operational efficiency.

## 📊 Dataset

- **Source**: Gas Turbine Engine Performance Dataset  
- **Features**: AT, AP, AH, AFDP, GTEP, TIT, TAT, CDP, CO, TEY  
- **Target Variable**: NOX

## 🔧 Workflow

1. **Data Loading** – Imported dataset using pandas.
2. **Preprocessing** – Handled missing values and standardized data.
3. **EDA** – Analyzed feature distributions and correlations.
4. **Feature Selection** – Selected top features using correlation and feature importance.
5. **Modeling** – Trained the following models:
   - Linear Regression
   - Decision Tree Regression
   - Random Forest Regression
   - Support Vector Regression (SVR)
6. **Hyperparameter Tuning** – Applied `GridSearchCV` for optimization.
7. **Evaluation** – Measured performance using RMSE and R² score.

## 📈 Results

- **Best Model**: Support Vector Regression (SVR)
- **Evaluation Metrics**:
  - RMSE: 2.916
  - R² Score: 0.933

## 🛠 Tools & Libraries

- Python (pandas, matplotlib, seaborn, scikit-learn)
