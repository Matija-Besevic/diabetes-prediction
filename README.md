# Diabetes Prediction using Random Forest

This project implements a complete Machine Learning pipeline to predict diabetes based on diagnostic measurements.

## 📊 Key Results
- **Test Set Accuracy:** 98.75%
- **Training Set Accuracy:** 99.94%
- **Model Used:** Random Forest Classifier (Optimized via GridSearchCV)

## 🛠️ Project Workflow
1. **Exploratory Data Analysis (EDA):** Visualizing data distribution and outcomes.
2. **Data Cleaning:** Handling invalid zero values by replacing them with the Mean/Median depending on their skewness.
3. **Feature Scaling:** Normalizing data using `StandardScaler` to ensure fair play between attributes.
4. **Hyperparameter Tuning:** Running a "tournament" of algorithms using `GridSearchCV`.
5. **Model Evaluation:** Detailed evaluation using Confusion Matrices and Classification Reports.
6. **Feature Importance:** Visualizing top 5 biometrical factors contributing to the diagnosis.
7. **Model Deployment Readiness:** Saving the final model and scaler via `joblib`.

## 📦 Saved Artifacts
- `diabetes_model.pkl` - Trained Random Forest Model
- `scaler.pkl` - Trained StandardScaler instance
