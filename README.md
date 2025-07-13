
# Loan Approval Model

## Overview

The Loan Approval Model is a machine learning project that aims to predict the likelihood of loan approval based on a variety of applicant information. This project utilizes several machine learning techniques and preprocessing steps to build a robust model that can assist financial institutions in making informed decisions about loan approvals.

## Project Description

The project involves building a predictive model to determine the probability of loan approval based on various features such as applicant income, loan amount, credit history, and more. The project follows a typical machine learning pipeline, including data preprocessing, feature engineering, model training, and evaluation.

## Data

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication). It contains several features related to the applicants' demographic and financial information:

- **Loan_ID**: Unique Loan ID
- **Gender**: Male/Female
- **Married**: Applicant married (Y/N)
- **Dependents**: Number of dependents
- **Education**: Applicant Education (Graduate/Undergraduate)
- **Self_Employed**: Self-employed (Y/N)
- **ApplicantIncome**: Applicant income
- **CoapplicantIncome**: Coapplicant income
- **LoanAmount**: Loan amount in thousands
- **Loan_Amount_Term**: Term of loan in months
- **Credit_History**: Credit history meets guidelines (1/0)
- **Property_Area**: Urban/Semi Urban/Rural
- **Loan_Status**: Loan approved (Y/N)

## Model Development

The model development process involves the following steps:

1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical features

2. **Feature Engineering**:
   - Creating new features that might help improve model performance

3. **Model Training**:
   - Splitting the data into training and testing sets
   - Training multiple machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest)
   - Hyperparameter tuning using GridSearchCV

4. **Model Evaluation**:
   - Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score
   - Cross-validation to ensure model robustness

## Results

The final model achieved the following performance metrics on the test set:

- **Accuracy**: 78
- **Precision**: 97


(Replace X.XX with actual values)

