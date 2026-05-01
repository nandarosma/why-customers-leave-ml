# why-customers-leave-ml
-Project Overview

This project aims to analyze customer behavior and predict churn using machine learning techniques.
By identifying key factors that influence customer churn, this project provides insights to support better customer retention strategies.

-Dataset

Source: Telco Customer Churn Dataset
Total records: ~7,000 customers

Features include:

Customer demographics

Service subscriptions

Billing information

Contract type

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

-Data Preprocessing

To ensure data quality, several cleaning steps were performed:

Converted TotalCharges from object → numeric

Removed missing values (11 rows)

Removed duplicate data (22 rows)

Dropped irrelevant column (customerID)

Result: Clean dataset ready for analysis and modeling

-Exploratory Data Analysis (EDA)

EDA was conducted to understand patterns and relationships between features and churn.

a. Key Findings:
1. Contract Type vs Churn
Month-to-month → ~42.6% churn (highest)
1-year → ~11%
2-year → ~2.8% (lowest)

Customers without long-term commitment are more likely to churn.

2. Tenure vs Churn
Churn customers → ~18 months
Non-churn customers → ~37 months

New customers are more likely to leave.

3. Monthly Charges vs Churn
Churn customers → ~74.6
Non-churn → ~61.3

Higher cost is associated with higher churn risk.
