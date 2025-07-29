# 🩺 Diabetes Prediction (Balanced 50/50 Binary Classification)

- **Dataset**: `diabetes_binary_5050split_health_indicators_BRFSS2015.csv`
- **Target**: Binary — `0` (No Diabetes), `1` (Diabetes) — **balanced**
- **Goal**: Evaluate model performance when class imbalance is removed
- **Approach**:
  - EDA, class distribution checks
  - Feature importance, scaling
  - Trained Logistic Regression, Random Forest, XGBoost
- **Best Model**: XGBoost with high accuracy and balanced performance
- **Insights**:
  - Dataset balance improved Logistic Regression significantly
  - Top predictors remain consistent: Age, BMI, GenHlth, PhysHlth
