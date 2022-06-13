# Credit Risk Analysis

## Overview of the loan prediction risk analysis:

This analysis applies machine learning to assess credit risk. Using a credit card dataset from LendingClub, I tested six different machine learning models to predict credit risk (classifying as low-risk or high-risk). The different models all attempted to address the challenge of unbalanced classification in the dataset, as low-risk loans far outnumbers the high-risk loans. 

## Results:

### Oversampling Models

* Naive Random Oversampling:
  * Balanced Accuracy Score: 65%
  * Classification Report
  * <img src="Resources/randomoversampling.png" width="75%" height="75%">   

* SMOTE
  * Balanced Accuracy Score: 63%
  * Classification Report
  * <img src="Resources/smote.png" width="75%" height="75%">  

### Undersampling Model
* Cluster Centroids 
  * Balanced Accuracy Score: 65%
  * Classification Report
  * <img src="Resources/cc.png" width="75%" height="75%"> 

### Combination Model
* SMOTEEN
  * Balanced Accuracy Score: 65%
  * Classification Report
  * <img src="Resources/smoteen.png" width="75%" height="75%"> 
  
### Ensemble Models 
* Balanced Random Forest Classifier 
  * Balanced Accuracy Score: 68%
  * Classification Report
  * <img src="Resources/rfc.png" width="75%" height="75%"> 
 
* Easy Ensemble AdaBoost Classifier 
  * Balanced Accuracy Score: 92%
  * Classification Report
  * <img src="Resources/adaboost.png" width="75%" height="75%">  

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

## Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
