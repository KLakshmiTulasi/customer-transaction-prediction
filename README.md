# Customer Transaction Prediction

## Overview

Banks and financial institutions need to identify customers who are likely to perform transactions in the future. Predicting customer transaction behavior enables targeted marketing, improved customer engagement, and better resource allocation.

This project uses Machine Learning classification algorithms to predict whether a customer will make a future transaction based on historical customer data.

## Problem Statement

Build a predictive model that classifies customers into:

* 0 = Customer will not make a transaction
* 1 = Customer will make a transaction

## Dataset

The dataset contains:

* 200 anonymized customer features
* ID_Code
* Target variable

The target variable indicates whether the customer is expected to perform a future transaction.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

## Machine Learning Models Implemented

* Logistic Regression
* Decision Tree
* Support Vector Machine (SVM)
* Random Forest
* XGBoost

## Hyperparameter Tuning

GridSearchCV was used to optimize model performance and identify the best parameter combinations.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score

## Results

Multiple machine learning models were trained and evaluated. Hyperparameter tuning further improved model performance and helped identify the most suitable model for production deployment.

## Business Impact

Accurate transaction prediction can help banks:

* Improve customer targeting
* Increase marketing effectiveness
* Reduce operational costs
* Improve customer retention strategies

## Future Improvements

* Feature Engineering
* Ensemble Learning
* Advanced Boosting Techniques
* Model Deployment using Flask or FastAPI
