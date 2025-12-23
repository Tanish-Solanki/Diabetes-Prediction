# Diabetes Prediction using Machine Learning

A machine learning–based classification project that predicts whether a person is diabetic based on medical attributes.  
The project compares multiple classification models and selects the best-performing one using cross-validation and hyperparameter tuning.

---

## Problem Statement
Diabetes is a chronic disease that requires early diagnosis for effective treatment.  
This project aims to predict diabetes using patient medical data by applying supervised machine learning classification techniques.

---

## Dataset
The dataset contains medical attributes such as:
- Glucose level
- Blood pressure
- BMI
- Insulin
- Age

The target variable indicates whether the patient is diabetic or not.

---

## Models Implemented
The following classification models are trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

Model selection is performed using **GridSearchCV** with cross-validation.

---

## Methodology
1. Data loading and preprocessing
2. Feature selection and splitting into training and testing sets
3. Model training using multiple classifiers
4. Hyperparameter tuning using GridSearchCV
5. Performance comparison based on cross-validation score
6. Selection of the best-performing model

---

## Technologies & Libraries
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
