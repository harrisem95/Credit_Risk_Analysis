# Credit Risk Analysis

## Overview of Project

### Purpose
Credit Risk is important to evaluate but also difficult because the inherent imbalances within the classes. We evaluated credit risk using different techniques. We performed oversampling using the RandomOverSampling and SMOTE algorightms, undersampling using the ClusterCentroids algorithm, and the SMOTTEENN algorithm which is a combination of under and oversampling. Lastly we compared two different ensemble classifiers, the BalancedRandomForestClassifier and EasyEnsembleClassifier. For each method we calculated the accuracy score and created a classification report to determine how it performed.

## Results

### Naive Oversampling

![Naive Oversampling](/Resources/Naive_Oversampling.png) 

1. Balanced Accuracy: 0.6571840065203901
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall High Risk: 0.71
4. Recall Low Risk: 0.60

### SMOTE Oversampling

![SMOTE Oversampling](/Resources/SMOTE_Oversampling.png) 

1. Balanced Accuracy: 0.6619848637108801
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall High Risk: 0.63
4. Recall Low Risk: 0.69

### ClusterCentroids Undersampling

![ClusterCentroids Undersampling](/Resources/ClusterCentroids_Undersampling.png) 

1. Balanced Accuracy: 0.5442369453268994
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall High Risk: 0.69
4. Recall Low Risk: 0.40

### SMOTEENN: Combination of Over and Undersampling

![SMOTEENN](/Resources/SMOTEENN.png) 

1. Balanced Accuracy: 0.6735758643684762
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall High Risk: 0.76
4. Recall Low Risk: 0.58

### Balanced Random Forest Classifier

![Balanced Random Forest Classifier](/Resources/BalancedRandomForestClassifier.png) 

1. Balanced Accuracy: 0.7885466545953005
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall High Risk: 0.70
4. Recall Low Risk: 0.87

### Easy Ensemble AdaBoost Classifier

![Easy Ensemble](/Resources/EasyEnsemble.png) 

1. Balanced Accuracy: 0.9316600714093861
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall High Risk: 0.92
4. Recall Low Risk: 0.94


## Results

### Conclusions 
After calculating the accuracy score and creating the classification reports for the above models, it is clear that the Easy Ensemble AdaBoost Classifier is the best model to use with a balanced accuracy score of 0.93, which is the closest to one. This model had the highest accuracy. It also had the highest recall risk. This would be the best machine learning model to use for future analysis.

