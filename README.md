# # Transactional Fraud Detection Analysis

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SQL
- Power BI

## Key Features
- Fraud pattern analysis
- Feature engineering
- Logistic Regression baseline model
- ROC-AUC evaluation
- Interactive Power BI dashboard

## Results
- Achieved high fraud detection recall and ROC-AUC above 0.97 on the test dataset.



WORK FLOW

             creditcard.csv
                    ↓
              Load Dataset
                    ↓
              Data Profiling
                    ↓
            Missing Value Check
                    ↓
            Class Imbalance
                    ↓
                   EDA
            ↙       ↓       ↘
       Amount      Time    Correlation
            ↘       ↓       ↙
          Feature Engineering
                    ↓
                X and y
                    ↓
             Train/Test Split
                    ↓
              Feature Scaling
                    ↓
          Logistic Regression
                    ↓
               Predictions
                    ↓
       ┌────────────┼────────────┐
       ↓            ↓            ↓
   Precision      Recall      F1-Score
       └────────────┼────────────┘
                    ↓
                ROC-AUC
                    ↓
           Confusion Matrix
                    ↓
          Feature Importance
                    ↓
             Power BI
                    ↓
             Final Report
                    ↓
              Presentation