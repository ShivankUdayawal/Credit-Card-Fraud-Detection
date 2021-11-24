# Credit-Card-Fraud-Detection
## Recognizing Fraudulent Credit Card Transactions

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/04.jpg)

### Introduction :
There have always been people who would develop new ways to illegally access someone's finances since the payment systems were invented. This has become a huge issue in the modern era, because all purchases can be made online with just your credit card information. Even before two-step verification was employed for online purchasing in the United States in the 2010s, many American retail website users were victims of online transaction fraud. When a data breach results in monetary theft and, as a result, the loss of customers' loyalty and the company's reputation, it puts organisations, consumers, banks, and merchants at danger.

In 2017, unauthorised card operations claimed the lives of 16.7 million people. Furthermore, according to the Federal Trade Commission (FTC), credit card fraud claims increased by 40% in 2017 compared to the previous year. Around 13,000 incidents were reported in California and 8,000 in Florida, the two states with the highest per capita rates of this sort of crime. The amount of money at stake will exceed approximately $30 billion by 2020.

### What is Credit Card Fraud Detection?
“A series of operations conducted to prevent money or property from being gained under false pretences is known as fraud detection.”
Fraud can be committed in a variety of ways and in a wide range of industries. To make a decision, the majority of detection systems combine a number of fraud detection datasets to create a connected picture of both legitimate and invalid payment data. This decision must consider IP address, geolocation, device identification, “BIN” data, global latitude/longitude, historic transaction patterns, and the actual transaction information. In practice, this means that merchants and issuers deploy analytically based responses that use internal and external data to apply a set of business rules or analytical algorithms to detect fraud.

### False application fraud :
App fraud is often accompanied by account / identity theft. This means that someone is applying to open a new credit account or credit card in a different name. First, criminals steal documents that will serve as proof of your fake claim.

Anomaly detection helps determine if a transaction has abnormal patterns such as date and time or quantity of items. If the algorithm detects this unusual behavior, the bank account holder is protected by several verification methods.

### How Does Credit Card Fraud Happen?
Credit card fraud is commonly induced both through card owner’s negligence together along with his statistics or through a breach in a website’s security.
Here are a few examples:

The consumer discloses his credit card number to unknown persons.
The card is lost or stolen and is being used by someone else.
Messages stolen from intended recipients and used by criminals.
Employees of the company copy the card or card number of the owner.
Manufacture of counterfeit credit cards.
If your card is lost or stolen, unauthorized debiting of funds may occur; That is, the person who finds it uses it to make a purchase. Criminals can also spoof your name and use a card or order certain items through a mobile phone or computer. There is also the problem of using counterfeit credit cards - counterfeit cards with real account information that have been stolen from the cardholder. This is especially dangerous because the victim has their real card, but they don't know that someone copied their card. These fraudulent cards look legitimate and have a logo and a magnetic code on them. original stripe.Fraudulent credit cards are often destroyed by criminals after several successful payments, shortly before the victim realizes the problem and reports it.

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/06.jpg)

### Business Challenge :
Detecting fraud transactions is of great importance for any credit card company. We are tasked by a well-known company to detect potential frauds so that customers are not charged for items that they did not purchase.

So the goal is to build a classifier that tells if a transaction is a fraud or not.


The challenge is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.

#### Main challenges involved in credit card fraud detection are:
  1. Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.
  2. Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones.
  3. Data availability as the data is mostly private.
  4. Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported.
  5. Adaptive techniques used against the model by the scammers.

#### How to tackle these challenges?
  1. The model used must be simple and fast enough to detect the anomaly and classify it as a fraudulent transaction as quickly as possible.
  2. Imbalance can be dealt with by properly using some methods.
  3. For protecting the privacy of the user the dimensionality of the data can be reduced.
  4. A more trustworthy source must be taken which double-check the data, at least for training the model.
  5. We can make the model simple and interpretable so that when the scammer adapts to it with just some tweaks we can have a new model up and running to deploy.

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/07.jpg)

### Description of Dataset :
  1. The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly Imbalanced, the positive class (frauds) account for 0.172% of all transactions.

  2. It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

  3. Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

  4. The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/10.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/11.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/12.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/13.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/15.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/16.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/17.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/18.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/19.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/20.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/21.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/22.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/23.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/24.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/25.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/26.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/27.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/28.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/29.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/30.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/31.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/32.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/33.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/34.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/35.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/36.jpg)

![](https://github.com/ShivankUdayawal/Credit-Card-Fraud-Detection/blob/main/Data%20Visualization/37.jpg)
