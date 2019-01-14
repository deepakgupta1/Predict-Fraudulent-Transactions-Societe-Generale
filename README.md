# Predict-Fraudulent-Transactions-Societe-Generale
Predict the probability of a transaction being fraudulent.

### Problem
Societe Generale (SocGen) is a French multinational banking and financial services company. With over 1,54,000 employees, based in 76 countries, they handle over 32 million clients throughout the world on a daily basis.

They provide services like retail banking, corporate and investment banking, asset management, portfolio management, insurance and other financial services.

While dealing with innumerable money transactions, they’ve set up an internal team which closely monitors and alarms the transactions which could be deemed fraudulent.

In this problem, given an anonymised data of transactions, you have to predict the probability of a transaction being fraudulent.

### Approach

### Feature engineering: 
Made some interaction features. Since features were masked could not do much FE. I also changed the features:
* Target encoding of categorical features
* Count of high cardinality features

### Models
Made several models with different sets of features, selected the one with best cross validation score. Final model is a xgboost model trained on target encoding of categorical features.

### Tools
* Sklearn
* Matplotlib
* pandas
