# HW_20_credit-risk-classification

## Overview of the Analysis
A) Purpose: Based on the existing financial information of the borrower, the aim is to predict the risk of lending money to new borrowers in order to make informed decisions about loan approval.

B) The financial information of the borrowers includes their loan size, interest rate, income, debt-to-income ratio, number of accounts, credit status (derogatory marks), total amount of debt, and their loan status.

C) This dataset comprises financial information for 75,536 borrowers. Based on loan status, where 0 indicates a healthy status and 1 indicates a risky status, there are 75,036 borrowers with a healthy loan status, while 2,500 borrowers have been labeled as high-risk.

D) The features (X) including loan size, interest rate, income, debt-to-income ratio, number of accounts, credit status (derogatory marks), and total amount of debt are utilized to predict the loan status, which serves as the prediction target (y).

E) The data was divided into training and testing groups using the train_test_split function. A logistic regression model was then applied to train the training dataset. Subsequently, the test dataset was used for predictions to validate the accuracy of the model. The confusion matrix was employed on the test dataset to determine the number of true positives, true negatives, false positives, and false negatives. Additionally, a classification report was generated to obtain precision and recall percentages for the predicted test dataset.

## Results:
Precision: 94% (an average--in predicting healty loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
Accuracy: 99%
Recall: 95% (an average--the model had 100% recall in predicting healthy loans, but 89% recall in predicting high-risk loans)