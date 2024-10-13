# Heart-disease-prediction-using-machine-learning

This project implements several machine learning models to predict heart disease based on medical data. The goal is to evaluate different classifiers and identify the best model for accurate heart disease prediction.

## Purpose

The goal of this project is to predict the presence of heart disease using multiple machine learning classifiers. Various models are trained and compared, with a Stacking Classifier providing the best accuracy.

## Features

- **Data Preprocessing**:
   - Standardized the dataset using `StandardScaler`.
   - Split into training and test sets to ensure robust model evaluation.
  
- **Models Used**:
   - **K-Nearest Neighbors (KNN)**
   - **Support Vector Classifier (SVC)**
   - **Naive Bayes**
   - **Decision Trees**
   - **Random Forest**
   - **AdaBoost**
   - **Stacking Classifier**: Combines predictions from multiple models to improve accuracy.

- **Evaluation**:
   - Classification reports and confusion matrices are used to compare models.
   - Performance metrics such as accuracy, precision, recall, and F1-score are calculated for all models.

## Sections

1. **Data Preprocessing**:
   - Cleaned and standardized the data for input into machine learning models.
   - Split the data into training and test sets for evaluation.
2. **Model Training**:
   - Trained multiple classifiers such as KNN, Random Forest, and more.
   - Implemented a Stacking Classifier to combine the outputs of various base models.
3. **Model Evaluation**:
   - Generated classification reports and confusion matrices to evaluate performance.
   - The **Stacking Classifier** achieved the highest accuracy of 0.87 on the test set.
