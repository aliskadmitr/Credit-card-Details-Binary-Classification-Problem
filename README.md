# Credit-card-Details-Binary-Classification-Problem
## F1 Score 99% / OverSampling / RNN / LazyClassifier / RandomForestCkassifier

### Overview
This project aims to address the Credit Card Details Binary Classification Problem by predicting whether a credit card transaction is fraudulent based on the provided data. The challenge involves using machine learning techniques to achieve high accuracy and performance, ensuring the model can effectively distinguish between fraudulent and non-fraudulent transactions.
---
### Dataset
The dataset contains several features related to credit card transactions, including demographic information about the cardholder and transaction details. The target variable is binary, indicating whether the transaction is fraudulent or not.

Features:
* GENDER
* Car_Owner
* Propert_Owner
* Type_Income
* EDUCATION
* Marital_status
* Housing_type
* Mobile_phone
* Work_Phone
* Phone
* Type_Occupation
* EMAIL_ID
* CHILDREN
* Family_Members
* Annual_income
* Birthday_count
* Employed_days
---
### Approach
Data Preprocessing
Handling Missing Values: Missing values in the dataset were replaced with the median for numerical columns and the mode for categorical columns.

Model Selection and Evaluation
Initially, various classifiers were tested using the LazyClassifier library to quickly evaluate their performance. The LazyClassifier provides a fast way to compare the performance of multiple classifiers with minimal code.

Best Performing Model
The best-performing model was identified as the RandomForestClassifier, achieving an F1 score of 99%. This model was selected for its superior performance in distinguishing between fraudulent and non-fraudulent transactions.
---


### Getting Started
To reproduce the results or further experiment with the dataset, follow these steps:

Clone the repository.
Install the required dependencies.
Run the preprocessing script to prepare the data.
Train and evaluate the models using the provided notebooks.
Dependencies
Python 3.x
pandas
numpy
scikit-learn
matplotlib
tensorflow
keras
LazyPredict
Acknowledgments
We would like to thank the Kaggle community for providing the platform and resources to work on this interesting and challenging problem.
