## Project Overview
This project utilizes the PIMA Indians Diabetes dataset to build a predictive model using Support Vector Machine (SVM). The goal is to accurately classify whether a female patient is likely to have diabetes based on diagnostic health attributes.
Dataset Information
The dataset contains several medical predictors and one target variable:
Features include: Number of Pregnancies, Glucose Concentration, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
Target Variable:
Outcome (1 = diabetes, 0 = no diabetes)

Technologies & Libraries
Python (Jupyter Notebook)
pandas, numpy
matplotlib, seaborn
scikit-learn (SVM, preprocessing, evaluation metrics)

Preprocessing Steps
Missing values handled (zero values treated in relevant columns)
Feature scaling using StandardScaler
Train-Test Split (typically 70%-30%)

 Model Used
Support Vector Machine (SVM)
Kernel tuning:Linear, Radial Basis Function (RBF), Polynomial

Evaluation Metrics: Accuracy Score, Confusion Matrix, Classification Report (Precision, Recall, F1-Score), ROC-AUC Curve

 Results
Best performance observed with RBF kernel.
ROC-AUC and F1-score used to assess robustness.

Goal
To build a reliable and accurate diabetes prediction model that can assist healthcare professionals with early detection, potentially improving patient outcomes.
