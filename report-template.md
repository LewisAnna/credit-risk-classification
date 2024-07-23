# Module 12 Report Template

## Overview of the Analysis

In this Challenge, I evaluated a model based on loan risk. It is a dataset containing historical lending activity data from a peer-to-peer lending services company. What I am trying to create is a model that can identify the creditworthiness of borrowers. There were 7 columns in this dataset, all telling us different aspects- such as: 	loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks and total_debt. The stages of the machine learning process that I used for this analysis was as follows: Create the labels set and features, splitting the data into training and testing datasets by using train_test_split, creating a Logistic Regression Model with the Original Data and evaluating the data.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * The precision was  0.99 and the recall was 1.00  for '0'
    * The precision was  0.91 and the recall was 0.85  for '1'

## Summary

* I thimk that the Logistic Regression model had a great preformance, with an almost accurate '0' and a pretty good '1'. I do ave to say though, that the '1' is more important to predict than the '0', because we dont want to mix up anyone that is high risk for receiving a loan.

