---
title: Telco Customer Churn EDA
---

# Telco Customer Churn EDA

**Skills:** Python, Pandas, EDA, Data Cleaning, Statistical Testing, Visualization  
**Repo:** [Repository](https://github.com/giosroom99/telco-churn-eda)  
**Notebook:** [notebooks/01_telco_churn_eda.ipynb](https://github.com/giosroom99/telco-churn-eda/blob/main/notebooks/01_telco_churn_eda.ipynb)

---

## 1) Problem

Which customer segments and service attributes are most associated with churn, and where should retention efforts be prioritized?

---

## 2) Data

- **Source:** IBM Telco Customer Churn dataset (file: `WA_Fn-UseC_-Telco-Customer-Churn.csv`)
- **Rows / Columns:** 7,043 rows, 21 columns
- **Target / Label:** `Churn` (Yes/No)
- **Key features:** tenure, MonthlyCharges, TotalCharges, Contract, PaymentMethod, InternetService, TechSupport, OnlineSecurity

### Data cleaning

- Missing values strategy: convert `TotalCharges` to numeric and fill missing values (from blank strings) with 0
- Outlier handling: not applied (EDA focus)
- Encoding: standardize `Churn`, map `SeniorCitizen` to Yes/No
- Train/validation split strategy: not applicable (EDA only)

---

## 3) Exploratory Data Analysis

Show 3-6 key visuals:

- Target balance (churn rate and counts)
- Numeric distributions (tenure, MonthlyCharges, TotalCharges)
- Churn rate by key categories (Contract, PaymentMethod, InternetService, TechSupport, OnlineSecurity)

**Key insights:**

- Churn is more concentrated in certain contract and service segments.
- Shorter-tenure customers show different churn behavior than long-tenure customers.
- Customers with fewer support/security add-ons show higher churn risk.

---

## 4) Modeling

### Baseline

- Not included (EDA-only scope)

### Final models tried

- Not included (EDA-only scope)

### Feature engineering

- Not included (EDA-only scope)

---

## 5) Evaluation

- Not included (EDA-only scope)

**Business framing:**  
Future modeling would weigh false negatives (missed churners) more heavily than false positives.

---

## 6) Results and Takeaways

- EDA identifies which segments show the strongest churn signals for targeted retention.
- Key drivers are service type, contract structure, and tenure-related patterns.
- With more time: build a baseline classifier and quantify lift from targeted retention.

---

## 7) Next Steps (Production-minded)

- Add a lightweight baseline model (logistic regression)
- Track churn rates over time by segment for drift
- Define retraining schedule and monitoring metrics
- Deploy batch scoring for weekly retention outreach lists

---

## Appendix

- Notebook: `notebooks/01_telco_churn_eda.ipynb`
- Output tables: `outputs/tables/numeric_tests.csv`

