# Module 12 Report Template

## Overview of the Analysis

In this project, I have used LogisticRegression model to train and test it for identifying the creditworthiness of the borrowers.

The historical data for this project comes from a lending services company which contains various variables such as 'loan_size', 'borrower_income', 'debt_to_income', 'total_debt' and more.

I have imported the data in a data frame then split the data into X (Features) and y (Target) variables.

Splitting of the data is done as the next step to train the model and then to test the accuracy of the model.

I have used  LogisticRegression model in this project for training and testing purposes.

After doing the first analysis with the provided data, I have used RandomOverSampler method to balance the data. Then I have used the same procedure to check if the accuracy of the model has increased.

The results of the analysis are as follows:

## Results

* Machine Learning Model 1:
  * Accuracy Score : 0.9924164259182832
  * recall: 0 -> 1.00 | 1 -> 0.89



* Machine Learning Model after RandonOverSampling:
  * Accuracy Score : 0.9942073279078859
  * recall: 0 -> 0.99 | 1 -> 0.99

## Summary

Looking at the confusion matrix and the classification report, it is very obvious that the model performed very well. The accuracy of 99% is very good. The number of false positives and false negatives are very small as compared to the number of true positives. So we can confidently use logistic regression for our current dataset. 

But after doing RandonOverSampling the model has improved the accuracy score from 99.24 to 99.42. It is still better to balance the train and test data to reduce the bias and improve accuracy.
