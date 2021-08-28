# Credit_Risk_Analysis

## Overview
Jill has recruited me to evaluate algorithms that can be used to predict credit risk using the credit card database available on LendingClub to determine whether they can be used for that purpose.

## Resources
- Data Sources: LoanStats_2019Q1.csv
- Software: Juypter Notebook 6.3.0, mlenv kernel (Python 3.9.4)

## Results
Through the analysis of the data given, I have been able to determine the following:

- For naïve random oversampling, the balanced accuracy score is 0.67, the precision score is 0.99, and the recall score is 0.58.

- For SMOTE oversampling, the balanced accuracy score is 0.65, the precision score is 0.99, and the recall score is 0.66.

- For undersampling, the balanced accuracy score is 0.65, the precision score is 0.99, and the recall score is 0.57.

- For SMOTEENN sampling, the balanced accuracy score is 0.55, the precision score is 0.99, and the recall score is 0.54.

- For the Balanced Random Forest Classifier, the balanced accuracy score is 0.79, the precision score is 0.99, and the recall score is 0.87.

- For the Easy Ensemble AdaBoost Classifier, the balanced accuracy score is 0.93, the precision score is 0.99, and the recall score is 0.94.

## Summary
Based on these results, and on the consideration that sensitivity is more important than recall in determining the creditworthiness of an account holder in receiving a loan, I hereby conclude that the best algorithm to use for that purpose would be the Easy Ensemble AdaBoost Classifier, for it has the highest recall score out of any algorithm tested, clocking in at 0.94.  While all algorithms tested had identical precision scores at 0.99 (to two decimal points,) the Easy Ensemble AdaBoost Classifier also boasted the highest balanced accuracy score, registering at 0.93.  Without a doubt, I would endorse the Easy Ensemble AdaBoost Classifier for this and related applications.
