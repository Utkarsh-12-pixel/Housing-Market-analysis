#  Housing Market Analysis Dashboard (End-to-End Project)

## Project Overview
This project is an end-to-end data analysis solution built using Power BI and Google BigQuery. It focuses on analyzing housing market trends including sales performance, pricing patterns, and regional insights.

---

##  Data Source
- Source: Google BigQuery (Cloud Data Warehouse)
- Dataset: Housing Data
- Data includes:
  - Purchase Price
  - Offer Price
  - Region
  - Sales Type
  - Date
  - Area (SQM)

---

##  Data Processing (SQL - BigQuery)

- Created a new table from raw data
- Performed aggregation using SQL

Example Query:
```sql
SELECT sales_type, AVG(purchase_price)
FROM `project.dataset.Test`
GROUP BY sales_type;
```

---

## Tools & Technologies
- Power BI
- DAX (Data Analysis Expressions)
- Power Query
- Google BigQuery (SQL)

---

##  Data Modeling
- Created a dedicated measures table
- Used relationships for efficient filtering
- Applied optimized DAX calculations

---

##  Key DAX Measures

- Last 12 Months Sales (Rolling Window)
- Year-over-Year Sales Growth
- Median Price Change
- Total YTD Sales
- Units Sold (Latest Quarter)
- Sales by Region
- Average Price per SQM
- Offer to SQM Ratio

---

##  Dashboard Features

### 1. Market Overview
- Price trends by region
- Total sales metrics
- Offer vs Purchase price analysis

### 2. Sales Performance
- Region-wise sales
- Key Influencers visual
- Time-based analysis

### 3. House Type Analysis
- Price comparison by property type
- SQM pricing trends
- Inflation & yield comparison

---

##  Key Insights

- Sales performance varies significantly by region
- Strong correlation between offer price and purchase price
- Certain house types show higher profitability
- Year-over-year growth trends highlight market fluctuations

---

##  Dashboard Preview

1 house market overview
<img width="1920" height="1020" alt="Screenshotsoverview png" src="https://github.com/user-attachments/assets/5f1c020e-b5f7-4822-9751-fc48f886d3df" />
2 Sales performance
<img width="1920" height="1020" alt="Screenshotssales png" src="https://github.com/user-attachments/assets/d4bd7a7d-86e9-4aa5-b4c5-7bff8ae2380f" />
3 House type analysis
<img width="1920" height="1020" alt="Screenshotshouse_type png" src="https://github.com/user-attachments/assets/c9f783a9-2d9e-4acf-a17b-08bf0d9431d4" />






---

##  Conclusion
This project demonstrates end-to-end data analytics workflow:
Data Extraction → Data Cleaning → Data Modeling → DAX Calculations → Data Visualization → Business Insights

---

##  Project Link
https://github.com/Utkarsh-12-pixel/Housing-Market-analysis
