# Online Shoppers Purchase Prediction using Machine Learning

# Project Overview

This project applies supervised machine learning techniques to predict whether an online visitor will complete a purchase before leaving an e-commerce website.

Using the Online Shoppers Purchasing Intention Dataset, three classification algorithms were developed, evaluated and compared to determine the most suitable model for deployment.

The project demonstrates the complete machine learning workflow, including:

- Business Understanding
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Model Development
- Model Evaluation
- Business Recommendations


# Business Problem

SmartShop Online is an international e-commerce retailer that wants to predict whether an online visitor is likely to complete a purchase.

Accurate predictions can help the business:

- Improve conversion rates
- Personalise marketing campaigns
- Recommend relevant products
- Reduce shopping cart abandonment
- Optimise marketing expenditure


# Dataset

Dataset: Online Shoppers Purchasing Intention Dataset

Source: UCI Machine Learning Repository

The dataset contains:

- 12,330 customer browsing sessions
- 17 predictor variables
- 1 target variable (Revenue)

Target Variable:

- TRUE = Purchase
- FALSE = No Purchase


# Machine Learning Workflow

# Exploratory Data Analysis

- Dataset exploration
- Summary statistics
- Missing value analysis
- Feature identification
- Target distribution
- Correlation analysis

# Data Preparation

- One-Hot Encoding
- Boolean Encoding
- Train-Test Split
- Feature Scaling using StandardScaler

# Classification Models

- Logistic Regression
- Support Vector Machine (Linear Kernel)
- Decision Tree Classifier


# Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|---------:|----------:|-------:|---------:|
| Logistic Regression | 85.35% | 51.81% | 75.17% | 61.34% |
| **Support Vector Machine (Linear)** | **86.83%** | **55.75%** | **72.03%** | **62.85%** |
| Decision Tree | 84.43% | 49.76% | 72.90% | 59.15% |

The Support Vector Machine achieved the strongest overall predictive performance and was selected as the recommended model.


# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


# Skills Demonstrated

- Exploratory Data Analysis
- Data Cleaning
- Feature Engineering
- Data Preprocessing
- Machine Learning
- Logistic Regression
- Support Vector Machines
- Decision Trees
- Model Evaluation
- Business Analytics
- Data Visualisation

## Business Outcome

The Support Vector Machine demonstrated the highest overall predictive performance and is recommended for deployment. The model can help e-commerce organisations identify customers who are most likely to complete a purchase, enabling more effective marketing strategies and improved customer conversion rates.
