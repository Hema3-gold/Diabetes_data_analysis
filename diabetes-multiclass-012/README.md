# 🩺 Diabetes Risk Prediction (Multiclass Classification)

- **Dataset**: `diabetes_012_health_indicators_BRFSS2015.csv`
- **Target**:
  - `0`: No Diabetes
  - `1`: Prediabetes
  - `2`: Diabetes
- **Challenge**: Severe imbalance — class 1 (Prediabetes) under 2%
- **Approach**:
  - Full EDA (univariate, bivariate, correlation heatmap)
  - SMOTE to oversample minority classes
  - Models: Logistic Regression, Random Forest, XGBoost
- **Best Model**: XGBoost with highest accuracy and class-wise F1 scores
- **Insights**:
  - HighBP, HighChol, Age, and GenHlth are top drivers
  - Prediabetes remains difficult to predict even after resampling
