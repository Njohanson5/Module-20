# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    #The purpose of the analysis is to show the value of high risk or healthy loans. 

* Explain what financial information the data was on, and what you needed to predict.
    # We are predicting the value of the loan, and examining the various columns of the CSV. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

Precision is a measure of how many of the positive predictions made are correct (true positives) so looking at the values we can see '0' 100% and '1' 85%
F1-Score is a measure combining both precision and recall. A combined score of the recall and F1 resulting 90

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Rcall scores.

         precision    recall  f1-score   support

           0       1.00      0.99      1.00     18786
           1       0.85      0.90      0.87       598

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.93     19384
weighted avg       0.99      0.99      0.99     19384

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
