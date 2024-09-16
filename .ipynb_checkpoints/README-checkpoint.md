# Online Payments Fraud Detection with Machine Learning
The introduction of online payment systems has helped a lot in the ease of payments. But, at the same time, it increased in payment frauds. Online payment frauds can happen with anyone using any payment system, especially while making payments using a credit card. That is why detecting online payment fraud is very important for credit card companies to ensure that the customers are not getting charged for the products and services they never paid.

## DataSet
I collected a **[dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)** from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. Below are all the columns from the dataset I’m using here:

- step: represents a unit of time where 1 step equals 1 hour
- type: type of online transaction
- amount: the amount of the transaction
- nameOrig: customer starting the transaction
- oldbalanceOrg: balance before the transaction
- newbalanceOrig: balance after the transaction
- nameDest: recipient of the transaction
- oldbalanceDest: initial balance of recipient before the transaction
- newbalanceDest: the new balance of recipient after the transaction
- isFraud: fraud transaction

## Decision Tree Classifier Model
A **Decision Tree Classifier** is a popular and versatile machine learning algorithm used for classification tasks. Here’s a brief summary:

- **Structure:** It models decisions in a tree-like structure, where each internal node represents a decision based on a feature, each branch represents the outcome of that decision, and each leaf node represents a class label.
- **Working:** The model splits the data into subsets based on the value of input features. This process is repeated recursively, creating a tree where each path from the root to a leaf represents a classification rule.
