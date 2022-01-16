# Credit_Risk_Analysis

## Overview

The purpose of this analysis is to compare machine learning models and their ability to detect risky loans. The data is from **LendingClub**, and in its raw form is very unbalanced. There are far more good loans than risky loans, which is representative of the current market. Oversampling, undersampling, and a combination approach (oversampling & undersampling) are used to train models with less bias. With good data being provided the machine learning models are used to prediect credit risk.

For further detail the code can be viewed [here](/challenge/credit_risk_resampling.ipynb) and [here.](/challenge/credit_risk_ensemble.ipynb)

## Results

The following is a bulleted list of results comparing sampling methods and models. The metrics of highest improtance for this analysis are balanced accuracy score, high risk loan precision, and high risk loan recall. Balanced accuracy score represents the fraction of correct predeictions, expressed as a fraction 0 to 1 or as a percent. Precision represents the fraction of actual positive instances in the total numper of positive predictions. Precision is expressed as a fraction 0 to 1 or as percent. The final metric of particualar interest in this analysis is recall; which represents the fraction of positive predictions in the total number of actual positive instances. Recall is also expressed as a fraction from 0 to 1 or as a percent.  

[More_information_about_performance_metrics](https://towardsdatascience.com/a-practical-guide-to-seven-essential-performance-metrics-for-classification-using-scikit-learn-2de0e0a8a040)

* Naive Random Oversampling

![naive_random](/resources/naive_random.png)

![score_naive](/resources/score_naive.png)

* SMOTE Oversampling

![smote](/resources/smote.png)

![score_smote](/resources/score_smote.png)

* Cluster Centroids Undersampling

![undersampling](/resources/undersampling.png)

![score_undersampling](/resources/score_under.png)

* Combination (Over and Under) Sampling

![combination](/resources/combination.png)

![score_combo](/resources/score_combo.png)

* Balanced Random Forest Classifier

![balancedforest](/resources/balancedforest.png)

![score_forest](/resources/score_forest.png)

* Easy Ensemble AdaBoost Classifier

![easyensemble](/resources/easyensemble.png)

![score_ensemble](/resources/score_ensemble.png)


Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
