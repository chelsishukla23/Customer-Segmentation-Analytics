📊 Telco Customer Segmentation & Churn Analytics

Power BI | Python | Machine Learning | Business Analytics

🔍 Project Overview

This project analyzes telecom customer data to identify distinct customer segments, understand churn behavior, and quantify revenue at risk. Using machine learning–driven clustering and interactive Power BI dashboards, the project converts raw customer data into actionable business insights that support retention, pricing, and product strategy decisions.

💼 Business Problem

Telecom companies face high customer churn, especially among short-tenure and high-usage customers. Traditional reporting often fails to explain why customers churn and which customers contribute the most revenue loss.

This project aims to:

Segment customers based on behavior and usage

Identify churn-prone customer groups

Quantify financial impact of churn

Provide data-driven recommendations to reduce revenue loss

🗂 Dataset Description

The dataset contains 7,000+ telecom customers with attributes related to:

Demographics: gender, senior citizen, dependents, partner

Service usage: internet type, security, streaming, tech support

Billing & contracts: payment method, contract type, monthly charges

Behavioral metrics: tenure, number of services

Financial metrics: Total Revenue, Lifetime Value (LTV)

Churn label: Yes / No

Additional engineered features include:

Customer Lifetime Value (LTV)

Average Monthly Revenue

High-Value Customer Flag

Cluster labels (ML-based)

🧠 Methodology

The project followed a structured analytics pipeline:

Data Cleaning & Feature Engineering

Handled missing values

Derived LTV, revenue, and service usage metrics

Standardized numeric variables

Customer Segmentation (ML)

Applied K-Means clustering

Optimal number of clusters chosen using Elbow Method & Silhouette Score

Reduced dimensionality using PCA & t-SNE for visualization

Cluster Profiling

Compared demographics, service usage, churn, and revenue

Built clear customer personas

Dashboard Development (Power BI)

Executive summary

Persona deep-dive

Churn risk & revenue impact analysis

👥 Customer Personas (Key Findings)
🟦 Cluster 0 — High-Value Loyal Customers

Long tenure, high LTV

Multi-year contracts

Lowest churn rate

Ideal for loyalty programs and premium upsell

🟨 Cluster 1 — Churn-Prone Revenue Segment

Short tenure, month-to-month contracts

High churn despite moderate–high spending

Requires targeted retention and contract incentives

🟩 Cluster 2 — Low-Value Stable Customers

Low usage and spending

Low churn risk

Limited upsell potential, cost-efficient servicing recommended

📉 Key Insights

Month-to-month contracts drive the majority of churn

Electronic check payment method is strongly associated with churn

A small subset of customers accounts for disproportionate revenue loss

Retention efforts should focus on high-LTV, churn-prone clusters

💡 Business Recommendations

Incentivize long-term contracts for churn-prone customers

Encourage auto-pay methods to reduce churn

Focus retention spend on high-LTV customers

Maintain low-cost service model for low-value segments

🛠 Tools & Technologies

Python: Pandas, NumPy, Scikit-learn

Machine Learning: K-Means, PCA, Silhouette Analysis

Visualization: Power BI

Analytics Techniques: Segmentation, churn analysis, revenue impact modeling

📂 Project Deliverables

Power BI Dashboard (PBIX & PDF)

Python Notebook (Data Processing & ML)

Customer Personas & Business Insights

Executive-ready Analytics Case Study

📌 Why This Project Matters

This project demonstrates the ability to:

Apply machine learning to real business problems

Translate analytics into executive-level insights

Build decision-driven dashboards

Think like a Data Analyst, Business Analyst, Product Analyst, and Consultant
