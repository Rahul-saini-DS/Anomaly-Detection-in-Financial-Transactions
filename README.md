# Anomaly-Detection-in-Financial-Transactions

## Abstract
Credit card fraud is a significant problem, with billions of dollars lost each year. Machine learning can be used to detect credit card fraud by identifying patterns that are indicative of fraudulent transactions. Credit card fraud refers to the physical loss of a credit card or the loss of sensitive credit card information. Many machine-learning algorithms can be used for detection. This project proposes to develop a machine-learning model to detect credit card fraud. The model will be trained on a dataset of historical credit card transactions and evaluated on a holdout dataset of unseen transactions.

Keywords: Credit Card Fraud Detection, Fraud Detection, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree.

## Overview
With the increase in the use of credit cards in daily life, credit card companies must prioritize the security and safety of their customers. According to credit card statistics in 2021, 2.8 billion people used credit cards in 2019, and fraud reports in the U.S. rose by 44.7% in 2020.

There are two main types of credit card fraud:

New Account Fraud – When an account is opened under your name by an identity thief.

Account Takeover – When a thief uses an existing account, usually by stealing credit card information.

These rising trends motivated the use of machine learning methods to detect fraud in large transaction datasets.

## Project Goals
The goal of this project is to detect fraudulent credit card transactions and protect customers from unauthorized charges. The approach includes:

Using multiple ML models to identify fraud.

Comparing their performance.

Identifying the best algorithm for real-world deployment.

Visualizing fraud trends and model performance.

Reviewing related literature and fraud detection techniques.

## Data Source
The dataset is sourced from Kaggle and contains:

Transactions made by European credit card users in 2013 over two days.

Total rows: 284,808

Features: 31 (28 anonymized using PCA)

Notable attributes:

Time: Time elapsed from the first transaction

Amount: Transaction amount

Class: Label (0 = genuine, 1 = fraud)

## Algorithms Used
K-Nearest Neighbors (KNN)

Logistic Regression (LR)

Support Vector Machine (SVM)

Decision Tree (DT)

## Future Work
Future improvements may include:

Testing on more varied and large-scale datasets.

Changing the data split ratios for validation.

Integrating telecom/location data to spot geographic mismatches.

Real-time fraud alert systems based on user profiling and geolocation.

Example: If a user is in Dubai and their card is used in Abu Dhabi simultaneously, it can be flagged automatically.

## Conclusion
The objective of detecting fraudulent transactions using ML models was achieved successfully. Among the tested models, KNN and Decision Tree showed 100% accuracy on the given dataset. These results demonstrate the potential of machine learning to enhance fraud detection and improve customer trust by ensuring transactional security.
