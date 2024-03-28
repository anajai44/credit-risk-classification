# credit-risk-classification

## Overview of the Analysis

The data provided from `lending_data.csv` contained information of many different borrowers as the loan ammount, interest rate, income, debt to income ratio, accounts, derogatory marks, total debt, and the loan_status. All of that information is necessary because it was used to determine if the borrower was a healthy loan or a high-risk-borrower. 
* 1. I imported and read the data into a dataframe, so that I could better understand the data. 
* 2. I labeled the "loan status" as the y and the rest of columns as y.(loan status: 0=healthy, 1=high-risk)
* 3.  Data was split into the training and testing datasets
* 4. logistic regression model was created with the training data, and was saved as X_test. 
* 5. A dataframe was created  where it compare the results of the test data and the actual. Most results were alike. 
* 6. Finally, I created the classification report for the logistic regression model. 

## Results

According to the report from logistic regression model predicts really well the healthy loan because it has a 100% precision. Meanwhile, it isn't really accurate for the high-risk-loan since it's a 85% precision. In average for both it's about 92% presice, and a 99% accurate. 

## Summary
* Which one seems to perform best? How do you know it performs best? Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

The logistic regression peforms best on the healthy loan.
Therefore if the focus was just for healthy loans, this model would be a great fit. However, if it was required for a high-risk-loan, I would need to train more data. 
