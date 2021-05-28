# Credit_Risk_Analysis

Loans serve as an essential part of the worlds economy. For financial institutions and borrowers most loans are mutually beneficial, however there are instances where the borrower may end up defaulting on a loan resulting in a negative outcome for both parties. To avoid defaults on loans, financial institutions and banks must accurately assess the credit risk of potential borrowers. Financial Institutions have traditionally relied on factors such as income, credit scores collateral assets to asses lending risk, but the rise of financial technology (Fin Tech) has enabled financial institutions to use machine learning to to analyze risk.

The use of Machine learning to predict credit risk allows financial insitutions to provide a quicker and more reliable loan experience. Machine learning also allows for financial instititions to more accurately predict good loan candidates, which will lower the default rates of loans. For this project, I will be using Python and the Sci-Kit learn library to build and evaluate machine learning models to predict credit risk.

## Overview of Analysis

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
### Scores By Model

#### Oversampling

1. Naive Random Oversampling
    - Balanced Accuracy Score: .645
    - Precision Score: High = .01
    - Recall Score: High - .61
![](Resources/Naive_over.png)

2. Smote Oversampling
    - Balanced Accuracy Score: .62
    - Precision Score: High = .01
    - Recall Score: High = .61
![](Resources/smote_over.png)

#### Undersampling

3. ClusterCentroids
    - Balanced Accuracy Score: .509
    - Precision Score: High = .01
    - Recall Score: High = .57
![](Resources/ClusterCentroids.png)

#### Over-and-Under Sampling
4. SMOOTEENN
    - Balanced Accuracy Score: .616
    - Precision Score: High = .01
    - Recall Score: High = .69, Low = .54
![](Resources/over_under.png)

#### Ensemble Classifiers
5. BalancedRandomForestClassifier
    - Balanced Accuracy Score: .787
    - Precision Score: High = .04
    - Recall Score: High = .67, Low = .91
![](Resources/BalancedRandomForest.png)

6. EasyEnsembleClassifier
    - Balanced Accuracy Score: .925
    - Precision Score: High = .07
    - Recall Score: High = .91, Low = .94
![](Resources/EasyEnsemble.png)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
