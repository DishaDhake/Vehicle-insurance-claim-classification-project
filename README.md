# Vehicle Insurance Claims Classification Project

This project predicts whether a vehicle insurance policyholder will file a claim within the next 6 months. The project involves data preprocessing, model training, and evaluation using various machine learning techniques. It leverages Python libraries such as Scikit-learn, Imbalanced-learn, Matplotlib, and Seaborn for data processing, model training, and result visualization.

## Project Overview

- **Location**: Albany, NY
- **Duration**: October 2023 - November 2023
- **Objective**: Predict vehicle insurance claims using various machine learning algorithms.

## Project Workflow

1. **Data Preprocessing**:
   - Loaded and cleaned insurance claim data.
   - Removed irrelevant columns and handled missing values.
   - Encoded categorical variables and created new features.
   - Balanced the dataset using SMOTE (Synthetic Minority Over-sampling Technique) to ensure a well-represented minority class.

2. **Model Training**:
   - Split the preprocessed dataset into training and validation sets.
   - Trained multiple machine learning models, including Logistic Regression, Naive Bayes, Decision Trees, and XGBoost.
   - Optimized model parameters to enhance predictive performance.

3. **Model Evaluation**:
   - Evaluated models based on **Accuracy**, **Precision**, **Recall**, **F1 Score**, and **AUC-ROC**.
   - Visualized the ROC curve to assess model performance.

## Key Findings

- Achieved high predictive accuracy and robustness across multiple models.
- Successfully balanced the dataset, which led to improved recall and precision.
- XGBoost and Decision Trees showed the most promising results, with high AUC-ROC scores and accuracy.

