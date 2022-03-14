# Credit_Risk_Analysis

## Overview
The purpose of this analysis to build and test different machine learning models to evaluate credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, using different techniques to train and evaluate models with unbalanced classes is needed. In this analysis, imbalanced-learn and scikit-learn libraries are used to build and evaluate models using resampling.
## Results:
### Random Oversampling Model
  <img align= "center" width="415" alt="Random Oversampling" src="https://user-images.githubusercontent.com/33046642/158053037-b29776a8-c56c-406e-b87a-d08b48c5bb5a.png">
  
  - Balanced Accuracy Scores: 0.6456
  - Precision Scores: 0.99
  - Recall Scores: 0.68

### SMOTE Oversampling Model
<img align= "center" width="415" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/33046642/158053154-9e7d35dd-8616-4f90-9ed0-f38972d2f356.png">

  - Balanced Accuracy Scores: 0.6234
  - Precision Scores: 0.99
  - Recall Scores: 0.64
  
### Cluster Centroids Undersampling Model
<img align="center" width="409" alt="Undersampling" src="https://user-images.githubusercontent.com/33046642/158053206-97a99303-4907-4f93-a7bd-43b61a32164d.png">

  - Balanced Accuracy Scores: 0.5122
  - Precision Scores: 0.99
  - Recall Scores: 0.45
  
### SMOTEENN Combination (Over-Under) Sampling Model
<img align="center" width="409" alt="Combination Sampling" src="https://user-images.githubusercontent.com/33046642/158053249-e0291cb3-a722-4e09-bf1a-ce58a5217cef.png">

  - Balanced Accuracy Scores: 0.64
  - Precision Scores: 0.99
  - Recall Scores: 0.58
  
### Balanced Random Forest Classifier
<img align="center" width="413" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/33046642/158053270-873fc010-70c4-4432-bcf5-8ca976d2dc2c.png">

  - Balanced Accuracy Scores: 0.7877
  - Precision Scores: 0.99
  - Recall Scores: 0.91
  
### Easy Ensemble AdaBooster Classifier 
<img align="center" width="413" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/33046642/158053294-7d120562-eb57-4574-a5ab-46764161ceec.png">

  - Balanced Accuracy Scores: 0.9254
  - Precision Scores: 0.99
  - Recall Scores: 0.94

## Summary 
From the results shown above, it seems that the Easy Ensemble AdaBooster Classifier is the best model for predicting credit risk since it has the highest accuracy, precision, and recall scores compared to other models. 
