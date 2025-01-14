# Online Payment Fraud Detection

This project aims to detect fraudulent online payment transactions for Blossom Bank using machine learning models. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model selection, and evaluation to build a robust fraud detection system.

## Project Overview

Fraud detection is a critical task in the financial sector. This project focuses on identifying fraudulent transactions using various machine learning algorithms. The process involves analyzing transaction data, extracting meaningful features, and applying classification models to predict fraudulent activities.

## Dataset

The dataset contains transaction details such as amount, transaction type, and other relevant features. The target variable indicates whether a transaction is fraudulent or legitimate.

## Key Steps

1. **Data Preprocessing**: 
   - Handling missing values
   - Encoding categorical features
   - Normalizing numerical features

2. **Exploratory Data Analysis (EDA)**:
   - Univariate and bivariate analysis to understand data distributions and relationships
   - Visualization of key features and trends

3. **Feature Engineering**:
   - Creation of new features to improve model performance
   - Selection of important features using correlation analysis

4. **Model Selection and Evaluation**:
   - Implemented models: Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest
   - Model performance:
     - Logistic Regression: Accuracy = 0.986
     - K-Nearest Neighbors: Accuracy = 0.99
     - Decision Tree: Accuracy = 0.992, Recall Cross-Validation = 0.8318
     - Random Forest: Accuracy = 0.994, Recall Cross-Validation = 0.6
   - Cross-validation and hyperparameter tuning for model optimization

## Results

- The Random Forest Classifier achieved the highest accuracy of 0.994.
- Decision Tree Classifier showed a good balance between accuracy and recall with a cross-validation recall score of 0.8318.




