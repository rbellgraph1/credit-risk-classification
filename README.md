* The  purpose of the analysis is to evaluate if we can predict the high risk loans from the healthy loans. 

* Using the information from historical loan parameters such as loan_size, interest_rate, borrower_income,	debt_to_income,	num_of_accounts,	derogatory_marks,	total_debt, and loan status we are doing an analysis to determine if maching learning can predict the accurate outcomes. 

* Within this analysis we are using the Loan Status as the y_value parameter the remainder parameters from above as the X_value to split the data to train and test sets. 

* Two different Logistic Regression models were created using the original data and the oversampled method using the x and y parameters. 
* In the orignal model the (Model 1) we can predict healty loans very well with recal at 1, f1-score at .99 however not as accurate with the high risk loans only having a recall of .85 and F1-score at .91. 

* In the second model using RandomeOverSampler (Model 2) we get a much better prediction of the riskier loans. We can see the results from Recal from .85 to .84 but we can see an much better recall from .91 to .99 and F1-score from .88 to .91.  Both models are showing a .99 accuracy. 

* To summarize the outcome of the analysis, we do believe the model can predict both healthy and riskier loans at a high level.  
* Depending on the risk levels we are willing to accept may need to add additional value parameters. 
* I personally would like to see a higher precisiion of greater than 90 before we considering the model sufficient to predict riskier loans. 
* Risk loans depending on the size, have a huge cost and time involved for the bank and require a much higher degree of precision. 

![Alt Text](https://github.com/rbellgraph1/credit-risk-classification/blob/main/2023-07-17_21-11-17.png)
