# Transactional Fraud Detection Analysis

## Objective
Detect fraudulent financial transactions using historical transaction data.

## Dataset
- 284,807 transactions
- 492 fraud cases
- Fraud rate: 0.172%

## EDA Findings
- Fraud is highly imbalanced.
- Higher fraud frequency during night hours.
- Features V14, V12, and V17 showed strong correlation with fraud.

## Model
- Logistic Regression with balanced class weights.
- Evaluation metrics: Precision, Recall, F1-score, ROC-AUC.

## Results
- ROC-AUC: 0.97+
- High recall achieved for fraud detection.

## Conclusion
The baseline model can effectively identify suspicious transactions and can be improved further using advanced techniques such as Random Forest, XGBoost, and SMOTE.