# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).


Utilizing a dataset enriched with historical lending information, my aim is to engineer a model capable of accurately assessing borrower creditworthiness through machine learning techniques. The chosen methodology for this purpose is the Logistic Regression Algorithm, celebrated for its efficacy in predicting outcomes in classification challenges across various fields.




## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1:
* Model 1 Accuracy: 97% (avg)
      * Precision: 
          * Healthy: 100% 
          * High-risk: 84%
      * Recall scores:
          * Healthy: 99% 
          * High-risk: 94%
* Model 2 Accuracy: 99% (avg)
      * Precision: 
          * Healthy: 100% 
          * High-risk: 84%
      * Recall scores:
          * Healthy: 99% 
          * High-risk: 99%

## Summary
I recommend using model 2, as it outperformed model 1. Model 2 was more accurate and displayed better recall for high-risk loans. That said, both models did superbly well at identifying healthy loans, so if that is the intended goal, either model works well.
