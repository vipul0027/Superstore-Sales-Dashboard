# 📊 Superstore Sales Dashboard & 15-Day Forecast (Power BI)

---

## 🔎 Project Overview

This end-to-end Data And Business Intelligence project analyzes Superstore sales data to uncover performance trends, profitability drivers, and short-term sales projections using Microsoft Power BI.

The objective was not just to build visuals, but to simulate a real-world business scenario where management requires KPI-driven dashboards and forecast-backed insights for strategic decision-making.

---

## 🎯 Business Problem Statement

The company needed:

- Clear visibility into sales and profit performance
- Identification of high and low-performing regions
- Customer segment contribution analysis
- Shipping & payment behavior insights
- Short-term sales forecasting for inventory & operational planning

---

## 📊 Dataset Summary

- 2M+ Total Sales
- 22K+ Orders
- 175K+ Profit
- Multiple categories, sub-categories, regions & segments

---

## 🛠️ Tools & Technologies Used

- Microsoft Power BI
- Power Query (Data Cleaning & Transformation)
- DAX (Calculated Measures & KPIs)
- Data Modeling & Relationships
- Time Intelligence Functions
- Sales Forecasting Visualization

---

## 🧮 DAX & Time Intelligence Implementation

To enhance analytical depth, several DAX measures were created:

### 🔹 Key DAX Measures Implemented

- Total Sales = SUM(Sales[Sales])
- Total Profit = SUM(Sales[Profit])
- Total Orders = DISTINCTCOUNT(Sales[Order ID])
- Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)


### 🔹 Core KPI Measures

- Total Sales = SUM(Sales[Sales])
- Total Profit = SUM(Sales[Profit])
- Total Orders = DISTINCTCOUNT(Sales[Order ID])
- Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

### 🔹 Time Intelligence Measures

- Year-over-Year (YoY) Sales Growth
- YoY Profit Growth
- SAMEPERIODLASTYEAR() comparisons
- DATEADD() for time shifting
- Monthly trend evaluation
- Growth trend analysis to support forecasting

These calculations enabled deeper business analysis beyond simple aggregation.

---

## 📈 Key Insights Generated

- Technology category contributed the highest overall revenue.
- Consumer segment accounted for the largest sales share.
- West & East regions dominated overall revenue contribution.
- Standard Class shipping was the most frequently used mode.
- Certain states showed high revenue but lower profit margins.
- Seasonal trends revealed strong performance in Q3 & Q4.
- 15-Day forecasting highlighted potential short-term revenue patterns.

---

## 📊 Dashboard Features

- Interactive slicers & filters
- Region-wise and state-wise performance map
- Category & Sub-Category breakdown
- Segment & Payment Mode analysis
- Year-over-Year Monthly Sales & Profit comparison
- 15-Day Sales Forecast visualization
- KPI cards for performance monitoring

![Dashboard](<img width="1743" height="742" alt="Screenshot 2026-02-13 134429" src="https://github.com/user-attachments/assets/f505f68b-0690-48d1-9dad-bbc82ec857e5" />
)
---

## 💡 Business Impact Perspective

If implemented in a real organization, this dashboard would help:

- Optimize inventory planning using forecast insights
- Improve profitability by identifying low-margin regions
- Support marketing campaigns targeting high-value segments
- Enhance operational efficiency through shipping trend analysis
- Enable data-driven strategic decisions

---

## 🧠 Key Learning Outcomes

Through this project, I strengthened:

- End-to-end Business Intelligence workflow understanding
- Data cleaning & transformation using Power Query
- Practical implementation of DAX calculations
- Hands-on experience with Time Intelligence functions
- KPI-driven dashboard design principles
- Business interpretation of revenue & profit trends
- Understanding of seasonality & short-term forecasting
- Analytical thinking and data storytelling skills

---

## ⚡ Challenges Faced

- Cleaning inconsistent transactional data
- Managing relationships between multiple tables
- Creating accurate Year-over-Year DAX measures
- Balancing dashboard clarity with analytical depth
- Interpreting forecast outputs meaningfully

---

## 🚀 Future Improvements

- Adding advanced DAX KPIs (Rolling Average, CAGR, Dynamic Growth %)
- Implementing drill-through & drill-down reports
- Automating refresh via Power BI Service
- Deploying dashboard for real-time cloud access

---

## 👨‍💼 Author

Vipul Kamble  
Aspiring Data Analyst  
Open to Data Analyst / Business Intelligence roles
