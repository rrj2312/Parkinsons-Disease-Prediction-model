# Parkinson’s Disease Prediction using Machine Learning

## Project Overview
This project focuses on predicting Parkinson’s Disease using machine learning techniques applied to biomedical voice measurements. Parkinson’s is a neurodegenerative disorder, and early detection through data-driven methods can support clinical decision-making.

The goal of this project is to build, evaluate, and interpret a classification model that can distinguish between healthy individuals and patients with Parkinson’s Disease.

## Dataset
* The dataset consists of biomedical voice features extracted from speech signals.
* Each record represents a subject with multiple numerical features related to vocal frequency, jitter, shimmer, and noise components.
* Target variable:
  * 0 → Healthy
  * 1 → Parkinson’s Disease

## Methodology
1. Data Preprocessing
** Checked for missing values
** Feature scaling applied where necessary
** Target variable separated for supervised learning

2. Model Used
** Logistic Regression
** Chosen for its interpretability and effectiveness in binary classification problems
** Suitable for medical datasets where explainability matters

3. Evaluation Metrics
** Accuracy
**Confusion Matrix
** Precision, Recall, and F1-Score
** Weighted and Macro averages for balanced performance analysis

## Model Performance
### Accuracy
Accuracy Score: 0.8974

### Confusion Matrix
[[11  3]
 [ 1 24]]
** True Negatives: 11
** False Positives: 3
** False Negatives: 1
** True Positives: 24

## Key Observations
** The model achieves ~90% accuracy, indicating strong predictive capability.
** High recall (96%) for Parkinson’s cases, which is critical in medical diagnosis to minimize false negatives.
** Balanced precision and recall across both classes.
