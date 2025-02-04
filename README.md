# Wine Quality Prediction Using Machine Learning

## Project Overview
This project aims to develop a predictive model to estimate wine quality based on physicochemical properties. Using machine learning techniques, multiple classifiers were built and evaluated to identify the best model for distinguishing high-quality and low-quality wines.

## Data & Preprocessing
- **Dataset**: Portuguese red wine dataset from the UCI Machine Learning Repository.
- **Features**: 11 physicochemical properties (e.g., acidity, alcohol content, sulphates).
- **Target Variable**: Wine quality score (3–8), converted into a binary classification (good/bad).

### Preprocessing:
- Handled missing and duplicate values.
- Removed weakly correlated features.
- Applied outlier filtering using quantile-based thresholds.

## Machine Learning Models
The following models were implemented and evaluated:
- **Logistic Regression** (Best Performance)
- **Decision Tree Classifier**
- **Naive Bayes**
- **Support Vector Machine (SVM)**
- **AutoML (TPOTClassifier)**

## Results & Evaluation
- **Best Model**: Logistic Regression & TPOTClassifier (AUC-ROC: 0.88).

### Key Insights:
- Higher alcohol content correlates with better quality.
- Higher volatile acidity lowers wine quality.
- Sulphates and citric acid positively impact wine ratings.
