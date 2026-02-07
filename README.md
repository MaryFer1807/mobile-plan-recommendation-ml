# Mobile Plan Recommendation – Machine Learning Project

## Project Overview
Megaline, a mobile telecommunications company, wants to reduce the number of customers using legacy plans by recommending one of its new plans: **Smart** or **Ultra**.

This project builds a machine learning classification model that analyzes customer behavior and predicts which plan is most suitable for each user. The analysis is based on real usage data from customers who have already switched to the new plans.

## Objective
The main objectives of this project are to:
- Build a classification model to recommend Smart or Ultra plans.
- Analyze customer behavior based on calls, messages, and internet usage.
- Compare different machine learning models and hyperparameters.
- Achieve a minimum accuracy score of **0.75** on the test dataset.
- Validate model performance using proper train, validation, and test splits.

## Dataset
The dataset contains monthly behavior data for each user with the following features:
- `calls`: number of calls made
- `minutes`: total call duration in minutes
- `messages`: number of text messages sent
- `mb_used`: internet traffic used (MB)
- `is_ultra`: target variable (Ultra = 1, Smart = 0)

## Data Preparation
- Loaded and examined the dataset structure.
- Separated features and target variable.
- Split the data into training, validation, and test sets.
- Ensured data consistency and readiness for modeling.

## Model Development
Several classification models were trained and evaluated by tuning their hyperparameters, including:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Model performance was compared using accuracy scores on the validation set to identify the most effective approach.

## Model Evaluation
- Selected the best-performing model based on validation accuracy.
- Evaluated final model performance using the test dataset.
- Confirmed that the accuracy threshold of **0.75** was achieved or exceeded.
- Conducted a sanity check to validate model behavior.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Business Value
This project helps Megaline:
- Automatically recommend optimal mobile plans for customers.
- Improve customer satisfaction by aligning plans with usage behavior.
- Reduce reliance on outdated plans.
- Apply machine learning to support data-driven business decisions.

The project demonstrates a complete machine learning workflow, from data preparation and model selection to evaluation and business interpretation.
