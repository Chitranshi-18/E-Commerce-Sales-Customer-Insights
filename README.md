# E-Commerce-Sales & Customer-Insights

---

## 📘 Overview

This project analyzes an e-commerce transactional dataset to understand customer purchasing behavior, identify high-value customers, and evaluate sales performance using Python and Power BI. The focus is on business metrics such as AOV, CLV, RFM segmentation, and revenue concentration patterns.

---

## 🛠️ Tools & Technologies

- **Python**: Pandas, NumPy, Matplotlib – Data cleaning, EDA, customer metrics
- **Power BI**: Interactive dashboards and KPI visualization
- **Statistics (Descriptive)**: Trend and distribution analysis

---

## 🗂️ Dataset Structure

- **Source:** Kaggle – E-Commerce Sales Dataset
- **Type:** Single transactional dataset containing:
  - Invoice ID
  - Customer ID
  - Product details
  - Quantity & price
  - Transaction date

---
## 📂 Project Structure

```
E-Commerce-Sales-Customer-Insights/
├── data/ # CSV datasets (raw and cleaned)
│ └── ecommerce_data.csv
├── python/ # Python notebooks for analysis
│ ├── 01_Data_Cleaning.ipynb
│ ├── 02_Customer_Metrics.ipynb
│ └── 03_RFM_Analysis.ipynb
├── results/ # Output CSVs, charts, and metrics
├── power_bi/ # Power BI dashboards
└── README.md # Project overview and instructions
```
---
## 🚀 Project Workflow

1. **Data Cleaning (Python)**
   - Removed cancelled and invalid transactions
   - Converted date columns to datetime format
   - Created revenue feature (Quantity × UnitPrice)
2. **Sales & Customer Metrics**
   - Average Order Value (AOV)
   - Customer Lifetime Value (CLV)
   - Purchase frequency per customer
3. **RFM Analysis**
   - Calculated **Recency, Frequency, Monetary** metrics
   - Segmented customers into RFM score groups
   - Identified high-value and at-risk customer segments
4. **Revenue Concentration Analysis**
   - Applied Pareto analysis
   - Found that ~30% of customers contribute ~70% of total revenue
5. **Power BI Dashboard**
   - Sales KPIs (Revenue, Orders, AOV)
   - Customer segmentation (RFM & CLV)
   - Revenue trends over time
   - Top customers and contribution analysis

---

## 📊 Key KPIs

- **Total Revenue**
- **Average Order Value (AOV)**
- **Customer Lifetime Value (CLV)**
- **Purchase Frequency**
- **RFM Segments**

---

## 🔍 Insights Generated

- A small percentage of customers generate the majority of revenue (Pareto effect)
- High-frequency, high-monetary customers show strong retention behavior
- RFM segmentation helps identify churn-risk customers for targeted engagement

---

## 📝 Future Improvements

- Add cohort analysis for retention tracking
- Implement customer clustering using K-Means
- Predict customer churn using basic ML models
