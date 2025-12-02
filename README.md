# Default Prediction using SVM Algorithm
## Overview

This repository implements a Support Vector Machine (SVM) model to predict credit default risk, a core use-case in quantitative finance and risk analytics.
The project demonstrates the application of machine learning methods in credit risk modelling .

## Key Objectives

- Build a predictive model for default vs. non-default classification.

- Apply SVM (linear, polynomial, RBF kernels) to credit risk datasets.

- Perform rigorous feature engineering, model tuning, and evaluation.

- Demonstrate the ability to combine ML techniques with banking/domain knowledge.

## Topics Covered
1. **Understanding the Credit Risk Dataset**

- Borrower attributes (demographics, financial ratios, credit history).

- Target variable: Default (1) or No Default (0).


2. **Data Preprocessing & Feature Engineering**

- Train-test split

- Scaling using StandardScaler


3. **SVM Model Implementation**

- Comparison across different kernel functions:

✔ Linear SVM

Interpretable coefficients

Suitable for near-linearly separable data

✔ Polynomial Kernel SVM

Captures moderate non-linear relationships

✔ RBF Kernel SVM

Most flexible

Best results for non-linear credit behaviour patterns

4. **Model Evaluation**

- Accuracy

- Precision, Recall, F1-score

- ROC curve & AUC metric

- Confusion matrix

Discussion on Type I and Type II errors in context of credit risk

Type I (False Negative): Missing a defaulter → Very costly for banks

Type II (False Positive): Predicting default for good borrower → Lost business
