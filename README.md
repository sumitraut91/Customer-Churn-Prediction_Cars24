# Customer-Churn-Prediction_Cars24
## Overview

This project focuses on predicting customer churn using machine learning models and extracting actionable insights from the dataset. The deliverables include a Jupyter Notebook/Python script, visualizations, and reports summarizing findings and recommendations.

## How to Use

### Prerequisites

Python 3.8 or higher.

Required libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost

## Installation

Clone the repository or download the project files.

## Dataset

Ensure the dataset (customer_data_1000.csv) is located in the same directory as the script or notebook.

## Steps to Run

1. Jupyter Notebook

Open the Customer_Churn_Analysis.ipynb file in Jupyter Notebook or any compatible IDE.

Execute the cells sequentially to:

Load and explore the dataset.

Perform feature engineering.

Train and evaluate models.

Generate visualizations.

2. Outputs:

Model evaluation metrics (accuracy, precision, recall, F1-score, AUC-ROC).

Generated visualizations saved in the outputs/ directory.

## Assumptions

All missing values in the dataset are treated using median imputation.

Categorical features are encoded using one-hot encoding.

Data normalization is applied only to features with significant scale differences.

New features such as Income-to-Spending Ratio and Age Group are included for enhanced predictive power.

## Outputs

PDF Report: Summarizes the analysis, findings, and recommendations.

PowerPoint Presentation: Provides a visual summary of key insights and strategies.

Visualizations: Key plots generated during analysis, including:

Churn rate by age group.

Feature importance (Random Forest).

Feedback score distribution by churn status.
