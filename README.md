# Credit_Risk_Analysis

## Overview
Using various machine learning algorithms to predict credit risk.

## Results

### Naive Random Oversampling

Balanced Accuracy: 64.98%

Precision: 0.97% 

Recall: 62.07%

<img width="387" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/89493488/148664307-574dd636-ae0e-4ff5-a818-e6b07b08647d.png">

### SMOTE Oversampling

Balanced Accuracy: 64.44% 

Precision: 0.93% 

Recall: 63.22%

<img width="315" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/89493488/148664316-1c55fdb9-52d2-4ddb-b8fe-511460a99e2b.png">

### Undersampling

Balanced Accuracy: 51.58%

Precision: 0.53%

Recall: 59.77%

<img width="387" alt="Undersampling" src="https://user-images.githubusercontent.com/89493488/148664320-68e4770c-3339-4016-a72c-81e7f78193d5.png">

### (Over and Under) Sampling

Balanced Accuracy: 63.76%

Precision: 0.83%

Recall: 70.11%

<img width="393" alt="(Over and Under) Sampling" src="https://user-images.githubusercontent.com/89493488/148664323-876f298b-8f4a-4523-896c-6258ff7121d1.png">

### Balanced Random Forest Classifier

Balanced Accuracy: 78.78%

Precision: 3.58%

Recall: 66.67%

<img width="570" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/89493488/148664330-b3c281ff-356a-43c0-bbc9-6919cfc348e6.png">

### Easy Ensemble AdaBoost Classifier

Balanced Accuracy: 92.54%

Precision: 7.47%

Recall: 90.8%

<img width="416" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/89493488/148664335-441a2bb3-a143-4fda-bc15-8bd604fe1ddb.png">

## Summary

I recommend the Easy Ensemble AdaBoost Classifier model because it had the highest recall percentage at 90.8%. This means this model accurately predicted credit risk in applicants 90.8% of the time. This is signfiicantly better than any of the other machine learning models, with the next highest being at 70.11%.
