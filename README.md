# Credit_Risk_Analysis

## Overview of Analysis

The purpose of this project was to create a machine learning model which can predict which loan applications carry a high risk and which carry low risk. Various machine learning techniques were used to see which type of model is best at predicting loan risk, to varying results. The different methods are as follows:
- Naive Random Oversampling
- SMOTE Oversampling
- Cluster Centroid Undersampling
- SMOTEENN Sampling
- Balanced Random Forest Classifying
- Easy Ensemble Classifying

The data were divided into training and testing sets and then given accuracy scores, precision scores, and confusion matrices and classification reports were generated.

## Results

### Naive Random Oversampling
- Balanced Accuracy: 66%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 72%
- Recall Low Risk: 60%

### SMOTE Oversampling
- Balanced Accuracy: 66.3%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 63%
- Recall Low Risk: 69%

### Undersampling
- Balanced Accuracy: 66.3%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 69%
- Recall Low Risk: 40%

### Combination (Over and Under) Sampling
- Balanced Accuracy: 54.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 72%
- Recall Low Risk: 57%

### Balanced Random Forest Classifier
- Balanced Accuracy: 78.9%
- Precision High Risk: 3%
- Precision Low Risk: 100%
- Recall High Risk: 70%
- Recall Low Risk: 87%

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy: 93.2%
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Recall High Risk: 92%
- Recall Low Risk: 94%

## Summary
These models are attempting to detect high risk loans. Each ML model in this project calculated the accuracy, precision, and recall (sensitivity) of this dataset using different means, and the goal is to decide which model is the most accurate to detect high risk loans. Of these models, the Easy Ensemble AdaBoost Classifier provided the highest accuracy, precision of high risk, and sensitivity of high and low risk, indicating that this model is the best to detect the risk levels of loans.
