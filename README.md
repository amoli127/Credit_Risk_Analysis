# Credit_Risk_Analysis

The purpose of this analysis is to build and evaluate machine learning models to assess credit risk. The analysis uses historical lending data from LendingClub to train and test several models, including logistic regression, decision tree, random forest, and ensemble classifiers.

## Results

### Random Oversampling

- Balanced Accuracy Score: 66%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 66%
    - Low Risk: 66%

### SMOTE Oversampling

- Balanced Accuracy Score: 66%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 66%
    - Low Risk: 66%

### ClusterCentroids

- Balanced Accuracy Score: 55%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 69%
    - Low Risk: 40%

### SMOTEENN

- Balanced Accuracy Score: 64%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 70%
    - Low Risk: 58%

### BalancedRandomForest Classifier

- Balanced Accuracy Score: 78%
- Precision:
    - High Risk: 3%
    - Low Risk: 100%
- Recall:
    - High Risk: 70%  
    - Low Risk: 87%

### EasyEnsemble Classifier

- Balanced Accuracy Score: 93%
- Precision:
   - High Risk: 9%
   - Low Risk: 100%
- Recall:
    - High Risk: 92%
    - Low Risk: 94%
