# Telecom Customer Churn Analysis

## Project Overview

Customer churn is a critical challenge for subscription-based businesses because losing existing customers directly impacts revenue and long-term growth.

This project analyzes customer churn behavior in a telecom company to identify the key drivers of churn, quantify revenue at risk, and provide actionable recommendations to improve customer retention. The analysis combines SQL, Python, and Power BI to uncover churn patterns across customer segments, contract types, tenure groups, and churn categories.

---

## Business Questions

1. What is the overall churn rate and how much revenue is associated with churned customers?
2. How is revenue distributed across different customer value segments?
3. Are high-value customers more likely to churn compared to other segments?
4. How does contract type influence customer churn?
5. Does customer tenure impact churn behavior?
6. What are the primary reasons customers leave the company?

---

## Dataset

**Source:** Maven Analytics Data Playground

The dataset contains telecom customer information including:

* Customer demographics
* Subscription details
* Contract information
* Service usage
* Monthly and total charges
* Customer status
* Churn categories and reasons

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQL
* Power BI

---

## Project Workflow

### Data Cleaning & Preparation

* Handled missing values
* Standardized categorical variables
* Prepared data for analysis

### Feature Engineering

Created business-focused features such as:

* Churn Flag
* ARPU (Average Revenue Per User)
* Customer Value Segment
* Tenure Bucket

### Exploratory Data Analysis

Analyzed churn behavior across:

* Customer value segments
* Contract types
* Tenure groups
* Service subscriptions
* Churn categories

### Revenue Risk Analysis

Evaluated:

* Revenue at risk from churned customers
* Revenue loss by customer segment
* Revenue loss by churn category
* Impact of churn on high-value customers

### Dashboard Development

Built an interactive Power BI dashboard to monitor churn KPIs, customer segments, revenue risk, and churn drivers.

---

## Key Metrics

| KPI               |  Value |
| ----------------- | -----: |
| Total Customers   |  7,043 |
| Churned Customers |  1,869 |
| Churn Rate        | 26.54% |
| Revenue At Risk   | $3.68M |

---

## Key Findings

* Overall churn rate is approximately **26.5%**, representing significant customer attrition.
* Churned customers account for approximately **$3.68M** in revenue at risk.
* High-value customers contribute the largest share of revenue loss (**~$2.09M**).
* Customers on **Month-to-Month contracts** exhibit the highest churn rates.
* Customers within the first **0–6 months** of tenure show the highest churn behavior.
* **Competitor-related reasons** account for the largest share of customer churn.

---

## Business Recommendations

### Strengthen Early Customer Onboarding

Focus retention efforts during the first six months of the customer lifecycle to reduce early-stage churn.

### Increase Long-Term Contract Adoption

Encourage customers to migrate from month-to-month plans to longer-term contracts through targeted incentives.

### Prioritize High-Value Customer Retention

Develop retention campaigns specifically focused on high-value customer segments.

### Reduce Competitor-Driven Churn

Implement loyalty programs and targeted win-back campaigns to improve customer retention.

---

## Dashboard Overview

### Executive Churn Overview

* Churn KPIs
* Customer status distribution
* Churn rate by contract type
* Churn rate by tenure bucket
* Revenue at risk by value segment

### Revenue Risk & Root Cause Analysis

* Revenue loss by churn category
* Revenue loss by customer value segment
* Contract vs value segment churn matrix
* Top churn reasons
* Revenue loss by offer

---

## Dashboard Screenshots

### Executive Churn Overview

(Add Screenshot Here)

### Revenue Risk & Root Cause Analysis

(Add Screenshot Here)

---

## Repository Structure

```text
telecom-customer-churn-analysis/
│
├── telecom_churn_analysis.ipynb
├── telecom_customer_churn.csv
├── telecom_dashboard.pbix
├── dashboard_screenshots/
└── README.md
```

---

## Skills Demonstrated

* SQL Analysis
* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Customer Segmentation
* KPI Development
* Revenue Risk Analysis
* Business Analytics
* Power BI Dashboarding
* Business Storytelling
* Stakeholder-Focused Recommendations
