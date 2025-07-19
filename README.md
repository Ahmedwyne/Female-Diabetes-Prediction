# 👩‍⚕️ Female Diabetes Prediction

This project predicts the likelihood of diabetes in adult female patients using machine learning algorithms. It utilizes the [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database), which contains diagnostic measurements from a study of women of Pima Indian heritage.

## 📌 Overview

The goal is to classify whether a patient has diabetes (`1`) or not (`0`) based on a set of medical predictor variables. This project involves:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature selection
- Model training and evaluation using several classifiers

## 📁 Files

- `female-diabetes-prediction.ipynb` – Jupyter notebook with:
  - Data loading and exploration
  - Preprocessing (handling zeros, normalization, encoding)
  - Training models like Logistic Regression, KNN, Random Forest, etc.
  - Performance evaluation

## 📊 Dataset Description

📍 **Source**: [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

The dataset contains 768 observations with 8 input features and 1 binary output (diabetes or not). All patients are female and at least 21 years old.

### Features

- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skinfold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function
- `Age`: Age (years)
- `Outcome`: Class variable (0 = no diabetes, 1 = diabetes)

## 🧠 Machine Learning Models Used

- Random Forest

Each model is evaluated using accuracy, confusion matrix, and classification metrics (precision, recall, F1-score).
