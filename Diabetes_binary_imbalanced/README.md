# 🩺 Diabetes Prediction (Imbalanced Binary Classification)

- **Dataset**: `diabetes_binary_health_indicators_BRFSS2015.csv`
- **Target**: Binary — `0` (No Diabetes), `1` (Diabetes)
- **Challenge**: Highly imbalanced dataset (~85% No Diabetes)
- **Approach**:
  - EDA (distribution, correlations)
  - SMOTE for handling imbalance
  - Logistic Regression, Random Forest, and XGBoost models
- **Best Model**: XGBoost with ~83% accuracy and highest F1-score
- **Key Insights**:
  - Age, BMI, General Health, and HighBP are top predictors
  - SMOTE improved recall for minority class (diabetic)
