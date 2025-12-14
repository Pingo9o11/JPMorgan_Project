# JPMorgan_Project
gi 

# Income Prediction & Segmentation Analysis

## Overview
This project analyzes demographic and employment factors associated with earning more or less than $50K annually using U.S. Census data. The goal is to identify key drivers of income, address class imbalance, and build robust predictive models suitable for marketing focussed decision-making.

## Dataset
The dataset is derived from the U.S. Census Adult Income dataset and includes demographic, educational, and employment-related attributes. The target variable is a binary indicator of whether an individual earns more than $50K per year.


## Methodology
The analysis follows a structured pipeline:
- Exploratory data analysis (EDA) to understand distributions and nonlinear patterns
- Feature preprocessing including scaling and encoding
- Class imbalance handling using SMOTE and class weighting
- Predictive modeling using Logistic Regression and XGBoost
- Segmentation Modeling and Evaluation

## Modeling
- Logistic Regression, Random Forest (baseline, interpretable)
- XGBoost with regularization
- Hyperparameters selected to balance performance and generalization

## Evaluation
Models are evaluated on a held-out test set using:
- Accuracy
- ROC-AUC
- Precision, Recall, and F1-score
- Confusion matrix
- Probability-based ROC curves for threshold analysis

## Results
XGBoost outperformed the baseline model in terms of ROC-AUC and recall on the minority class, while maintaining stable precision. Cluster-level summaries reveal distinct demographic profiles associated with income levels.

## How to Run
1. Clone the repository:
   ```bash
   git clone <https://github.com/Pingo9o11/JPMorgan_Project.git>
