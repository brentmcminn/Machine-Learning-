### 
Machine Learning Homework 

In the first Ensemble section of the homework I cleaned data using dummy variables to convert text string in the dataframe so I could run machine learning models that would help predict Loan Risk given a set of features. We categorized the loans using a lambda function to place them in high and low risk bins coded in 0 = low risk and 1 = high risk. 

>>>>>y = y.apply(lambda x: 0 if x =='low_risk' else 1)

The Ensemble Learning AdaBoost had an accuracy score of 93% vs 76% for the Balanced Random Forest. 
The top features were total rec prncp, total payment inv, total rec int. 

Resampling with Logistic Regression 



