📊 Loan Default Prediction Using Machine Learning

<p align="center">











</p>

📖 Project Overview

Loan default prediction is one of the most important applications of machine learning in the financial industry. Accurate prediction enables banks and lending institutions to identify high-risk borrowers before approving loans, reducing financial losses while improving credit risk management.

This project develops and compares four machine learning classification models to predict whether a borrower is likely to default on a loan. The project also addresses class imbalance using SMOTE and evaluates model performance using several classification metrics.

🎯 Project Objectives
Clean and preprocess the loan dataset.
Perform Exploratory Data Analysis (EDA).
Handle class imbalance using SMOTE.
Build and compare multiple machine learning models.
Evaluate model performance using Accuracy, Precision, Recall, F1 Score and ROC-AUC.
Identify the key drivers of loan default.
Provide business recommendations for financial institutions.
🗂 Repository Structure
loan-default-prediction/
│
├── data/
│   └── loan_data.csv
│
├── notebooks/
│   └── Loan_Default_Prediction.ipynb
│
├── images/
│   ├── roc_curve.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
├── report/
│   └── Loan_Default_Prediction_Report.pdf
│
├── requirements.txt
├── README.md
└── LICENSE
⚙️ Machine Learning Workflow
Loan Dataset
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Train-Test Split (80/20)
      │
      ▼
SMOTE (Handle Class Imbalance)
      │
      ▼
Model Training
 ├── Logistic Regression
 ├── Decision Tree
 ├── Random Forest
 └── XGBoost
      │
      ▼
Model Evaluation
 ├── Accuracy
 ├── Precision
 ├── Recall
 ├── F1 Score
 ├── ROC Curve
 ├── ROC-AUC
 └── Confusion Matrix
      │
      ▼
Feature Importance
      │
      ▼
Business Insights & Recommendations
📷 Project Results

Add your screenshots in the images folder and display them like this:

ROC Curve
![ROC Curve](images/roc_curve.png)
Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)
Feature Importance
![Feature Importance](images/feature_importance.png)
Model Comparison
![Model Comparison](images/model_comparison.png)
⭐ Key Results
✅ Compared four machine learning classification models.
✅ Applied SMOTE to address class imbalance.
✅ Achieved 84.75% Accuracy using XGBoost.
✅ Achieved the highest ROC-AUC (0.731) using Logistic Regression.
✅ Identified the most influential predictors of loan default through feature importance analysis.
👩‍💻 Author

Angeline Oyaro

Bachelor of Science in Actuarial Science
