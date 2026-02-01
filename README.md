# Telco Customer Churn Analysis

This project analyzes customer churn behavior in a telecommunications dataset to identify key drivers of attrition and derive actionable business insights that can inform customer retention strategies.

The focus of this analysis is on understanding *why* customers churn rather than immediately building a complex predictive model.

---

## Problem Statement

Customer churn is a major challenge in the telecom industry, directly impacting revenue and customer lifetime value.  
This project aims to:

- Quantify overall churn
- Identify high-risk customer segments
- Understand how contract type, tenure, pricing, and payment behavior influence churn

---

## Dataset

- **Source:** IBM Telco Customer Churn dataset  
- **Records:** 7,000+ customers  
- **Target Variable:** `Churn` (Yes / No)

### Key Features
- Customer tenure
- Monthly and total charges
- Contract type
- Payment method
- Internet and phone service details

---

## Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- Git & GitHub

---

## Data Cleaning & Preparation

- Converted `TotalCharges` from string to numeric
- Handled missing values created during type conversion
- Verified class balance and feature distributions before analysis

---

## Exploratory Data Analysis

The analysis focuses on both numerical and categorical drivers of churn.

### Key Findings

- **Tenure:**  
  Churn is heavily concentrated among early-tenure customers. Customers who remain beyond the first 1–2 years are significantly less likely to churn.

- **Contract Type:**  
  Month-to-month contracts show dramatically higher churn compared to one-year and two-year contracts.

- **Monthly Charges:**  
  Customers with higher monthly charges exhibit a higher likelihood of churn, especially when paired with short contract durations.

- **Payment Method:**  
  Customers using electronic checks have substantially higher churn rates compared to those using automatic payment methods.

---

## Business Insights

- Churn is not random; it is strongly driven by customer commitment level and billing behavior.
- Early lifecycle engagement is critical to retention.
- Contract upgrades and payment method incentives represent high-impact retention levers.
- High-paying customers without long-term contracts are the most at-risk segment.

---
## Next Steps

- Feature engineering (tenure buckets, pricing ratios)
- Baseline churn prediction using Logistic Regression
- Tree-based models (XGBoost) with SHAP explainability
- Retention strategy simulation and ROI estimation

---

## Author

DHARKIVE-STUDIO

