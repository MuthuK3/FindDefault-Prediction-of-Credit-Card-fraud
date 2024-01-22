## Clone the github repository

https://github.com/MuthuK3/FindDefault-Prediction-of-Credit-Card-fraud.git


# Project Title

Credit Card Fraud Detection

## Overview

This project aims to develop a machine learning model for detecting fraudulent credit card transactions using a dataset of transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with only a small percentage of transactions labeled as fraud.

## Dataset

The dataset contains transactions made in two days, with 492 frauds out of 284,807 transactions. The positive class (frauds) accounts for 0.172% of all transactions. The dataset file is named `credit_card.csv`.An highly imbalanced dataset.

## Code and Resources Used

Python Version: Google colaboratory

Packages: pandas, matplotlib, seaborn, numpy, sklearn, imblearn

## Project Detail

EDA :

  Checked for the null values in the dataset.
  Checked the imbalance in Class in the dataset.
  How the fraud and the non-fraudulent  occurs with respect to the transaction amount and distribution of the amount for positive(frauds) and negative(non-fraudulent) is shown in   a graph.
  Distribution of time also analysed as it doesnot largely affect the dataset.

Data Preprocessing :

  The imbalance in data can be handled by many methods, here oversampling method SMOTE is used to deal with the imbalance in the data.
  After applying SMOTE the imbalnce in the data is handled by oversampling the positive class(frauds) with the same as negative class(non-frauds)

Model Training :

  The machine learning model used for this project is a Random Forest Classifier. Adjustments to hyperparameters and model evaluation metrics are discussed in the notebook.

## Results 

The model achieved the following results on the test set,

    Accuracy        : 99.9386%
    Precision Score : 0.8421052631578947
    Recall          : 0.8
    F1 Score        : 0.8205128205128205

## Conclusion

  SMOTE solves the imbalance in the dataset by oversampling.
  The model Random Forest Classifier applied to this dataset gives almost perfecr accuracy for the dataset.

