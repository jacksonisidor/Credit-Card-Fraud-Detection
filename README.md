# Credit Card Fraud Detection

## Overview
The primary objective of this project is develop a model that can accurately identify fraudulent credit card transactions. This repository contains a detailed data science project that uses credit card transaction history to practice various data science and machine learning skills.

## Skills Used: 
- Data Preprocessing: Exploring, handling missing values, and preparing the data for modeling.
- Imbalance Data Strategies: Given a heavy data imbalance, I tested strategies like oversampling (SMOTE) and undersampling to find the best approach.
- Outlier Management: Used statistics knowledge to effectively handle outliers and mitigate the risk of adversely affecting model training. 
- Model Selection: I tested various models and used knowledge from personal experience to make the optimal choice, which ended up being an XGBoost classifier.
- Feature Engineering: Extracted meaningful information from the data in an attempt to optimize the model through important/coorelated features.
- Hyperparameter Tuning: Used Bayesian Optimization to identify the best set of parameters to use in the XGBoost model. I came across an issue with the oversampled data, and successfully adapted to a random search technique.
- Model Evaluation: Imbalanced test data can reduce the interpretability of accuracy scores, so I analyzed both AUPRC and classification reports to come up with a conclusion that weighed the advantages and disadvantages of two models.

## Data Source
All data used is sourced from ['Credit Card Card Fraud Detection'](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) by Machine Learning Group on Kaggle. Clicking on the link will take you to the Kaggle data card. This data contains information on transactions made by credit cards in September 2013 by European cardholders.

## Repository Structure
- `cc_fraud_detection.ipynb`: A Jupyter Notebook containing the steps to producing a credit card fraud detection models. 

