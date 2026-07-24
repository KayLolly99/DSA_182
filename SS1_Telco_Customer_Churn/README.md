# Telco Customer Churn Prediction

This project uses logistic regression to predict which customers are likely to churn (cancel their services) for a telecommunications provider.

# What This Project Does

The model analyses customer data including demographics, service usage, and account history to identify customers at risk of leaving. The goal is to help the business take proactive retention actions before customers cancel their services.

## Skills Demonstrated
- Data cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Logistic Regression
- Model Evaluation
- Confusion Matrix
- ROC-AUC

## Tools
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

# Key Findings

The strongest predictors of customer churn were:
- Contract type – Two-year contracts significantly reduce churn risk
- Internet service type – Fibre optic customers are more likely to churn
- Add-on services – Customers with online security and tech support are less likely to churn

# Model Performance

The model achieved a ROC-AUC score of approximately 0.78, indicating good ability to distinguish between customers who will churn and those who will stay.

# Business Recommendations

- Convert month-to-month customers to longer contracts
- Investigate why fibre optic customers are churning at higher rates
- Promote online security and tech support services to reduce churn
