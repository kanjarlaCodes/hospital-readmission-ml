# Hospital Readmission Prediction Using Logistic Regression

## Project Overview

This project applies supervised machine learning techniques to predict whether a patient is likely to be readmitted to a hospital based on demographic and clinical features. Logistic Regression is used for binary classification, and SMOTE is implemented to address class imbalance in the dataset.

---

## Problem Statement

Hospital readmissions are a major concern in healthcare management, often linked to poor patient outcomes and increased costs. The goal of this project is to predict patient readmission using structured clinical data, enabling proactive care and resource optimization.

---

## Dataset

The dataset includes the following features:

- `diagnosis`: Primary diagnosis of the patient
- `gender`: Gender of the patient
- `length_of_stay`: Duration of hospitalization
- `num_previous_admissions`: Number of prior hospitalizations
- `readmitted`: Target variable (Yes/No)

---

## Methodology

- Exploratory Data Analysis (EDA)
- Handling missing values
- One-Hot Encoding of categorical variables
- Train-test split (80/20)
- Addressing class imbalance using SMOTE
- Logistic Regression Model Training
- Model Evaluation using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1 Score)

---

## Results

- Model performance was improved significantly after applying SMOTE to balance the dataset.
- Logistic Regression achieved reasonable accuracy and improved recall for the minority class.
- Pneumonia and heart failure patients showed higher readmission rates, indicating potential areas for clinical intervention.

---

## Tools & Technologies

- Python 3.x
- Pandas, NumPy
- scikit-learn
- imbalanced-learn (SMOTE)

---

## Author

Vaishnavi Kanjarla  
Ph.D. Candidate | Healthcare AI Research | Clinical Data Science  
