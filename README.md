# ATM-Fraud-Detection
![images](https://user-images.githubusercontent.com/92949677/173197847-c9b768e3-5149-47ec-93da-7fb08fca47ab.jpg)

- This a real time ATM Fraud Detection project 
- In this project,we will train the past given data by using Deep Neural Network and will make prediction.

# Abstract
In this project,we will deal with the fraud detection in ATM.Australian banking client's profitability and reputation are being hit by fraudulent ATM transactions. They want PredCatch to help them in reducing and if possible completely eliminating such fraudulent transactions. PredCatch believes it can do the same by building a predictive model to catch such fraudulent transactions in real time and decline them. The Job is to build this fraud detection and prevention predictive model.
The challenging part of the problem is that the data contains very few fraud instances in comparison to the overall population. To give more edge to the solution they have also collected data regarding location [geo_scores] of the transactions, their own proprietary index [Lambda_wts], on network turn around times [Qset_tats] and vulnerability qualification score [instance_scores]. As of now you don't need to understand what they mean.The data has been provided with different names because of the confidenciaity.

# Introduction
Over the past two decades, consumers across the
globe have come to depend on and trust the ATM to
conveniently meet their banking needs. As banks
have introduced ATMs approximately 25 years ago,
from that time, the fraudsters are also trying to start
tapping into the system. In recent years there has been
a proliferation of ATM frauds across the globe.

Many banks have not sufficiently educated the
customers on the basic usage of cards, resulting in
ignorant card holders either losing their cards in the
machine, or panic-stricken customers breaking the
glass door to exit the ATM enclosure after a latenight transaction.

# Types of ATM Fraud
## 1.Operational Fraud - 
- Operational fraud, typically, is
perpetrated from within; employees responsible for
ATM management can accidentally expose ATMs to
fraud by making sensitive information readily
available to fraudsters. 
## 2.Equipment Fraud -
Another concern for operators
of ATMs is fraud related to fake ATM equipment.
This ranges from add-on devices such as fake card
readers or skimmers to ruses involving false fascias
or even bogus ATMs.
## 3.Digital Fraud-
The migration of proprietary
operating system to Microsoft Windows technology
has led to greater connectivity and inter-connectivity
of ATMs. Vast network including ATMs, branch
system, phone systems, ticketing systems, and other
infrastructure connected via the World Wide Webare susceptible to a new kind of threat, a threat to
digital security. 

# Objective-
The main objective of this project is to make a prediction model that can detect future frauds and can help in preventing the fraud transactions.

# Main Problem
The main problem of this project is that we have very less fraud data which makes it little challenging and also the features are given a different name,so we will not able to understand the features.The data is also very huge ,so using Machine learning algorithm will take too much time.

# Steps to be followed
1. Understand the Problem and Objectives
2. Understand the data and develope some problem solving idea.
3. Exploratory Data Analysis
4. Merging the different given data to make a single DataFrame.
5. Data cleaning (if require)
6. Split the train and test data
7. Use Deep Neural Network to train the data.
8. Evaluation of the data.
9. Predict the target variable for given test data.

# Important Libraries
1. Pandas 
2. Numpy
3. seaborn
4. sklearn
5. tensorflow
6. keras

# Conclusion
In this project,we explored the utility of the Deep Neural Network using Multilayer Perceptron(MLP),one of the model of Deep Learning.
The accuracy and the confusion matrix was extremely good and gave a hint to predict future frauds using this model.






