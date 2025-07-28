
---

### 📁 `task_2_churn_pipeline/README.md`
```markdown
# 📊 Customer Churn Prediction Pipeline

## Objective
Build a robust, production-ready machine learning pipeline to predict customer churn from structured data.

## Dataset
- **Source**: [Telco Customer Churn (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Features**: Demographics, services, tenure, charges, etc.

## Methodology
- Data preprocessing (imputation, encoding, scaling)
- Model selection: Logistic Regression and Random Forest
- Hyperparameter tuning using GridSearchCV
- Pipeline created using `scikit-learn.Pipeline`
- Exported model with `joblib`

## Results
- **Best Model**: Random Forest
- **Accuracy**: ~80%
- **AUC**: ~0.85

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn joblib
