# Maternal Risk Prediction ML Project

## Overview
This project builds a **multiclass maternal health risk prediction model** (Low, Mid, High risk) using machine learning.  
The goal is to support maternal healthcare by identifying risk levels early and providing interpretable results.

## Features
- Logistic Regression with **L2 regularization** for stability against multicollinearity.
- Preprocessing pipeline:
  - Outlier detection (IQR)
  - Feature scaling
  - Multicollinearity checks (heatmap)
- Evaluation metrics: **Precision, Recall, F1-score, Confusion Matrix**.
- Addressed class imbalance with stratified sampling and class weights.

## Results
- Achieved **F1-score of 0.73 for High Risk classification**.
- Strong performance for Low and High risk categories; Mid risk is still a challenge.

