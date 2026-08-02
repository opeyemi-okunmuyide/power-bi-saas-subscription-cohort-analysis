# SaaS Subscription Cohort Analysis Dashboard | Opeyemi Okunmuyide

## Project Overview

This project analyzes customer retention and subscription performance for a Software-as-a-Service (SaaS) business using Power BI.

The objective was to transform raw subscription data into an interactive dashboard that helps business stakeholders understand customer retention, churn trends, recurring revenue, subscription plans, and renewal behavior.

The project demonstrates an end-to-end business intelligence workflow, including data cleaning and transformation in Power Query, DAX calculations, and interactive dashboard development.

Although this project began as a guided exercise, the dashboard layout, visual design, and several analytical components were customized to improve usability.

---

## Business Problem

Subscription-based businesses rely on recurring revenue and customer retention for long-term growth. Understanding when customers churn, how long they remain subscribed, and which subscription plans generate the most value is essential for improving customer lifetime value.

This dashboard answers questions such as:

- How many active subscribers does the business currently have?
- What is the monthly churn rate?
- Which subscription plans generate the highest Monthly Recurring Revenue (MRR)?
- Which billing frequency is most popular?
- What percentage of customers renew their subscriptions automatically?
- How well are different customer cohorts retained over time?

---

## Tools Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

## Dataset

The dataset contains SaaS subscription information including:

- Subscription ID
- Customer ID
- Subscription Start Date
- Subscription End Date
- Subscription Plan
- Billing Frequency
- Monthly Recurring Revenue (MRR)
- Auto-Renew Status

---

# Data Preparation - Power Query

The following transformations were completed:

- Corrected data types
- Removed unnecessary columns
- Renamed columns for readability
- Standardized Billing Frequency values
- Standardized Auto-Renew values
- Created Start Date (SOM) to group subscriptions into monthly cohorts
- Expanded subscriptions into monthly records
- Created Month Number for retention analysis
- Created Month Span to calculate subscriber activity across time
- Created Plan Tier Sort column for custom report sorting

These transformations prepared the data for accurate retention calculations and interactive reporting.

---

# DAX Measures

The dashboard uses custom DAX measures to calculate key business metrics:

- **Total Subscriptions** – Counts the total number of subscriptions.
- **Active Subscriptions** – Counts subscriptions that are currently active.
- **Churned Subscriptions** – Counts subscriptions that have ended.
- **Churn Rate** – Calculates the percentage of subscriptions that have churned.
- **Total Monthly Recurring Revenue (MRR)** – Calculates the total recurring revenue generated from active subscriptions.

These measures update dynamically based on report filters and slicers.

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

Tracks customer retention by subscription month, allowing users to visualize how customer retention changes over time.

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

The dashboard reveals several important business insights:

- Enterprise plans generate the highest Monthly Recurring Revenue despite having fewer subscribers.
- Most subscribers have automatic renewal enabled.
- Customer retention gradually declines across successive cohort months, reflecting typical subscriber behavior in subscription-based businesses.
- The cohort matrix allows stakeholders to quickly identify periods of stronger or weaker customer retention.

---

# Dashboard Preview

<img width="1487" height="952" alt="dashboard-preview" src="https://github.com/user-attachments/assets/979e0f85-2add-4822-ba13-919ae1febd6e" />

---

# Skills Demonstrated

This project demonstrates practical experience with:

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- DAX
- Cohort Analysis
- Business Intelligence
- Interactive Dashboard Design
- Business Reporting
- Data Visualization
- Business Analysis
