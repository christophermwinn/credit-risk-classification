# credit-risk-classification
Supervised Learning Challenge

## Overview of the Analysis

The purpose of this analysis was to create a model based on loan risk.

* Dataset of historicl lending activity from a peer to peer lending services company
* Goal to create a model that identifies the creditworthiness of borrowers
* Loan status was used as the dependent variable (y value)
* Data was split into training and testing sets
* A logistic regression model was created with the original data
* The training data was then resampled to predict a new logistic regression model

## Results

Results of the analysis are below:

* Machine Learning Model 1:
  * The balanced accuracy score is: 0.9520479254722232
  * For healthy loans:
    * Precision- 1.00
    * Recall- 0.99
    * f1-score- 1.00
  * For high risk loans:
    * Precision- 0.85
    * Recall- 0.91
    * f1-score- 0.88
  * Accuracy- 0.99
  



* Machine Learning Model 2:
  * The balanced accuracy score is: 0.9936781215845847
  * For healthy loans:
    * Precision- 1.00
    * Recall- 0.99
    * f1-score- 1.00
  * For high risk loans:
    * Precision- 0.84
    * Recall- 0.99
    * f1-score- 0.91
  * Accuracy- 0.99

## Summary

Both models perform well for healthy loans, with identical results across the metrics of precision, recall, and f-1 score.  The second model, 
utilizing the oversampled data, performs better for high risk loans, particularly with regards to recall.  This measure is important for 
high risk loans, as lending institutions would want to minimize the instance of false negatives for this loan category.  For this reason, 
I would recommend using Machine Learning Model 2.
