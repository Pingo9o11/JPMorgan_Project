# JPMorgan_Project

# Income Prediction & Segmentation Analysis

## Overview
This project analyzes demographic and employment factors associated with earning more than $50K annually using U.S. Census data. The goal is to identify key drivers of income, address class imbalance, and build robust predictive models suitable for real-world decision-making.

## Dataset
The dataset is derived from the U.S. Census Adult Income dataset and includes demographic, educational, and employment-related attributes. The target variable is a binary indicator of whether an individual earns more than $50K per year.

Key features include:
- Age
- Education
- Marital status
- Occupation
- Weeks worked per year

## Methodology
The analysis follows a structured pipeline:
- Exploratory data analysis (EDA) to understand distributions and nonlinear patterns
- Feature preprocessing including scaling and encoding
- Class imbalance handling using SMOTE and class weighting
- Predictive modeling using Logistic Regression and XGBoost

## Modeling
- Logistic Regression (baseline, interpretable)
- XGBoost with histogram-based tree construction and regularization
- Hyperparameters selected to balance performance and generalization

## Evaluation
Models are evaluated on a held-out test set using:
- ROC-AUC
- Precision, Recall, and F1-score
- Confusion matrix
- Probability-based ROC curves for threshold analysis

## Results
XGBoost outperformed the baseline model in terms of ROC-AUC and recall on the minority class, while maintaining stable precision. Cluster-level summaries reveal distinct demographic profiles associated with income levels.

## How to Run
1. Clone the repository:
   ```bash
   git clone <repo-url>
