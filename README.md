# ML_Models_for_Smart_Finance_Predicting_Corporate_Bankruptcy

## Introduction
This project focuses on predicting bankruptcy in companies using machine learning models. Bankruptcy prediction is crucial for the financial sector, as it helps identify companies at risk of financial distress. In this study, we explore different machine learning algorithms, preprocess the data, and evaluate model performance.

## Table of Contents
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Selection](#model-selection)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

## Dataset
We use the "company_bankruptcy.csv" dataset, which contains financial and non-financial features of various companies. The target variable is "Bankrupt?" (1 for bankrupt, 0 for non-bankrupt).

## Data Preprocessing
Data preprocessing steps include handling missing values, outlier detection and removal, and feature scaling using RobustScaler.

## Exploratory Data Analysis
We explore the dataset's shape, data types, and distribution of the target variable. Understanding the data is crucial for building accurate models.

## Feature Engineering
We use PCA to select the most important features that impact the target variable. Dimensionality reduction helps improve model efficiency.

## Model Selection
We experiment with different machine learning models, including Decision Trees, Random Forest, Logistic Regression, and Gradient Boosting, to find the best-performing model.

## Model Evaluation
We evaluate model performance using metrics such as accuracy, recall, precision, and F1-score. We also visualize the results with confusion matrices.

## Conclusion
This study provides insights into predicting bankruptcy in companies using machine learning models. The best-performing model can assist financial institutions in identifying companies at risk of bankruptcy.

Feel free to explore the code and results in this repository to gain a better understanding of the project.

