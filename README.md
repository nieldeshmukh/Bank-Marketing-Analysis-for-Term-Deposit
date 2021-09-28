# Bank-Marketing-Analysis
![Alt text](term_deposit.png?raw=true "Title")

## Objective

1. Bank Marketing dataset is collected from direct marketing campaign of a bank institution from Portuguese.

2. Marketing campaign can be understood as phone calls to the clients to  convince them accept to make a term deposit with their bank.

3. After each call, they are being noted as to no - being the client did  not make a deposit and yes - being the client on call accepted to make a  deposit.

4. The purpose of this project is to predict if the client on call would  accept to make a term deposit or not based on the information of the  clients.
5. For More Information refer https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

## Main  Issues with the dataset

1. There is data imbalance between two classes The number of yes(1) is very low in comparison to no(0)

2. Missing Value in the dataset.

## Techniques Used

1. General Data cleaning and data handling and EDA.
2. Feature Encoding and Feature Scaling with MinMaxScaler.
3. Used Logistic regression, Support Vector Classifier(SVC) for training data.
4. To deal with data imbalance we use SMOTE - Synthetic Minority Over-sampling Technique. 
* SMOTE: creates synthetic (not duplicate) samples of the minority class. Hence 
         making the minority class equal to the majority class. SMOTE does this 
         by selecting similar records and altering that record one column at a 
         time by a random amount within the difference to the neighbouring records.

## Result

![Alt text](roc_after_SMOTE.png?raw=true "Title")

### AUC after applying SMOTE = 0.931
