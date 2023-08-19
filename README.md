# HW_20_credit-risk-classification

## Overview of the Analysis
A) Purpose: Base on this exiting financial information of the borrower to predict the risk for lending money to the new borrowers for making decision of loan approval. 

B) The financial information of the borrowers include their loan size, interest_rate, income, debt/income ratiom, number of accounts, credit status (derogatory marks), total amount of debt and their loan status. 

C) This dataset has 7,7536 borrower's financial information , based on the loan status, 0 is healthy and 1 is risky, the number of borrows who have healthy loan status is 7,5036 and there are 2500 borrowers whose loan status are labeled as high-risk. 

D) The features (X) of loan size, interest_rate, income, debt/income ratiom, number of accounts, credit status (derogatory marks), total amount of debt are used to predict loan_status as predicion target (y). 

E) Data was splited into training and testing groups using train_test_split function, using logistic regression model to train training dataset. Then the test dataset was used for predicition to validate the accuracy of this model. The confusion matrix was used to for test dataset to see the number of true positives, true negatives, false positives and false negatives. The classification report was applied to get the precision and recall percentage in predicted test dataset. 

## Results:
Precision: 94% (an average--in predicting healty loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
Accuracy: 99%
Recall: 95% (an average--the model had 100% recall in predicting healthy loans, but 89% recall in predicting high-risk loans)