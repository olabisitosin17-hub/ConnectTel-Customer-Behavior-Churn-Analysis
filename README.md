# ConnectTel Customer Behavior Churn Analysis
## Project Overview

This project analyzes customer behavior and churn patterns to understand service preferences, customer retention, revenue performance, and key factors associated with customer churn. The analysis was conducted using Power BI and Excel on 7,043 customer records.

## Business Problem

ConnectTel wanted to understand customer usage patterns, service preferences, and customer lifetime value across different segments. The analysis was intended to inform marketing campaigns, service improvements, and customer retention strategies.

## Dataset

**Dataset:** Telco Customer Churn

**Source:** Kaggle

**Records:** 7,043 customers

**Original columns:** 21

**Final dataset:** 7,043 rows × 24 columns

## Tools Used

- **Microsoft Excel** — Data preparation and analysis
- **Power BI** — Interactive dashboard and visualization

## 🧹 Data Cleaning & Preparation

The dataset was cleaned and enriched before analysis to improve data quality, readability, and analytical usefulness.

- **Data Cleaning & Standardization:** Resolved missing values by converting 11 blank `TotalCharges` entries to `0` for new customers. Standardized `SeniorCitizen` values to "Yes/No", mapped "No internet/phone service" entries to "No" across seven columns, and renamed key tenure and fee variables for readability.
- **Feature Engineering:** Added three structured analytical fields:
    - **`Tenure_Group`**: Segmented customer longevity into New (0–12m), Growing (13–24m), Established (25–48m), and Loyal (49+m).
    - **`Service_Count`**: Calculated active services per customer.
    - **`Bundling`**: Flagged users subscribing to two or more services.
- **Final Output:** Delivered a clean, complete dataset comprising **7,043 rows and 24 columns** with zero missing values.

### 🔎 Analysis

### Customer Behavior Analysis

---

## Dashboards

📊 Power BI Dashboard

(screenshot/!Screenshot 2026-09-22 164840.png)

!Screenshot 2026-09-22 164914.png

!Screenshot 2026-09-22 164944.png

### **🔍 Key Insights**

- **26.54% churn rate** — 1,869 customers churned.
- **$139K revenue** was lost to churn.
- Month-to-month customers are the highest-risk contract group.
- New customers in their first 12 months are most vulnerable.
- Bundling is associated with stronger customer loyalty.
- Senior customers show substantially higher churn.
- Higher monthly charges, particularly for Fibre optic customers, are associated with higher churn.

### **Business Recommendations**

- Strengthen 90-day onboarding for new customers.
- Encourage migration to long-term contracts.
- Promote bundled service packages.
- Develop a senior-customer retention programme.
- Encourage automatic payment methods.
- Review Fibre optic pricing and offer targeted loyalty incentives.
