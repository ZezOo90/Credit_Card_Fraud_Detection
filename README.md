# Credit Card Fraud Detection Classifier

This repository contains a simple machine learning classifier model that predicts whether a credit card withdrawal transaction is fraudulent or legitimate. The model utilizes the logistic regression algorithm and achieves an impressive accuracy of 96%.

## Dataset

The dataset used for training and testing the model can be downloaded from Kaggle. It consists of various features related to credit card transactions, which are used as inputs for the classifier.

## Libraries Used

The following libraries were employed in building the classifier:

- Sklearn: A powerful machine learning library that provides various tools for classification, regression, and clustering tasks.
- Pandas: A versatile data manipulation library used for data preprocessing and analysis.
- Numpy: A fundamental package for scientific computing in Python, essential for handling arrays and matrices efficiently.

## Usage

To use this classifier model, follow these steps:

1. Download the dataset from Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
2. Install the required libraries (Sklearn, Pandas, Numpy).
3. Load the dataset into your Python environment using Pandas.
4. Preprocess the data if necessary (e.g., handle missing values, normalize features).
5. Split the dataset into training and testing sets.
6. Train the logistic regression model using Sklearn's `LogisticRegression` class.
7. Evaluate the accuracy of the trained model on the testing set.
8. Use the trained model to make predictions on new credit card withdrawal transactions.
