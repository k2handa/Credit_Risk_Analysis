# Credit_Risk_Analysis

## Overview
We have been tasked to determine credit card risk, in general credit risk inherently has unbalanced classification. so we will have to administer a series of tests to properly determine risk. using techniques such as machine learning and algorithms to predict credit risk to a higher certainty. we will be using the following to determine the best possible test and technique to give us the most accurate results.

* Oversampling the data using RandomOverSampler & SMOTE

* Undersampling the dats using ClusterCentroids

* using a combination of under and over sampling using SMOTEEN

* finally compare BalancedRandomForestClassifier and EasyEnsembleClassifier Machine Learning in hopes of reducing the bias to help predict the risk

## Results

### RandomOverSampler

* Balanced accruacy = 0.654

* Precision score = 0.01

* Recall Score = 0.66(high) & 0.65(low)

### SMOTE Oversampling

* Balanced accruacy = 0.648

* Precision score = 0.01

* Recall Score = 0.61(high) & 0.68(low)

### ClusterCentroids Undersampling 

* Balanced accruacy = 0.539

* Precision score = 0.01

* Recall Score = 0.66(high) & 0.42(low)

### Combination Sampling with SMOTEENN

* Balanced accruacy = 0.644

* Precision score = 0.01

* Recall Score = 0.70(high) & 0.58(low)

### Balanced Random Forest Classifier

* Balanced accruacy = 0.734

* Precision score = 0.08

* Recall Score = 0.50(high) & 0.96(low)

### Ensemble Adaboost Classifier

* Balanced accruacy = 0.920

* Precision score = 0.09

* Recall Score = 0.89(high) & 0.95(low)

## Summary 

The Highest Balanced accuracy comes from the Ensemble AdaboostClassifier with 0.920, the lowest balanced accuracy comes from Cluster Centroids Undersampling at 0.539

Ensemble Adaboost Classifier precision score was the highest at 0.09, followed by the Balanced Random Forest Cklassifier at 0.08. 

Ensemble Adaboost Classifier has the highest recall scores at 0.89(high risk) and 0.95(low risk)

taking all of this into consideration, its suffice to say that Ensemble Adaboost model is the best to use to predict credit risk for the organizaion. 


`

