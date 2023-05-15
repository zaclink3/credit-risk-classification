# credit-risk-classification

# Module 20 Report Template

## Overview of the Analysis

For the module we used machine learing, LogisticRegression, and resampling to calculate various datapoints and predictions for credit risk data. The purpose of this analysis was to evaluate a model based on loan risk by using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. This data included but was not limited to; interest rate, borrower income, and debt to income ratio. To sum this up, we had to take the data, and seperate the loan status column from the rest of the data. Then we assigned variables and split the data into training and testing pieces to conduct LogisticRegression. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores:
  - Accuracy - Accuracy Score was 96%. That is pretty high, but would like to refine the model to get a better score before this would be something pushed to production. 
  - Precision - Precision score for the healthy loans was very accurate coming in at 1. While the unhealthy loans was .83. Since this is for predicting the positive of whether this would be a high risk loan or not, I would like to improve the model before pushing into production. 
  - Recall - Recall means that it is identifying postitive instances in a dataset. for this model the recall score was .99 for both loans. this would give me and my team comfort that this model is correctly identifying the positives but still would need to evaluate other factors before pushing into production. 



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores:
  - Accuracy - Accuracy Score was 96%. That is pretty high, but would like to refine the model to get a better score before this would be something pushed to production. 
  - Precision - Precision score for the healthy loans was very accurate coming in at 1. While the unhealthy loans was .82. Since this is for predicting the positive of whether this would be a high risk loan or not, I would like to improve the model before pushing into production. 
  - Recall - This score was lower for high risk loans with .92. This should be evaluated before moving further. As high risk loans are risky

## Summary

Overall the models had fairly good accuracy scores. While accuracy can be a useful metric to assess the overall performance of a classification model, it has some limitations. For example, it can be misleading when the classes in the dataset are imbalanced, as a model that always predicts the majority class will achieve a high accuracy score even if it performs poorly on the minority class. Therefore, I would recommended to use additional evaluation metrics, such as precision, recall, F1 scores. Based on the evaluation of the models above. and considering the precision,  recall and accuracy scores. I would recommend the Machine Learning Model 1 (Testing_report)