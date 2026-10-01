# Customer Churn Prediction using Machine Learning

## Project Overview

Customer Churn Prediction is a machine learning project that predicts whether a customer is likely to leave a service.

The project uses customer information such as tenure, contract type, monthly charges, payment method, and other service details to identify customers who are at higher risk of churn.

## Objective

* Analyze customer data to identify churn patterns.
* Perform Exploratory Data Analysis (EDA).
* Build classification models to predict customer churn.
* Compare different machine learning models using Accuracy, Recall, and ROC-AUC.
* Identify important factors that contribute to customer churn.

## Dataset

The project uses the **Telco Customer Churn** dataset.

The dataset contains information about:

* Customer demographics
* Account information
* Services subscribed
* Contract details
* Payment methods
* Monthly and total charges
* Customer churn status

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Encoding
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis
10. Model Comparison

## Exploratory Data Analysis

The following factors were analyzed to understand customer churn:

* Churn distribution
* Customer tenure
* Monthly charges
* Contract type
* Payment method
* Senior citizen status

Visualizations were created using Matplotlib and Seaborn.

## Machine Learning Models

Three classification models were implemented:

### 1. Logistic Regression

Used as a baseline classification model for predicting customer churn.

### 2. Random Forest

An ensemble learning algorithm used to capture complex relationships between customer features and churn.

### 3. XGBoost

A gradient boosting algorithm used for classification and predictive modeling.

## Model Evaluation

The models were evaluated using:

* Accuracy
* Recall
* ROC-AUC
* Classification Report
* Confusion Matrix
* ROC Curve

## Feature Importance

Random Forest and XGBoost feature importance were analyzed to identify which customer attributes have the greatest influence on churn prediction.

## Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
└── Dataset
```

## Conclusion

This project demonstrates how machine learning can be used to predict customer churn and identify patterns associated with customers leaving a service.

Logistic Regression, Random Forest, and XGBoost were trained and evaluated using multiple performance metrics. The analysis can help businesses identify customers who may be at risk of churn and support data-driven customer retention strategies.
