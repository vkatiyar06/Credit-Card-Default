# Credit-Card-Default
# Problem
In recent years, the credit card issuers in Taiwan faced the cash and credit card debt crisis and the delinquency is expected to peak in the third quarter of 2006 (Chou,2006). In order to increase market share, card-issuing banks in Taiwan over-issued cash and credit cards to unqualified applicants. At the same time, most cardholders, irrespective of their repayment ability, overused credit card for consumption and accumulated heavy credit and cash–card debts. The crisis caused the blow to consumer finance confidence and it is a big challenge for both banks and cardholders

# About Dataset
There are 25 variables: \
ID: ID of each client\
LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit\
SEX: Gender (1=male, 2=female)\
EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)\
MARRIAGE: Marital status (1=married, 2=single, 3=others)\
AGE: Age in years\
PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months,8=payment delay for eight months, 9=payment delay for nine months and above)\
PAY_2: Repayment status in August, 2005 (scale same as above)\
PAY_3: Repayment status in July, 2005 (scale same as above)\
PAY_4: Repayment status in June, 2005 (scale same as above)\
PAY_5: Repayment status in May, 2005 (scale same as above)\
PAY_6: Repayment status in April, 2005 (scale same as above\)
BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)\
BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)\
BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)\
BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)\
BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)\
PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)\
PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)\
PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)\
PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)\
PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)\
PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)\
default.payment.next.month: Default payment (1=yes, 0=no)\

# Approach
To apply different ML algorithms and to find which works best on this dataset.\
Data dosen't contain any NAN values. Irrelevant columns were removed from the data.\
Data is viualized using Seaborn.\
One hot encoding is done for categorical variables like 'marriage','education',etc.\
Feature Sacling is done for numerical varialbes in order to make all variable in range suitable for algorithms.\
Logistic Regression gives 82.5% accuracy with 0.432 F1 score.\
Stochastic Gradient Descent gives 81.33% accuracy with 0.377 F1 score.\
KNN gives 81.67% accuracy with 0.354 F1 score.\
SVM gives 80.67% accuracy with 0.301 F1 score.\
Decision Tree Classifier gives 73.1% accuracy with 0.3571 F1 score.\
Random Forest gives 81.33% accuracy with 0.391 F1 score.\
KNN gives 81.8% accuracy with 0.404 F1 score.\
