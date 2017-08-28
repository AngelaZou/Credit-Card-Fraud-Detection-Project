# Credit-Card-Fraud-Detection-Project
## What is credit card fraud
Credit card fraud is a wide-ranging term for theft and fraud committed using or involving a payment card,<br>
such as a credit card or debit card, as a fraudulent source of funds in a transaction. It is of importance<br>
to detect such fraud via some novel methods. Here we will apply several `machine learning algorithms` to make prediction.<br>

## Dataset
The datasets(https://www.kaggle.com/dalpozz/creditcardfraud) contains transactions made by credit cards in September 2013 by european cardholders.This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. <br>

## Key Results
First I analyze the raw data via several data analysis technique. The data distribution may show the nature of data.<br>
For example, I analyze the frauds cases with the first principal component.<br>
<div align=center><img width="500" height="350" src="https://github.com/AngelaZou/Credit-Card-Fraud-Detection-Project/blob/master/figure/fig1.png"/></div><br>
<div align=center>The Fraud Case vs The First Principal Component</div><br>
Then I apply LogisticRegression algorithom. Best model to choose from cross validation is with C parameter =  0.01 <br>
I measure the accuracy using the Area Under the Precision-Recall Curve (AUPRC).<br> 
<div align=center><img width="400" height="350" src="https://github.com/AngelaZou/Credit-Card-Fraud-Detection-Project/blob/master/figure/fig2.png"/></div><br>
You can see all the codes in the jupyter notebook.<br>

## Certification

