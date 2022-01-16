# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to compare machine learning models and their ability to detect risky loans. The data is from **LendingClub**, and in its raw form is very unbalanced. There are far more good loans than risky loans, which is representative of the current market. Oversampling, undersampling, and a combination approach (oversampling & undersampling) are used to train models with less bias. With good data being provided the machine learning models are used to prediect credit risk.

For further detail the code can be viewed [here](/challenge/credit_risk_resampling.ipynb) and [here.](/challenge/credit_risk_ensemble.ipynb)

## Results

* Naive Random Oversampling

![naive_random](/resources/naive_random.png)

* SMOTE Oversampling

![smote](/resources/smote.png)

* Cluster Centroids Undersampling

![undersampling](/resources/undersampling.png)

* Combination (Over and Under) Sampling

![combination](/resources/combination.png)

* Balanced Random Forest Classifier

![balancedforest](/resources/balancedforest.png)

* Easy Ensemble AdaBoost Classifier

![easyensemble](/resources/easyensemble.png)


Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
