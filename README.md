# Task 2: Credit Risk Prediction

## Overview
The goal of this task is to predict whether a loan applicant is likely to default on their loan. Using the Loan Prediction dataset, we build and evaluate machine learning models to make accurate predictions and identify the key factors influencing loan approval.

## Dataset
- **Source:** Kaggle (Loan Prediction Dataset)
- **Features include:** 
  - Gender, Married, Dependents, Education, Self_Employed
  - ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term
  - Credit_History, Property_Area
- **Target:** Loan_Status (1 = Approved, 0 = Not Approved)

> **Note:** The CSV dataset is not included in this repository. Please download it from Kaggle and place it in the same folder as the notebook before running.

## Approach
1. **Data Cleaning:** 
   - Handle missing values for categorical and numerical columns.
   - Fix irregular entries like '3+' in Dependents.
2. **Feature Encoding:** 
   - Convert categorical variables into numeric format using Label Encoding.
3. **Train-Test Split:** 
   - Split dataset into training and testing sets for model evaluation.
4. **Feature Scaling:** 
   - Scale features for Logistic Regression using StandardScaler.
5. **Model Training:** 
   - Logistic Regression
   - Decision Tree Classifier
6. **Model Evaluation:** 
   - Accuracy score
   - Confusion matrix
   - Classification report
7. **Insights & Feature Importance:** 
   - Identify which features have the most impact on loan approval.

## Results
- **Logistic Regression Accuracy:** ~81%
- **Decision Tree Accuracy:** ~78%
- **Key Influential Features:** Credit_History, ApplicantIncome, LoanAmount

## Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn

## How to Run
1. Download the dataset from Kaggle.  
2. Place the CSV file in the same folder as the notebook.  
3. Open the Jupyter Notebook (`Task2_Credit_Risk_Prediction.ipynb`) and run all cells.  
4. Check the outputs: model metrics, graphs, and feature importance.
