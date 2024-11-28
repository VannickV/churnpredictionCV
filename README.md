# Churn Prediction Case 

## Overview
This project involves predicting customer churn using a dataset and comparing the performance of multiple machine learning models. The best-performing model, Random Forest, was selected for further fine-tuning and optimization. The goal is to identify the most accurate predictive model while understanding the key factors driving customer churn.

## Approach
1. **Dataset Preparation**:
   - Loaded and explored the dataset for missing values, correlations, and target variable distribution.
   - Preprocessed features with encoding, scaling, and balancing techniques such as SMOTE.

2. **Model Comparison**:
   - Baseline models including Logistic Regression, Random Forest, and XGBoost were trained.
   - Model performances were compared using metrics like Recall, Precision, F1-Score, and ROC-AUC.

3. **Fine-Tuning**:
   - Random Forest, the strongest model, was selected for further hyperparameter tuning using RandomizedSearchCV.
   - The optimized model achieved significant improvement in performance.

## Key Insights
- Random Forest demonstrated the best balance of accuracy and robustness.
- Proper preprocessing and handling of class imbalance significantly impacted model outcomes.
- Feature importance analysis highlighted critical factors influencing customer churn.

## Requirements
- Python 3.12 or higher
- Libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `imblearn`
  - `xgboost`

Install the requirements with:
```bash
pip install -r requirements.txt
