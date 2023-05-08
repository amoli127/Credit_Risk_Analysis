# Credit_Risk_Analysis

The purpose of this analysis is to build and evaluate machine learning models to assess credit risk. The analysis uses historical lending data from LendingClub to train and test several models, including logistic regression, decision tree, random forest, and ensemble classifiers.

## Results

### Random Oversampling

<p align="center">
  <img src="https://user-images.githubusercontent.com/117063056/236720174-2c1c5dc3-0248-4b50-b851-db8f640e6e48.png">
</p>


- Balanced Accuracy Score: 66%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 66%
    - Low Risk: 66%

### SMOTE Oversampling

<p align="center">
  <img src="https://user-images.githubusercontent.com/117063056/236720176-ec293588-cd9e-417e-bbca-c9109146bc12.png">
</p>


- Balanced Accuracy Score: 66%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 66%
    - Low Risk: 66%

### ClusterCentroids

<p align="center">
  <img src="https://user-images.githubusercontent.com/117063056/236720172-ec1a4be4-6bc8-44a0-bc6e-25df52c1c66e.png">
</p>


- Balanced Accuracy Score: 55%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 69%
    - Low Risk: 40%

### SMOTEENN


<p align="center">
  <img src="https://user-images.githubusercontent.com/117063056/236720177-0ef546d8-3f89-4473-9aad-a60576c54231.png">
</p>

- Balanced Accuracy Score: 64%
- Precision:
    - High Risk: 1%
    - Low Risk: 100%
- Recall:
    - High Risk: 70%
    - Low Risk: 58%

### BalancedRandomForest Classifier

<p align="center">
  <img src="https://user-images.githubusercontent.com/117063056/236720178-38f6d414-f5a0-4801-bc7c-4dcecd528cac.png">
</p>

- Balanced Accuracy Score: 78%
- Precision:
    - High Risk: 3%
    - Low Risk: 100%
- Recall:
    - High Risk: 70%  
    - Low Risk: 87%

### EasyEnsemble Classifier

<p align="center">
  <img src="https://user-images.githubusercontent.com/117063056/236720173-b1d7a025-d363-478f-a92d-4b657cba78ea.png">
</p>

- Balanced Accuracy Score: 93%
- Precision:
   - High Risk: 9%
   - Low Risk: 100%
- Recall:
    - High Risk: 92%
    - Low Risk: 94%
