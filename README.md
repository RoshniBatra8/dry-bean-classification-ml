# Dry Bean Multiclass Classification

## Project Overview
This project focuses on multiclass classification of the Dry Bean Dataset (13,611 samples across 7 classes). The objective was to compare multiple machine learning models and select the most balanced and reliable classifier while addressing class imbalance.

## Dataset
- Source: UCI Machine Learning Repository
- 13,611 samples
- 16 numerical features
- 7 bean types
- No missing values

## Feature Engineering
The following features were engineered to enhance model performance:
- Area_Perimeter_Ratio
- Shape_Index
- Eccentricity_Squared

A stratified train-test split was applied to maintain class balance.

## Models Tested
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Decision Tree

## Evaluation Metrics
- Accuracy
- Macro Precision
- Macro Recall
- Macro F1-Score
- ROC AUC (Macro)

Macro F1-score was prioritized due to dataset imbalance.

## Final Results
Support Vector Machine achieved the highest **Macro F1-score of 93.25%**, demonstrating balanced performance across all classes.

## Key Learnings
- Feature engineering significantly impacts model performance.
- Accuracy alone is not reliable for imbalanced datasets.
- Balanced metrics are essential for fair model selection.
