# Credit Risk Analysis Report

The purpose for this analysis is to predict the risk of default by individuals looking to take out a loan. It takes into consideration the loan's size and interest rate, the borrower's income, debt-to-income ratio, and total existing debt. Using this data, we wanted to predict whether or not the individual had already been flagged as safe or not.
To start, we separated our loan_status variable from the larger dataframe and then randomly split the data into training and testing sets. Next we ran our data through a logistic regression model and calculated the accuracy results. Following that, we oversampled data to see if we could find a model that could predict even more accurately from a mock, larger dataset.

* Logistic Regression Model:
  * Accuracy - 0.99
    
  * Healthy Loan Precision - 1.00
  * Healthy Loan Recall - 0.99
  
  * High-Risk Loan Precision - 0.85
  * High-Risk Loan Recall - 0.91


* RandomOverSampler:
  * Accuracy - 0.99
    
  * Healthy Loan Precision - 0.99
  * Healthy Loan Recall - 0.99
  
  * High-Risk Loan Precision - 0.99
  * High-Risk Loan Recall - 0.99
    

 I personally think the Logistic Regression done with the original data is the better model to use. The second model is likely to be an overfitted one. 
