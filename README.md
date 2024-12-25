# Loan Prediction SVM Model

## Overview

This project involves building a Support Vector Machine (SVM) model to predict loan approval status based on various applicant attributes. The model is trained using the Loan Prediction dataset and demonstrates data preprocessing, exploratory data analysis, and model evaluation.

## Features

Data preprocessing and cleaning, including handling missing values and label encoding.

Visualizations to understand the relationships between features and loan status.

Implementation of a linear kernel SVM classifier.

Model evaluation using accuracy scores on both training and test datasets.

## Dataset

The dataset used for this project contains the following columns:

**Loan_ID**: Unique Loan Identifier (excluded during training).

**Gender**: Gender of the applicant.

**Married**: Marital status of the applicant.

**Dependents**: Number of dependents.

**Education**: Graduate or Not Graduate.

**Self_Employed**: Employment status.

**ApplicantIncome**: Applicant's income.

**CoapplicantIncome**: Co-applicant's income.

**LoanAmount**: Loan amount in thousands.

**Loan_Amount_Term**: Term of the loan in months.

**Credit_History**: Credit history meets guidelines (1: Yes, 0: No).

## Project Workflow

### 1. Import Dependencies

We use Python libraries like pandas, numpy, seaborn, and scikit-learn for data manipulation, visualization, and modeling.

### 2. Data Collection and Processing

Load the dataset using pandas.

Handle missing values by dropping rows with NaNs.

Perform label encoding for categorical variables.

Replace specific values (e.g., "3+" dependents with 4) for numerical consistency.

### 3. Data Visualization

Create count plots to analyze relationships between features (e.g., Education and Loan Status, Marital Status and Loan Status).

### 4. Feature Engineering

Convert categorical features like "Married" and "Gender" into numerical values.

Separate the dataset into features (X) and target variable (Y).

### 5. Train-Test Split

Split the dataset into training and test sets using an 80:20 ratio with stratification to maintain class balance.

### 6. Model Training

Train a Support Vector Machine classifier with a linear kernel using the training dataset.

### 7. Model Evaluation

Evaluate the model's performance using accuracy scores for both training and test datasets.

## Results

**Training Accuracy**: Calculated during evaluation.

**Test Accuracy**: Calculated during evaluation.


**Property_Area**: Urban, Semiurban, or Rural area.

**Loan_Status**: Loan approval status (Y: Approved, N: Not Approved).
