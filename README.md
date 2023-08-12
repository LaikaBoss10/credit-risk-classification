# Module 12 Report Template

## Overview of the Analysis

In credit_risk_classification.ipynb the quality of loans (High risk (1) or healthy (0)) was used to train and test a logistic regression algorthim. The logistic regression algorthim was able to determine the quality of loans with a accuracy of 94.% based on 7 input variables(loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks and total_debt). The model was then recreated after applying a random over sampling technique to address the bias of the model due to the data having a majority population of healthy loans. This increased the accuracy of the model to 99.5%.



## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * balanced accuracy score =         0.944
  * Healthy Loan precision score =    1.00 
  * Healthy Loan recall score =       1.00
  * High Risk Loan precision score =  0.87
  * High Risk Loan recall score =     0.89



* Machine Learning Model 2 (Random Over Sampling):
  * balanced accuracy score =         0.995
  * Healthy Loan precision score =    1.00 
  * Healthy Loan recall score =       0.99
  * High Risk Loan precision score =  0.99
  * High Risk Loan recall score =     1.00 
## Summary

Machine Learning Model 2 performed better at analyzing our dataset. However this is often the case when applying random over sampling on an unbalance data set. The question is which model would perform better when predicting the loan quality of new loans. Therefore new loan data should be collected and the viability of the machine learning models should be tested against them before a determination can be made on which machine learning model is superior at judging new loan data.