# Credit_Risk_Analysis

## Challenge Overview 

This challenge applies machine learning to a real world challenge-- predicting credit card risk. This is useful for determining good candidates for a loan, which can lead to lower default rates as well as provide more reliable experience. 

**The supervised machine learning models used were:**

* Naïve Random Oversampling
* SMOTE Oversampling
* Cluster Centroids Undersampling
* SMOTEENN Combination (Over and Under) Sampling
* Balanced Random Forest Classifier
* Easy Ensemble ADABoost Classifier

Deliverable 1: Use Resampling Models to Predict Credit Risk

Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

 ## Results
 
 ### Naive Random Oversampling
 
 ![naive random oversampling](https://user-images.githubusercontent.com/86750935/139603200-4018cecb-1256-43c2-8539-fcb0064027c7.PNG)

* Balanced Accuracy Score: 65.72%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 71%
* Recall Low risk: 60%

### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/86750935/139603332-f1fac64c-0a34-4156-8aa4-1994c6a77b03.PNG)

* Balanced Accuracy Score: 65.2%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 62%
* Recall Low risk: 68%

### Cluster Undersampling

![cluster undersampling](https://user-images.githubusercontent.com/86750935/139603398-025a0c91-d4a8-40d7-ad46-8c1929e1b63d.PNG)

* Balanced Accuracy Score: 54.42%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 69%
* Recall Low risk: 40%

### SMOTEENN Combination (Over and Under) Sampling

![SMOTEENN Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/86750935/139603599-527dfba3-93e6-40a8-900a-b0ed671bc405.PNG)

* Balanced Accuracy Score: 64.02%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 71%
* Recall Low risk: 58%

### Random Forest Classifier

![balanced random forest classifier](https://user-images.githubusercontent.com/86750935/139603888-07f3bdb1-0087-4702-83b7-69a648740bc0.PNG)

* Balanced Accuracy Score: 78.875%
* Precision High Risk: 3%
* Precision Low Risk: 100%
* Recall High Risk: 70%
* Recall Low risk: 87%

### Easy Ensemble AdaBoost Classifier

![Easy Ensemble](https://user-images.githubusercontent.com/86750935/139603951-fc980547-0d26-4997-a7d1-62520517622f.PNG)

* Balanced Accuracy Score: 93.16%
* Precision High Risk: 9%
* Precision Low Risk: 100%
* Recall High Risk: 92%
* Recall Low risk: 94%

## Summary

All the models used to perform these analysis show weak precision in determining if a credit risk is high. The Ensemble models were more accurate on the sensitivity of high credit risks, and the last model used shows a recall of 92%--indicating almost all high credit risk. I would not recommend the usage of these models for this reason.
