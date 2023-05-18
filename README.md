# Credit Card Customer Churn Prediction
## Executive summary
1. Problem
Assume that we are a group of data analytics consultants hired by HSAC bank. Currently the credit 
card department of HSAC bank is facing a very high customer churn rate, which means that an 
increasing number of credit card holders have decided to close their credit card accounts. The 
department head is very confused with the current situation and concerned with the potential impact on 
the bank's performance. The department head would like to know the method to predictcustomer churn
and understand the rationale behind so that the department can improve the quality of products and 
services provided to change the situation.
In this report, we have adopted machine learning techniques to (1) find the optimal model for the bank
to predict credit card customer churn and (2) uncover the most important variables leading to the 
customer churn. We also proposed recommendations based on our research and findings.

2. Principal findings
We fit the dataset to several machine learning models subsequent to the EDA and data-preprocessing. 
Our machine learning includes (1) KNN, (2) SVM, (3) Logistic Regression, (4) Random Forest, (5) 
Basic GBM, (6) Stochastic GBM, (7) XGBoost and (8) K-means. We generated the test AUC for each 
model. In conclusion, the optimal model is Stochastic GBM with the highest test AUC of 0.9578. Based 
on the Stochastic GBM model, we find the top 2 most important variables, Total Transaction Count
and Total Transaction Amount, for HSAC to investigate further and pay more attention to.

3. Recommendations
Last but not least, we proposed recommendations for HSAC to both predict and prevent customer churn. 
In terms of prediction, we suggest HSAC to proactively and closely monitor customer activities and 
pay special attention to the 2 most important variables on a timely basis.
As for preventing attrition, we recommend HSAC to focus on Customer Relationship Management. 
For example, HSAC should conduct customer surveys regarding the service quality regularly. To attract 
and retain customers, HSAC can design and launch promotion programs to different clusters of 
customers. More importantly, HSAC should consider providing customized service to different clusters 
of customers according to the clusters grouped by K-means/clusters grouped by transaction amount.
