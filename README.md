# 📊 Telecom Customer Segmentation & Churn Analytics

**Power BI | Python | Machine Learning | Business Analytics**

## 🔍 Project Overview

This project analyzes telecom customer data to identify distinct customer segments, understand churn behavior, and quantify revenue at risk. Using machine learning–driven clustering and interactive Power BI dashboards, the project transforms raw customer data into actionable business insights that support retention, pricing, and customer engagement strategies.

## 👨‍💻 My Role

* Performed data cleaning, preprocessing, and feature engineering using Python.
* Conducted exploratory data analysis (EDA) to uncover customer behavior patterns.
* Built customer segmentation models using K-Means clustering.
* Evaluated clustering quality using the Elbow Method and Silhouette Score.
* Developed interactive Power BI dashboards to visualize customer segments, churn risk, and revenue impact.
* Generated business recommendations to improve customer retention and profitability.

---

## 💼 Business Problem

Telecom companies often struggle with customer churn, particularly among short-tenure and high-usage customers. Traditional reports provide churn statistics but fail to explain:

* Which customers are most likely to churn
* Which customer groups contribute the highest revenue
* Where retention efforts should be focused

This project addresses these challenges by combining machine learning and business analytics to identify meaningful customer segments and quantify churn-related revenue risk.

---

## 🎯 Project Objectives

* Segment customers based on demographics, service usage, and spending behavior.
* Identify high-risk customer groups likely to churn.
* Measure the revenue impact associated with customer churn.
* Build interactive dashboards for business stakeholders.
* Provide actionable recommendations for retention and growth strategies.

---

## 🗂 Dataset Description

The dataset contains over **7,000 telecom customers** with information related to:

### Customer Demographics

* Gender
* Senior Citizen Status
* Partner
* Dependents

### Service Usage

* Internet Service Type
* Online Security
* Device Protection
* Streaming Services
* Technical Support

### Billing & Contracts

* Contract Type
* Payment Method
* Monthly Charges
* Total Charges

### Customer Behavior

* Tenure
* Number of Services Used

### Business Metrics

* Customer Lifetime Value (LTV)
* Average Monthly Revenue
* Churn Status

### Engineered Features

* High-Value Customer Flag
* Revenue-Based Metrics
* Cluster Labels
* Churn Risk Indicators

---

## 🧠 Methodology

### 1. Data Cleaning & Preprocessing

* Handled missing values and inconsistent records.
* Converted categorical variables into machine-learning-ready formats.
* Standardized numerical features for clustering.
* Created derived business metrics and revenue indicators.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics and service adoption.
* Investigated churn trends across customer groups.
* Studied revenue distribution and contract behavior.
* Identified key variables influencing customer retention.

### 3. Customer Segmentation

Applied **K-Means Clustering** to group customers based on behavioral and financial characteristics.

#### Model Selection

* Elbow Method used to determine the optimal number of clusters.
* Silhouette Score used to validate cluster quality.
* PCA and dimensionality reduction techniques used for cluster visualization.

### 4. Cluster Profiling

Each cluster was analyzed based on:

* Revenue contribution
* Churn rate
* Customer tenure
* Contract preferences
* Service adoption behavior
* Customer Lifetime Value (LTV)

### 5. Dashboard Development

Interactive Power BI dashboards were created to provide:

* Executive Summary
* Customer Personas
* Churn Risk Analysis
* Revenue Impact Assessment
* Business Recommendations

---

## 👥 Customer Personas

### 🟦 Cluster 0 – High-Value Loyal Customers

**Characteristics**

* Long customer tenure
* High Lifetime Value
* Multi-year contracts
* Strong service adoption

**Business Opportunity**

* Loyalty programs
* Premium product upselling
* Referral campaigns

---

### 🟨 Cluster 1 – Churn-Prone Revenue Segment

**Characteristics**

* Short tenure
* Month-to-month contracts
* Moderate to high spending
* Elevated churn probability

**Business Opportunity**

* Retention campaigns
* Contract conversion incentives
* Personalized engagement offers

---

### 🟩 Cluster 2 – Low-Value Stable Customers

**Characteristics**

* Lower spending levels
* Limited service usage
* Low churn risk

**Business Opportunity**

* Cost-efficient servicing
* Selective cross-selling opportunities

---

## 📉 Key Insights

* Month-to-month contracts contribute significantly to overall churn.
* Customers using electronic check payment methods exhibit higher churn rates.
* A relatively small customer segment contributes a disproportionately high share of revenue loss.
* High-LTV customers require focused retention strategies.
* Contract duration and service adoption strongly influence customer loyalty.

---

## 💡 Business Recommendations

### Retention Strategy

* Incentivize long-term contract adoption among churn-prone customers.
* Implement personalized retention offers for high-value customers.

### Payment Optimization

* Encourage customers to switch to automated payment methods.

### Revenue Protection

* Prioritize retention investments for high-LTV customer segments.

### Customer Growth

* Upsell premium services to loyal customer groups.
* Expand engagement initiatives for valuable customer segments.

---

## 📊 Dashboard Highlights

The Power BI dashboard includes:

* Executive Summary
* Customer Segmentation Overview
* Customer Persona Analysis
* Churn Risk & Revenue Impact Analysis
* Strategic Business Recommendations

---

## 🛠 Tools & Technologies

### Programming & Analytics

* Python
* Pandas
* NumPy

### Machine Learning

* Scikit-Learn
* K-Means Clustering
* PCA
* Silhouette Analysis

### Data Visualization

* Power BI

### Business Analytics

* Customer Segmentation
* Churn Analysis
* Revenue Impact Modeling
* Customer Lifetime Value (LTV) Analysis

---

## 📂 Repository Structure

```text
dashboard/
├── Telco_Customer_Segmentation_Dashboard.pbix
├── Telco_Customer_Segmentation_Dashboard.pdf

data/
├── Telco_Data_Final.csv
├── Teleco-customer segmentation.xlsx

images/
├── Executive Summary.png
├── Customer Personas & Cluster Insights.png
├── Churn Risk & Revenue Impact.png
├── BUSINESS RECOMMENDATIONS.png

notebooks/
├── Telco_Customer_Segmentation.ipynb

README.md
```

---

## 📌 Business Impact

This project demonstrates the ability to:

* Apply machine learning techniques to solve real business problems.
* Translate complex analytical findings into executive-level insights.
* Build interactive dashboards that support data-driven decision-making.
* Combine technical analytics with business strategy and stakeholder communication.

---

## 🚀 Future Enhancements

* Deploy dashboards online for stakeholder access.
* Implement predictive churn modeling using supervised learning.
* Automate data refresh and reporting workflows.
* Integrate customer recommendation and retention scoring systems.
