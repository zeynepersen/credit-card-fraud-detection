# Credit Card Fraud Detection with 4 Machine Learning Algorithms


## Dataset Overview
**Time**: The seconds elapsed between this transaction and the first transaction in the dataset. It helps in understanding the distribution of transactions over time.

**V1 to V28**: These are the principal components obtained using PCA (Principal Component Analysis). They are anonymized to protect confidentiality.

**Amount**: The transaction amount. This feature can be useful for cost-sensitive learning.
Class: The response variable, where 1 indicates a fraudulent transaction and 0 indicates a legitimate transaction.

## Project Goal

The goal of this project is to develop an effective machine learning-based credit card fraud detection system that accurately identifies fraudulent transactions from legitimate ones in an imbalanced dataset. By employing techniques such as SMOTE (Synthetic Minority Over-sampling Technique) and Random Under-sampling, and leveraging predictive models including Random Forest, Logistic Regression, K-Nearest Neighbors, and Neural Networks using TensorFlow, the project aims to enhance the detection performance, ensuring high precision, recall, and overall robustness in identifying fraud while minimizing false positives. The ultimate objective is to provide a reliable and efficient tool for credit card companies to prevent fraudulent activities and safeguard customers' financial transactions.
## Imbalanced Data

Imbalanced data refers to datasets where the classes are not represented equally. This is common in many real-world scenarios, such as fraud detection, where fraudulent transactions (positive class) are much fewer than legitimate transactions (negative class). This imbalance can cause problems for machine learning models, as they may become biased towards the majority class and fail to adequately learn to identify the minority class.


