# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to train and evaluate a model based on loan risk. Using historical lending activity from a peer-to-peer lending service company a model will be built to identify the credit worthiness of borrowers.

The stages of the machine learning process in this analysis included:

1. Splitting the data into training and testing datasets
2. Creating and fitting a logistic regression model with the original data
3. Evaluating the model's performance using accuracy, precision, and recall scores


## Results

Description of Logistic Regression Model Accuracy, Precision, and Recall scores.
- Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances.
- Precision
    - Healthy Loan (class 0): 1.00
    - High-Risk Loan (class 1): 0.87
- Recall
    - Healthy Loan (class 0): 1.00
    - High-Risk Loan (class 1): 0.89

## Summary

The logistic regression model is doing a very good job predicting the healthy loans (class 0), with precision 1.00, recall 1.00. When it comes to risky loans (class 1), the model is still doing a good prediction, precision 0.87 and recall 0.89.

The lower percision and recall in predicting the risky loans (class 1) can be because of our imbalanced dataset as the support test data for class 1 is only 625 which is very low compared to 18759 for class 0. There is some room for improvement in predicting high risk loans. In other words, there are also very few high-risk loans for the model to learn from when compared to the number of healthy loans in the data set. If more of these types of loans could be added to the data to train from, there may be improvement to the model.

