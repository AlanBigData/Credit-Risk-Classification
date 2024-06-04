# Alan Lawrence
# Module 20
# Credit Risk Classification

## Project Overview
The objective of this project is to leverage various machine learning techniques to develop and evaluate Logistic Regression Models for identifying the creditworthiness of borrowers. The models are trained on a dataset containing features that help predict whether a loan is healthy (`0`) or high-risk (`1`).

## Methodology
The project follows these steps:

1. **Data Preparation:** The dataset is split into features and labels, further divided into training and testing sets.
  
2. **Model Construction:**
   - **Machine Learning Model 1:** A logistic regression model is trained on the original training data (`X_train`, `y_train`).
   - **Machine Learning Model 2:** The original training data is resampled using the `RandomOverSampler` module to handle class imbalance. A logistic regression model is then trained on the resampled data.

## Results
### Machine Learning Model 1:
- Accuracy: 94.4%
- Precision (High-risk loans): 0.87
- Recall (High-risk loans): 0.89

### Machine Learning Model 2:
- Accuracy: 99.6%
- Precision (High-risk loans): 0.87
- Recall (High-risk loans): 1.00

## Summary  
The comparison reveals that **Model 2** surpasses Model 1 in predicting high-risk loans and demonstrates higher overall accuracy. Notably, Model 2 achieves a significant improvement in recall, correctly identifying all high-risk loans. Therefore, **Model 2** is recommended for identifying high-risk loans due to its enhanced performance and superior accuracy.
