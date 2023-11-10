# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
        The purpose of this analysis is to automate the loan approval process by creating a machine learning model to predict loan status based on other factors. 
* Explain what financial information the data was on, and what you needed to predict.
        The financial information in the dataset includes loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, and total_debt. These features are used to predict the loan_status, which is set to either 0 or 1 indicating whether a loan was approved or not.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
        as it was described in the previous question, the loan_status column is set to either 0 or 1 where 0 means the loan was accepted and 1 means the loan was denied.
* Describe the stages of the machine learning process you went through as part of this analysis.
        preparing the data by reading in the csv, splitting the data into X and y variables, splitting the data into training and testing datasets, fitting a logistical regression model, making predictions using the testing data, and finally evaluating the model's performance.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
         The primary machine learning method used was logistic regression which is used for making the machine learning model.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
        Accuracy: 1.00
        precision: 0.99
        recall: 1.00



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
        Accuracy: .85
        precision: .91
        recall: .88

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
machine learning model 1 is the better machine learning model to use. The accuracy score is 15 points higher meaning it is correct 15% of the time more than the other model. Machine learning model 1 also has higher precision and recall scores meaning there are almost no false-positives, and it correctly recognizes all true-positive results. 