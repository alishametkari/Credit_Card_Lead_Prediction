# Credit_Card_Lead_Prediction
Hackathon Project - Credit Card Lead Prediction, by analytics vidya.
### Problem Statement :

Happy Customer Bank is a mid-sized private bank that deals in all kinds of banking products, like Savings accounts, Current accounts, investment products, credit products, among other offerings. The bank also cross-sells products to its existing customers and to do so they use different kinds of communication like tele-calling, e-mails, recommendations on net banking, mobile banking, etc. In this case, the Happy Customer Bank wants to cross sell its credit cards to its existing customers. The bank has identified a set of customers that are eligible for taking these credit cards. Now, the bank is looking for your help in identifying customers that could show higher intent towards a recommended credit card, given: Customer details (gender, age, region etc.) Details of his/her relationship with the bank (Channel_Code,Vintage, 'Avg_Asset_Value etc.)

### Approach :
I have used Random forest model and logistics regression for classification. I have used Grid Search method for hyperparameter tuning and RFE method for feature selection. To handle imbalance in data, I have used SMOTE technique. Random Forest classifier classified most of the tuples correctly, hence I chose Random Forest for prediction of test data set.

### Hackathon Score : 0.86224
### Hackathon Rank : 694 / 8141
