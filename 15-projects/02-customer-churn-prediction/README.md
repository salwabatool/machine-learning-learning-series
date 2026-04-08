# Customer Churn Prediction

**Goal**: Identify customers at risk of churning.

## Key Techniques
- Handling class imbalance (`class_weight='balanced'`)
- LabelEncoder for categorical features
- AUC-ROC as primary metric (better than accuracy for imbalanced data)

## Models Compared
- Logistic Regression (with class weight balancing)
- Random Forest
- Gradient Boosting
