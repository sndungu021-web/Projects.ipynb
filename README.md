# Overview

This project demonstrates a complete Machine Learning pipeline using the Titanic dataset. The goal is to predict whether a passenger survived the Titanic disaster based on demographic and travel-related features.

The project covers the entire ML workflow, from data preprocessing and feature engineering to model training, evaluation, and prediction.

# Project Objectives
- Perform exploratory data analysis (EDA)
- Clean and preprocess raw data
- Handle missing values and categorical features
- Engineer meaningful features
- Train and compare machine learning models
- Evaluate model performance
- Generate predictions for unseen data
- Create a reusable and scalable ML pipeline

# Dataset
The dataset contains passenger information from the Titanic disaster.

# Features
| Feature     | Description                       |
| ----------- | --------------------------------- |
| PassengerId | Unique passenger identifier       |
| Pclass      | Ticket class (1st, 2nd, 3rd)      |
| Name        | Passenger name                    |
| Sex         | Gender                            |
| Age         | Passenger age                     |
| SibSp       | Number of siblings/spouses aboard |
| Parch       | Number of parents/children aboard |
| Ticket      | Ticket number                     |
| Fare        | Ticket fare                       |
| Cabin       | Cabin number                      |
| Embarked    | Port of embarkation               |

# Target Variable
Survived
- 0 = Did not survive
- 1 = Survived

# Machine Learning Pipeline
## 1. Data Ingestion
- Load training and testing datasets
- Validate data integrity
- Inspect data types and missing values

## 2. Data Preprocessing
- Handle missing values
- Encode categorical variables
- Scale numerical features
- Remove irrelevant columns

## 3. Feature Engineering
- Create family size feature
- Extract passenger titles from names
- Generate categorical age groups
- Create fare categories

## 4. Model Training
Models evaluated:
- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- Gradient Boosting Classifier
- XGBoost (optional)

## 5. Model Evaluation
- Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Scor

## 6. Prediction
Generate predictions on the test dataset and export results for submission.
=>Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
