# Customer Intelligence & Churn Prediction Dashboard

## Project Overview

This project focuses on analyzing customer churn behavior and identifying high-risk customers using Machine Learning, Customer Segmentation, and Interactive Power BI Dashboards.

The objective is to help businesses improve customer retention by understanding churn drivers, customer value, and risk patterns.

---

## Business Problem

Customer churn directly impacts revenue and business growth. Organizations need to identify customers who are likely to leave and take proactive actions to retain them.

This project provides:

- Customer Segmentation using K-Means Clustering
- Churn Risk Analysis
- Revenue Impact Assessment
- Interactive Business Dashboards
- Actionable Business Insights

---

## Dataset

**IBM Telco Customer Churn Dataset**

Dataset includes:

- Customer Demographics
- Contract Information
- Payment Methods
- Internet Services
- Monthly Charges
- Total Charges
- Churn Status

Total Records: **7,043 Customers**

---

## Tools & Technologies

### Programming & Analytics

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

### Business Intelligence

- Power BI
- DAX
- Power Query

### Machine Learning

- K-Means Clustering
- Random Forest Classification

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

- Handled missing values
- Corrected data types
- Removed inconsistencies
- Prepared dataset for analysis

### 2. Exploratory Data Analysis (EDA)

- Customer demographics analysis
- Churn distribution analysis
- Service usage analysis
- Revenue analysis

### 3. Feature Engineering

Created additional business-focused features:

- RevenuePerMonth
- CustomerValue
- RiskScore
- TenureGroup

### 4. Customer Segmentation

Applied K-Means Clustering to group customers based on:

- Monthly Charges
- Total Charges
- Tenure
- Customer Value

### 5. Churn Prediction

Built a Random Forest model to:

- Predict customer churn
- Identify churn drivers
- Estimate customer risk

### 6. Dashboard Development

Created interactive Power BI dashboards for business stakeholders.

---

# Power BI Dashboards

## Executive Overview Dashboard

Features:

- Total Customers
- Churned Customers
- Churn Rate
- Revenue Analysis
- Contract Type Analysis
- Internet Service Analysis
- Payment Method Analysis

---

## Customer Segmentation Dashboard

Features:

- Customer Distribution by Segment
- Revenue Contribution by Segment
- Average Risk Score by Segment
- Revenue Per Month Analysis
- Customer Segmentation Scatter Plot

---

## Churn Risk Analysis Dashboard

Features:

- High Risk Customers
- Revenue at Risk
- Risk by Tenure Group
- Contract Type Risk Analysis
- Internet Service Risk Analysis
- Customer Risk Distribution

---

## Key Insights

### Customer Churn

- Month-to-month contract customers show the highest churn risk.
- Customers with shorter tenure are more likely to churn.
- Fiber Optic users exhibit higher churn rates compared to DSL users.

### Customer Segmentation

- High-value customer segments contribute significantly to revenue.
- Certain segments have elevated churn risk despite generating high revenue.
- Segmentation enables targeted retention strategies.

### Business Impact

- Identified high-risk customers and associated revenue exposure.
- Enabled data-driven retention planning.
- Improved understanding of customer behavior patterns.

---

## Project Structure

```text
Customer_Intelligence_and_Churn_Prediction
│
├── Customer_Churn_Analysis.ipynb
├── customer_segments.csv
├── requirements.txt
├── Customer_Intelligence_and_Churn_Prediction.pbix
│
├── screenshots
│   ├── executive_overview.png
│   ├── customer_segmentation.png
│   └── churn_risk_analysis.png
│
└── README.md
```

---

## Future Improvements

- XGBoost Model Implementation
- SHAP Explainability
- Real-Time Dashboard Integration
- Automated Data Refresh
- Deployment using Streamlit

---

## Author

**Ramisha**

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

---

## Project Highlights

✔ End-to-End Data Analytics Project

✔ Machine Learning-Based Churn Prediction

✔ Customer Segmentation using K-Means

✔ Interactive Power BI Dashboards

✔ Business-Oriented Insights and Recommendations
