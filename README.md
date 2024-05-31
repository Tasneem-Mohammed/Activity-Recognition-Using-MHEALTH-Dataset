# **Comparative Analysis of Machine Learning Models for Activity Recognition Using MHEALTH Dataset**

## Overview
This project compares the performance of different machine learning models for activity recognition using the MHEALTH dataset. Models evaluated include K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Neural Networks (NN), Logistic Regression, and Linear Regression.

## Tools and Technologies
- **Languages:** Python
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Keras
- **Data Source:** MHEALTH dataset from Kaggle

## Project Steps

### 1. Dataset Exploration
- **Data Loading:** Loaded MHEALTH dataset from Kaggle.
- **Data Cleaning:** Checked for missing values and duplicates, and balanced the dataset.
- **Data Visualization:** Used correlation heatmaps and scatter plots to visualize data points.

### 2. Data Preprocessing
- **Feature Scaling:** Standardized features using `StandardScaler`.
- **Data Splitting:** Split data into training and testing sets.

### 3. Model Training
- **KNN:** Tuned hyperparameters (k values) and evaluated accuracy.
- **SVM:** Implemented with RBF kernel, evaluated accuracy.
- **Neural Networks:** Built a sequential NN with two hidden layers, evaluated accuracy.
- **Logistic Regression:** Used GridSearchCV for hyperparameter tuning, evaluated accuracy.
- **Linear Regression:** Trained and evaluated accuracy.

### 4. Model Evaluation
- **Metrics:** Accuracy, confusion matrix, and classification report.
- **Visualization:** Plotted bar and line charts to compare model accuracies.

### 5. Results Analysis
- **Best Model:** SVM achieved the highest accuracy (95.4%).
- **Insights:** Discussed strengths and weaknesses of each model.

## Results Summary
- **KNN Accuracy:** 94.82%
- **SVM Accuracy:** 95.40%
- **Neural Network Accuracy:** 92.11%
- **Logistic Regression Accuracy:** 54.26%
- **Linear Regression Accuracy:** 25%

## Conclusion
The SVM model emerged as the best performer for activity recognition using the MHEALTH dataset due to its ability to handle complex data and high accuracy.

## Date
- **Date:** 11/5/2024.
