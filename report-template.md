Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of the analysis is to use various techniques to train and value a model based on loan risk

* Explain what financial information the data was on, and what you needed to predict.

A financial lending dataset information was provided. and we were asked to analyze the ability of the borrower to repay the loan or meet the financial obligation on time.

* Provide basic information about the variables you were trying to predict (e.g., `value counts`).

we were using the variables loan status as a target variable to do the prediction 

* Describe the stages of the machine learning process you went through as part of this analysis.
to provide this analysis we went through different stage
first, we have the data that was provided for us to be used to train and test the machine learning model, then we prepare the data for analysis, selecting features to be use in the machine learning model, like scaling, normalizing features, converting categorical features into numerical features, then we explore the data to gain a better understanding of the relationship and patterns in the data.

* Briefly touch on any methods you used (e.g., `Logistic Regression`, or any resampling method).
in this challenge we created the logistic regression with the original data and a logistic regression with the resampled training data to train our data and then fit the model

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.



* Machine Learning Model 1:

*Description of Model 1 Accuracy, Precision, and Recall scores.
logistic regression model indicate that the total number predicted are positive. for instance, for 0, the prediction was 1.00 (healthy loans) and for 1, the precisions 0.86. the ratio of true positives to the total number of actual positives. for class 0 the precision number is 1.00 and for class 1 the precision number is 91% are correctly identified by the model.

for F1 score who represent the harmonic mean and precision and recall, and is a combined measure of precision and recall. for class 0, the F1 score is 1.00 which indicates high performance. for class 1, the F1 score is 0.88, which indicates the model is not performing as well on this class compared to class 0

 
















* Machine Learning Model 2:

* Description of Model 2 Accuracy, Precision, and Recall scores.
The logistic regression model with the oversampled data has a precision score 1.00 for class 0, 99% for recall. 85% for Class 1 99% for recall. so, we notice that 15% of class 1 where inaccurately assign. because both classes are 99% accurate, we can say both classes were assigned correctly. F1 score has 1.00 for class 0 and 92% for class 1, we constate that the regression model with oversampled data perform better.

 













## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s?)

As you can see in this presentation below, these two models are providing the same output 


 
Since, these two models are giving the same output we, do not need to give any recommendation. 
