# Module 20 Report

## Overview of the Analysis

In this module the expectation was to create a supervised learning model to determine the creditworthiness of loan applicants. Using the subsets of the original data allowed for thorough learning of Logistical Regression Model. Separating the initial data into a (y) label of “0” a good loan applicant and “1” a risky loan applicant. By dropping the “loan status” column we were able to create a (x) label with the following features: loan size, interest rate, borrower income, debt to income, num of accounts, derogatory marks, and total debt. Once the data was structured correctly the regression model could be trained. The model was trained on x_trained and y_trained. The model was tested for the accuracy of its predictions by providing the x_test subset, whereby the model would predict test outcomes (y).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

•	This model does a good job in predicting both the healthy and the high-risk loans as can be inferred from the high accuracy score of 99% and balanced accuracy score of 97%. 

•	This model has a precision score of 100% for the healthy loans and 84% for the high-risk loans. The precision scores imply that the healthy loans were classified correctly as positive 100% of the times. However, for the high-risk loans, the classification was correct only 84% of the times.

•	This model has a recall score of 99% for the healthy loans and 94% for the high-risk loans. The scores imply that for all the instances where the loans were actually healthy, 99% of the times they were classified correctly. However, for all the instances where the loans were actually high-risk, they were classified correctly 94% of the times.


## Summary

Upon analysis, it was observed that both models exhibited commendable accuracy, precision, and recall scores. However, the logistic regression model that utilized resampling showcased a slightly superior performance

Considering the objective of accurately identifying both healthy loans and high-risk loans, the logistic regression model with resampling emerges as the optimal choice.
