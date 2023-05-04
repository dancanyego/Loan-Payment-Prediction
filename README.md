# Loan-Payment-Prediction
exploring publicly available data from LendingClub.com. You would want to invest in people who showed a profile of having a high probability of paying you back. We will try to create a model that will help predict this.

The Clasification report of the model are as follows Using the decision tree:

    precision    recall  f1-score   support

           0       0.85      0.85      0.85      2650
           1       0.22      0.23      0.22       511

    accuracy                           0.75      3161
   macro avg       0.54      0.54      0.54      3161
weighted avg       0.75      0.75      0.75      3161


The confusion Matrix are:

[[2240  410]
 [ 395  116]]
 
 Comparing the Clasification report using Random Forest model We Have :
 
 
   precision    recall  f1-score   support

          0       0.85      1.00      0.92      2431
          1       0.57      0.03      0.05       443

avg / total       0.81      0.85      0.78      2874

And The confusion Matrix:

[[2422    9]
 [ 431   12]]
