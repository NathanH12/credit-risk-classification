# Module 20 Report 

## Overview of the Analysis

The objective of this analysis is to develop a machine learning model for assessing the creditworthiness of borrowers. Using historical lending activity data from a peer-to-peer lending services company, the aim is to build a model that effectively predicts the likelihood of loan default.
The dataset includes crucial financial information on loans, with the primary focus on predicting the loan status (0 for healthy and 1 for high-risk).
The key variable to predict is the loan status, categorizing loans into healthy or high-risk categories.
The analysis encompasses data preprocessing, the division of data into training and testing sets, constructing a logistic regression model, evaluating model performance, and potentially implementing resampling techniques to address class imbalance.
Logistic regression serves as the initial model, and potential resampling techniques like RandomOverSampler are considered to handle class imbalance.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1
Balanced Accuracy: 95%
Precision for Class 0: 1.00
Recall for Class 0: .99
Precision for Class 1: .85
Recall for Class 1: .91

* Machine Learning Model 2
Balanced Accuracy: 99.5%
Precision for Class 0: .99
Recall for Class 0: .99
Precision for Class 1: .99
Recall for Class 1: .99

## Summary

Both models exhibit remarkable accuracy and efficiency, with Model 2 showcasing an equal proficiency in predicting both healthy and high-risk loans. The decision on which model to recommend depends on the specific business objective and priorities.

Considering the balanced nature of the dataset and the high performance of both models, either Model 1 or Model 2 could be recommended based on the specific goals of the company. Further evaluation, possibly considering the impact on decision-making processes, may guide the final model selection.

I would recommend Model 2 in most circumstances, but Model 1 could also be useful. 
