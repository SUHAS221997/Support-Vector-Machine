Diabetes Prediction Using Support Vector Machine (SVM)

This repository contains a project that uses the Support Vector Machine (SVM) algorithm to predict diabetes based on a given dataset of medical features. The project demonstrates the use of SVM for classification tasks and includes data preprocessing, model training, hyperparameter tuning, and evaluation.

Diabetes Prediction Using Support Vector Machine (SVM)

This repository contains a project that uses the Support Vector Machine (SVM) algorithm to predict diabetes based on a given dataset of medical features. The project demonstrates the use of SVM for classification tasks and includes data preprocessing, model training, hyperparameter tuning, and evaluation.

Dataset

The dataset used in this project is a diabetes dataset containing medical records of individuals. The target variable indicates whether or not a person has diabetes.

Features:
1. Pregnancies: Number of times pregnant
2. Glucose: Plasma glucose concentration
3. BloodPressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skinfold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body Mass Index (weight in kg/(height in m)^2)
7. DiabetesPedigreeFunction: Diabetes pedigree function (family history risk)
8. Age: Age of the individual
9. Outcome: 0 (No diabetes) or 1 (Diabetes)


Objective

The objective of this project is to use SVM to classify individuals as diabetic or non-diabetic based on their medical features.

Key Components

Data Preprocessing: Handles missing values, feature scaling, and data splitting.

SVM Implementation:
1. Linear and non-linear classification using kernel functions (e.g., linear, RBF).
2. Hyperparameter tuning with grid search for parameters like C and gamma.

Model Evaluation:
1. Accuracy, precision, recall, F1-score.
2. Confusion matrix visualization.
