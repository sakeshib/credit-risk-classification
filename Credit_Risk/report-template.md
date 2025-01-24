# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to evaluate the performance of machine learning models in predicting loan health, specifically distinguishing between healthy loans(0) and high-risk loans(1). The data consisted of financial information about loan characteristics and historical outcomes, and the goal was to predict the likelihood of a loan being high-risk and identify the creditworthiness of borrowers.

### Description
* Target Variable: Loan status (0=Healthy, 1=High-Risk)
* Distribution of Target Variable:
    * Healthy Loans(0): 18,765
    * High-Risk Loans(1): 619
* Stages of Machine Learning Process:
    * Loading data and separate into labels and features
    * Train the model - split between testing and training
    * Predict and evaluate the model
* Logistic Regression: used this model to predict the healthy vs high-risk loans

## Results

* Machine Learning Model 1:
    * Accuracy: 99%
    * Precision:
        * Class 0 (Healthy): 100%
        * Class 1 (High-Risk): 84%
    * Recall:
        * Class 0 (Healthy): 99%
        * Class 1 (High-Risk): 94%
    * F-1 Score:
        * Class 0 (Healthy): 100%
        * Class 1 (High-Risk): 89%

The logistic regression model performed exceptionally well for healthy loans, with almost 100% across three fields - precision, recall, and F-1 score. As for high-risk loans, the model maintained a 94% recall with a lower precision of 84%. 

## Summary

I would recommend the logistic regression model to predict healthy and high-risk loans due to its high recall. While healthy loans have predicted a near-perfect score on its precision, recall, and F-1 score using the model, the high-risk loans were also receiving a decent almost of recall (94%). From a business standpoint, it would be more beneficial to predict and highlight Class 1, as we'd like to minimize misclassifying high-risk loans as healthy.