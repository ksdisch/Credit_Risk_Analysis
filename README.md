# Credit Risk Analysis

## Overview
The purpose of this analysis was to use various supervised machine learning models to predict credit risk for potential clients. The models used included Logistic Regression, Balanced Random Forest, and Easy Ensemble. Additionally, re-sampling techniques such as Oversampling/SMOTE, Undersampling/Cluster Centroids, and SMOTEEN were used to resample the data to account for the fact that good loans easily outnumber risky loans. Finally, balanced accuracy scores, classification reports, and confusion matrixes were used to evaluate and compare the models and/or re-sampling techniques were used to determine which were best suited for this dataset.

## Results

### Naive Random Oversampling

![naive oversample](images/naive_oversample.png?raw=true "Title")

- Balanced Accuracy Score: 59.28%
- Precision Score: 99%
- Recall Score: 65%

### SMOTE Oversampling

![SMOTE oversample](images/SMOTE.png?raw=true "Title")

- Balanced Accuracy Score: 59.28%
- Precision Score: 99%
- Recall Score: 65%

### Cluster Centroids Undersampling
![cluster centroids undersample](images/cluster_centroids.png?raw=true "Title")

- Balanced Accuracy Score: 48.39%
- Precision Score: 99%
- Recall Score: 48%

### SMOTEENN Combination Over/Undersampling 
![over/under combination](images/overunder_combo.png?raw=true "Title")

- Balanced Accuracy Score: 64.39%
- Precision Score: 99%
- Recall Score: 57%

### Balanced Random Forest Classifier
![balanced forest](images/balanced_forest.png?raw=true "Title")

- Balanced Accuracy Score: 78.19%
- Precision Score: 99%
- Recall Score: 92%

### AdaBoost Classifier
![AdaBoost](images/adaboost.png?raw=true "Title")

- Balanced Accuracy Score: 92.54%
- Precision Score: 99%
- Recall Score: 94%

## Summary
The balanced accuracy scores of the different models from best to worst were: AdaBoost Classifier, Balanced Random Forest Classifier, SMOTEENN Combination Over/Undersampling, SMOTE Oversampling, Naive Random Oversampling, and Cluster Centroids Undersampling. Based on these results, I would recommend using the AdaBoost Classifier model for predicting credit risk with this dataset. Along with the best balanced accuracy score, this model also had impressive precision and recall scores relative to the other models. 
