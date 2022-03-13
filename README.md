# Credit_Risk_Analysis
Machine Learning Models
## Overview
The purpose of this analysis was to create a supervised machine learning model that could accurately predict credit risk alalysis, After data cleaning.

### Basic Cleaned Data 
![cleaned_data](./Module-17-Challenge-Resources/Resources/cleaned_data.png)

  
split my data using the resampled data to train and test a logistic regression model. Also, calculated balanced accuracy scores then printed confusion matrix and finally generated classification reports as results.
### Split Data into Trainingand Testing
![split_training_testing](./Module-17-Challenge-Resources/Resources/split_training_testing.png)

## Results

### Naive Random Oversampling
![naive_random_oversampling](./Module-17-Challenge-Resources/Resources/naive_random_oversampling.png)

### SMOTE Oversampling
![smote_sampling](./Module-17-Challenge-Resources/Resources/smote_sampling.png)

### Cluster Centroid Undersampling
![undersampling](./Module-17-Challenge-Resources/Resources/undersampling.png)

### SMOTEENN Sampling
![over_under_sampling](./Module-17-Challenge-Resources/Resources/over_under_sampling.png)

### Balanced Random Forest Classifying
![balanced_randomforest_classifier](./Module-17-Challenge-Resources/Resources/balanced_randomforest_classifier.png)

- Also, sorted importance and features in descending order.
 
![descending_feature_importance](./Module-17-Challenge-Resources/Resources/descending_feature_importance.png)



## Summary
This analysis is trying to find the best model for loan risk. We need to find a model that lets the least amount of high risk loans. Sampling the models, the scored highest were:
  - Easy Ensemble model has the highest accuracy score (0.93) and the F-1 score for low risk (0.97) is also the highest.
    - The recommended model for credit card analysis would be the Easy Ensemble model.
  - Balanced Random Rainforest model has the second highest accuracy score at 0.79 and the F-1 low score is 0.93.
  - Naïve Random Oversampling model has an accuracy of 0.65 and a F-1 score of 0.74 for low risk.
  - SMOTE model has an accuracy score of 0.66 and the F-1 score is 0.82 for low risk.
  - UnderSampling has the lowest accuracy score at 0.54 and F-1 score of 0.70.


the best model for predicting high risk loans is the Easy Ensemble Classifying model.

