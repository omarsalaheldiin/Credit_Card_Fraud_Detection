# Credit Card Fraud Detection

## Overview
The goal of this project is to identify fraudulent credit card transactions using a variety of machine learning models.
Given the imbalanced nature of the dataset, special techniques are applied to ensure the model's effectiveness in detecting fraud.

## Dataset
- [The dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset used for this project is the Credit Card Fraud Detection dataset from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders.

It consists of:
Features: Time, V1-V28 (PCA components), Amount.
Target: class.

## Data Exploration and Visualization
The dataset is explored and visualized to understand the distribution of features and identify any patterns. Key steps include:
- Checking for missing data
- Examining the distribution of the target variable (Class)
- Visualizing transactions over time
- Analyzing transaction amounts

## Modeling
Multiple machine learning models are used and compared:
- Random Forest Classifier
- AdaBoost Classifier
- XGBoost Classifier

The data is split into training, validation, and test sets.

## Evaluation
Model performance is evaluated using various metrics:
- Confusion Matrix
- ROC-AUC Score
- Feature Importance

## Results
The best model is the XGBoost, it achieves an AUC score of 0.973. The most important features are identified, which include V14, V4, V12, V17, V10, and V7.

## Libraries To run the notebook:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
