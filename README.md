📊 Loan Default Prediction Using Machine Learning

Project Overview

Loan default is a major challenge faced by banks and financial institutions, as it can lead to significant financial losses and increased credit risk. Predicting whether a borrower is likely to default enables lenders to make informed lending decisions, improve portfolio quality, and strengthen risk management practices.

This project applies machine learning techniques to predict loan default using borrower demographic, financial, and loan-related information. Multiple classification models were developed and compared to identify the most effective approach for predicting loan default.

Objectives

The main objectives of this project were to:

Perform data cleaning and preprocessing.  
Conduct exploratory data analysis (EDA).  
Handle class imbalance using SMOTE (Synthetic Minority Oversampling Technique).  
Develop and compare multiple machine learning classification models.  
Evaluate model performance using standard classification metrics.  
Identify the most important variables influencing loan default.  
Dataset

The dataset contains borrower demographic, financial, employment, and loan-related information.

Features
Age  
Income  
Loan Amount  
Credit Score  
Interest Rate  
Loan Term  
Debt-to-Income Ratio (DTI)  
Months Employed  
Number of Credit Lines  
Education  
Employment Type  
Marital Status  
Loan Purpose  
Has Mortgage  
Has Dependents  
Has Co-signer  
## 🎯 Target Variable

| Value | Description |
|:-----:|-------------|
| **0** | No Default |
| **1** | Loan Default |




Project Workflow
1. Data Preprocessing  
Loaded the dataset using Pandas.  
Checked for missing values.  
Removed unnecessary variables.  
Encoded categorical variables.  
Prepared the dataset for machine learning.  
2. Exploratory Data Analysis (EDA)  

The following analyses were performed:

Summary statistics
Distribution of numerical variables  
Correlation analysis  
Class distribution visualization  
Feature relationship analysis  
3. Handling Class Imbalance

The target variable was imbalanced. To improve model performance, SMOTE (Synthetic Minority Oversampling Technique) was applied to the training dataset before model development.

4. Machine Learning Models

The following classification models were trained and compared:

Logistic Regression  
Decision Tree Classifier  
Random Forest Classifier  
XGBoost Classifier  

The dataset was divided into:

Training Set (80%)  
Testing Set (20%)  
Model Performance
## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|:------|---------:|----------:|--------:|---------:|---------:|
| Logistic Regression | 67.72% | 21.29% | **65.98%** | **32.19%** | **0.731** |
| Decision Tree | 72.01% | 18.77% | 42.67% | 26.08% | 0.660 |
| Random Forest | 77.02% | 20.57% | 34.32% | 25.72% | 0.677 |
| XGBoost | **84.75%** | **29.60%** | 22.71% | 25.70% | 0.717 |
Model Evaluation

The models were evaluated using:

-Accuracy  
-Precision  
-Recall  
-F1 Score  
-ROC-AUC  
-ROC Curve  
-Confusion Matrix  
-Feature Importance  

## Feature importance

Feature importance analysis identified the variables that contributed most significantly to predicting loan default.

The most influential variables included:

Income
Loan Amount
Debt-to-Income Ratio (DTI)
Interest Rate
Loan Term
Months Employed
Age
Credit Score

These variables were the strongest predictors of borrower default and are consistent with factors commonly considered in credit risk assessment.

## Findings

The findings indicate that:

-Borrowers with higher debt burdens and larger loan amounts are more likely to default.  
-Income and employment history play an important role in loan repayment.  
-Credit score remains one of the strongest indicators of default risk.  
-Machine learning models can support lenders by providing faster and more consistent credit risk assessments.  


## Technologies Used
-Python
-Jupyter Notebook
-Pandas
-NumPy
-Matplotlib
-Scikit-learn
-XGBoost
-Imbalanced-learn (SMOTE)

## Findings

Future work may include:

Hyperparameter tuning to further improve model performance.  
Evaluating additional machine learning algorithms such as LightGBM and CatBoost.  
Deploying the model as a web application using Streamlit.  
Validating the model using real-world banking datasets.  
Investigating cost-sensitive learning techniques for highly imbalanced data.  
Author

Angeline Oyaro

Bachelor of Science in Actuarial Science

GitHub: https://github.com/Angie034

LinkedIn: https://www.linkedin.com/in/angeline-oyaro-2a2878253
