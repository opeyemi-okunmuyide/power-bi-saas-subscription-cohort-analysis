# SaaS Subscription Cohort Analysis Dashboard

**Author:** Opeyemi Okunmuyide

## Project Overview

This project explores customer retention and subscription performance for a Software-as-a-Service (SaaS) business using Power BI.

Using a publicly available SaaS subscription dataset from Kaggle, I transformed raw subscription data into an interactive dashboard that provides insights into customer retention, churn trends, recurring revenue, subscription plans, and renewal behavior.

The project demonstrates an end-to-end business intelligence workflow, including data cleaning and transformation in Power Query, DAX calculations, and interactive dashboard development.

---

## Business Problem

Subscription-based businesses rely on recurring revenue and customer retention for long-term growth. Understanding when customers churn, how long they remain subscribed, and which subscription plans generate the most value is essential for improving customer lifetime value.

This dashboard answers questions such as:

- How many active subscribers does the business currently have?
- What is the monthly churn rate?
- Which subscription plans generate the highest Monthly Recurring Revenue (MRR)?
- Which billing frequency is most popular?
- What percentage of customers renew their subscriptions automatically?
- How well are different customer cohorts retain customers over time?

---

## Tools Used

- Power BI
- Power Query
- DAX
- Data Visualization

---

## Dataset

The dataset used in this project was obtained from Kaggle.

**Source:** *[SaaS Subscription & Churn Analytics Dataset](https://www.kaggle.com/datasets/rivalytics/saas-subscription-and-churn-analytics-dataset?utm_source=chatgpt.com)*

It contains SaaS subscription information including:

- Subscription ID
- Customer ID
- Subscription Start Date
- Subscription End Date
- Subscription Plan
- Billing Frequency
- Monthly Recurring Revenue (MRR)
- Auto-Renew Status

The dataset was selected because it closely matched the structure required for subscription cohort analysis while allowing the project to be completed using an independent public dataset.

---

# Data Preparation (Power Query)

The raw dataset was cleaned and transformed in Power Query to support cohort analysis and interactive reporting.

The following transformations were completed:

- Corrected data types
- Removed unnecessary columns
- Renamed columns for readability
- Standardized Billing Frequency values
- Standardized Auto-Renew values
- Created **Start Date (SOM)** to group subscriptions into monthly cohorts
- Expanded subscriptions into monthly records
- Created **Month Number** for retention analysis
- Created **Month Span** to calculate subscriber activity across time
- Created **Plan Tier Sort** for custom report sorting

These transformations prepared the dataset for accurate retention calculations and dynamic reporting.

---

# DAX Measures

Custom DAX measures were created to calculate key business metrics used throughout the dashboard.

- **Total Subscriptions** – Counts the total number of subscriptions.
- **Active Subscriptions** – Counts subscriptions that are currently active.
- **Churned Subscriptions** – Counts subscriptions that have ended.
- **Churn Rate** – Calculates the percentage of subscriptions that have churned.
- **Total Monthly Recurring Revenue (MRR)** – Calculates total recurring revenue generated from active subscriptions.

These measures respond dynamically to report filters and slicers.

---

# Dashboard Features

The dashboard includes:

### KPI Cards

- Total Subscriptions
- Active Subscriptions
- Churned Subscriptions
- Churn Rate
- Total Monthly Recurring Revenue

### Cohort Analysis Matrix

Visualizes monthly customer retention by cohort, allowing retention trends to be tracked over time.

### Revenue Analysis

Displays Monthly Recurring Revenue (MRR) by subscription plan to compare revenue contribution across plan tiers.

### Subscription Analysis

Provides visual breakdowns of:

- Subscription Plan Distribution
- Billing Frequency Distribution
- Auto-Renew Status

### Interactive Filters

Users can filter the dashboard by:

- Subscription Plan
- Billing Frequency
- Auto-Renew Status

---

# Key Insights

The dashboard highlights several business insights:

- Enterprise plans generate the highest Monthly Recurring Revenue despite having fewer subscribers.
- Most subscribers have automatic renewal enabled.
- Customer retention gradually declines across successive cohort months, reflecting typical subscriber behavior in subscription-based businesses.
- The cohort matrix allows retention performance to be compared across different subscription cohorts.

---

# Dashboard Preview

<img width="1487" height="952" alt="dashboard-preview" src="https://github.com/user-attachments/assets/72e2746f-cc77-4357-a3d0-65483a9dda4d" />

---

# Skills Demonstrated

This project demonstrates practical experience with:

- Data Cleaning
- Power Query
- DAX
- Cohort Analysis
- Business Intelligence
- Interactive Dashboard Design
- Business Reporting
- Data Visualization
- Business Analysis

# What I Learned

Through this project, I strengthened my understanding of:

- Power Query data transformation
- DAX measure creation
- Cohort analysis and retention reporting
- Interactive dashboard design
- Translating business questions into data visualizations
