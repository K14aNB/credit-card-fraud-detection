# **Credit Card Fraud Detection**

## **Problem Statement**
- A credit card is a small thin plastic or fiber card that incorporates information about the person such as a picture or signature and the person’s name on it to charge purchases and services to his linked account. Charges are debited regularly. Nowadays, card data is read by ATMs, swiping machines, store readers, banks and online transactions.
- Each card has a unique card number which is very important. Its security mainly relies on the physical security of the card and also the privacy of the credit card number. There is a rapid growth in credit card transactions which has led to substantial growth in scam cases.
- Credit card fraud is expanding heavily because fraud financial loss is increasing drastically. Multiple data mining and statistical techniques are used to catch fraud. Therefore, detection of fraud using efficient and secured methods is very important.

## **About the dataset**
The dataset contains transactions made by credit cards in September 2013 by European cardholders.

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly imbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, V3...V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are Time and Amount. Feature Time contains seconds elapsed between each transaction and the first transaction in the dataset. The feature Amount is the transaction amount, this feature can be used for example-dependent cost-sensitive learning. Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.
