# Credit-Card-Default-Prediction

Overview  
Credit card default prediction is critical for financial institutions as it helps manage risk, optimize lending decisions, and ensure financial stability. By accurately predicting whether a client will default on a credit card payment, banks and financial institutions can take proactive measures to mitigate potential losses, enhance customer relationship management, and improve overall financial performance.  
The primary business problem addressed by this project is the high risk and financial losses associated with credit card defaults. For financial institutions, managing credit risk is crucial to maintaining profitability and ensuring financial stability. Credit card defaults can lead to significant losses, impact liquidity, and damage the overall health of the financial institution.

Objectives  
- Risk Management: Identify high-risk clients who are likely to default on their credit card payments.  
- Cost Reduction: Minimize losses associated with credit defaults by implementing preemptive measures.  
- Customer Retention: Develop tailored strategies to help clients manage their credit more effectively, thus improving customer satisfaction and loyalty.  
- Regulatory Compliance: Ensure compliance with regulatory requirements by maintaining robust risk assessment and management processes.    

This project aims to predict whether a given client will default on a credit card payment when due. The prediction is made using three machine learning models: Logistic Regression, Support Vector Classifier (SVC), and XGBoost. The dataset used for this project is sourced from Kaggle and contains detailed information on credit card clients in Taiwan from April 2005 to September 2005.  

Dataset Information  
This dataset includes information on default payments, demographic factors, credit data, payment history, and bill statements. It consists of 25 variables as described below:

ID: ID of each client  
LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)  
SEX: Gender (1=male, 2=female)  
EDUCATION: Education level (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)  
MARRIAGE: Marital status (1=married, 2=single, 3=others)   
AGE: Age in years  
PAY_0: Repayment status in September 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, … 8=payment delay for eight months, 9=payment delay for nine months and above)  
PAY_2: Repayment status in August 2005 (scale same as above)  
PAY_3: Repayment status in July 2005 (scale same as above)  
PAY_4: Repayment status in June 2005 (scale same as above)  
PAY_5: Repayment status in May 2005 (scale same as above)  
PAY_6: Repayment status in April 2005 (scale same as above)  
BILL_AMT1: Amount of bill statement in September 2005 (NT dollar)  
BILL_AMT2: Amount of bill statement in August 2005 (NT dollar)  
BILL_AMT3: Amount of bill statement in July 2005 (NT dollar)  
BILL_AMT4: Amount of bill statement in June 2005 (NT dollar)  
BILL_AMT5: Amount of bill statement in May 2005 (NT dollar)  
BILL_AMT6: Amount of bill statement in April 2005 (NT dollar)  
PAY_AMT1: Amount of previous payment in September 2005 (NT dollar)  
PAY_AMT2: Amount of previous payment in August 2005 (NT dollar)  
PAY_AMT3: Amount of previous payment in July 2005 (NT dollar)  
PAY_AMT4: Amount of previous payment in June 2005 (NT dollar)  
PAY_AMT5: Amount of previous payment in May 2005 (NT dollar)  
PAY_AMT6: Amount of previous payment in April 2005 (NT dollar)  
default.payment.next.month: Default payment (1=yes, 0=no)  

Project Objectives  
Exploration: Examine how the probability of default payment varies across different demographic categories.  
Prediction: Identify the strongest predictors of default payment.  
Modeling: Utilize Logistic Regression, SVC, and XGBoost to build predictive models for default payment.  

Usage  
Prerequisites  
Ensure you have the following libraries installed:  

pandas   
numpy  
scikit-learn  
matplotlib  
xgboost  

Source: Kaggle - https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

Acknowledgements  
Any publications based on this dataset should acknowledge the following:  

Lichman, M. (2013). UCI Machine Learning Repository http://archive.ics.uci.edu/ml. Irvine, CA: University of California, School of Information and Computer Science.  

The original dataset can be found at the UCI Machine Learning Repository. 

NB: Please note that continous changes will be done on the project to improve the model. 
