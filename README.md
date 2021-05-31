# Credit Risk Analysis

## Overview of Analysis
An analysis was conducted to find the best way to determine credit risk for individuals when the majority of accounts are considered "low risk." 

## Results

- Random Oversampling: Accuracy score = 65.2%, Precision = .009, Recall = 0.63
- SMOTE Oversampling: Accuracy score = 66.5%, Precision = .01, Recall = 0.66
- ClusterCentroids Undersampling: Accuracy score = 49%, Precision = 0.008, Recall = 0.59
- SMOTEENN: Accuracy score = 56.8%, Precision = 0.01, Recall = 0.76
- Balanced Random Forest Classifier: Accuracy score = 66.6%, Precision = 0.71, Recall = 0.33
- AdaBoost Classifier: Accuracy score = 75%, Precision = 0.02, Recall = 0.64

## Summary
By taking into account the accuracy, precision and recall scores, the most accurate model to use would be the Balanced Random Forest Classifier. While the accuracy is not the highest, it has the highest precision score, meaning it is more likely to make correct positive predictions. 


