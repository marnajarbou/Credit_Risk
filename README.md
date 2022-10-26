# Credit_Risk
Using Python-built machine learning models for modeling and assessing credit risk

## Overview
I oversampled the data using the RandomOverSampler and SMOTE algorithms and under sampled the data using ClusterCentroids using the credit card credit dataset from LendingClub, a peer-to-peer lending service provider. Our next strategy comprised combining over- and under-sampling using the SMOTEENN algorithm. We contrasted the performance of BalancedRandomForestClassifier and EasyEnsembleClassifier, two new machine learning models for predicting credit risk. Based on these findings, we assessed the models' effectiveness and issued a written recommendation regarding their suitability for predicting credit risk.

## Results

### Naive Random Oversampling
- The Balanced Accuracy Score is 66%
- Precision high risk score is only 1% and low risk score is 100%
- Recall score for hight risk is at 66% and low risk at 67%

### SMOTE Oversampling
- The Balanced Accuracy Score is again 66%
- Precision high risk score is only 1% and low risk score is 100%
- Recall score for hight risk is at 62% and low risk at 64%

### Undersampling Cluster Centroids Algorithm
- The Balanced Accuracy Score is at 63%
- Precision high risk score is only 1% and low risk score is 100%
- Recall score for hight risk is at 61% and low risk at 65%

### SMOTEENN Model
- The Balanced Accuracy Score is at 52%
- Precision high risk score is 1% and low risk score is 100%
- Recall score for hight risk is at 70% and low risk at 57%

### Balanced Random Forest Classifier
- The Balanced Accuracy Score is at 82%
- Precision high risk score is 4% and low risk score is 100%
- Recall score for hight risk is at 72% and low risk at 91%

### Easy Ensemble AdaBoost Classifier
- The Balanced Accuracy Score is at 91%
- Precision high risk score is 7% and low risk score is 100%
- Recall score for hight risk is at 90% and low risk at 94%

## Summary
EasyEnsembleClassifier has a Balanced Accuracy Score of 91% as a measure of its capacity to identify high risk credit and low risk scores. As a result, this model can be suggested. Compared to EasyEnsembleClassifier, other models used to analyze credit risk have a lack of precision.
