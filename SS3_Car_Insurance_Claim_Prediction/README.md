# Car Insurance Claim Amount Prediction

A data analysis and baseline modeling project exploring what drives car insurance claim amounts. The goal is to understand the data, identify key predictors, and outline a path toward more accurate claim prediction.

# Project Summary
This project analyzes a car insurance dataset containing **1,185 policies** and **38 features**, including vehicle specs, safety features, policy details, and geography. The target variable, `claim_amount`, is highly right-skewed, making it a challenging regression problem.

# Objectives
- Explore and understand the dataset
- Identify features most correlated with claim amounts
- Build a baseline Linear Regression model
- Recommend improvements for future modeling

# Dataset Highlights
- Records: 1,185
- Features: 38
- Target: `claim_amount` (continuous)
- Key variables: `vehicle_class`, `fuel_type`, `engine_cc`, `bhp`, `torque`, `policy_tenure`, `age_of_car`, safety feature flags

# Key Findings
- Claim amounts are heavily right-skewed → log transformation recommended
- `vehicle_class`, `fuel_type`, and `engine_cc` are among the strongest predictors
- Safety features like airbags and ABS show moderate correlation
- Performance metrics (BHP, torque) also influence claim amounts
- `policy_tenure` and `age_of_car` have weaker but meaningful relationships

# Baseline Model
A Linear Regression model was trained using a log-transformed target.
Result: Low R² score — expected for noisy insurance claim data. The model provides a starting point but lacks the complexity needed to capture non-linear relationships.

# Recommendations
1. Apply **log transformation** to `claim_amount`
2. Use **target encoding** for high-cardinality features like `make` and `model`
3. Create **interaction features** such as `fuel_type * engine_cc`
4. Try advanced models: **XGBoost**, **Random Forest**, or **LightGBM**
5. Consider a hybrid approach: predict **claim probability** and **claim severity** separately
6. Add richer data: driver history, credit score, mileage, and regional accident stats

# Tech Stack
- Python
- Pandas / NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

