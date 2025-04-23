# Credit Card Fraud Detection – SLF Project

This project applies supervised machine learning techniques to detect fraudulent credit card transactions. The goal is to build a classification model that accurately identifies suspicious activity while minimizing false positives.

Given the highly imbalanced nature of fraud data, this project integrates SMOTE for resampling, and SHAP for transparent feature explanations, providing both accuracy and interpretability for financial risk monitoring systems.

---

## Project Overview

- **Objective:** Predict whether a transaction is fraudulent based on transaction features.
- **Dataset:** Anonymized credit card transaction dataset with numerical feature encoding.
- **Models Applied:**
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier

---

## Techniques & Tools

- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- SMOTE – Synthetic Minority Oversampling
- GridSearchCV for Hyperparameter Tuning
- AUC-ROC, Precision, Recall, F1-Score
- SHAP – Model explainability and feature importance
- Confusion Matrix & ROC Curve Visualizations

---

## Key Insights

- XGBoost delivered the best results with high precision and recall on the minority (fraud) class.
- SMOTE significantly improved recall, allowing the model to catch more fraudulent transactions.
- SHAP values helped explain key features contributing to classification decisions.


---

## Author

**Amneh Mohammad Ibrahim Ghanem**  
Master’s in Data Science – Deakin University  
[LinkedIn](https://www.linkedin.com/in/amneh-m) | [GitHub](https://github.com/amneh992)
