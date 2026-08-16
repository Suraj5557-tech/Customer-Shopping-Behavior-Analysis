# 🛍️ End-to-End Customer Shopping Behavior Analysis

## 📌 Executive Summary
This project delivers a comprehensive, data-driven analysis of retail customer transactions ($N = 3,900$). By engineering data pipelines in **Python**, running analytical queries in **PostgreSQL**, and building an interactive dashboard in **Power BI**, this project uncovers actionable insights into customer demographics, spending patterns, discount elasticity, and subscription retention.

The final deliverables include an interactive **Power BI Dashboard** and a structured **Microsoft Word Executive Report** designed to drive business strategy and revenue optimization.

---

## 🛠️ Tech Stack & Methodology
* **Data Processing & Pipeline:** Python (Pandas, SQLAlchemy)
* **Relational Database:** PostgreSQL
* **Business Intelligence & Dashboards:** Power BI
* **Documentation & Reporting:** Microsoft Word

### Data Workflow Pipeline
1. **Data Ingestion & Cleaning:** Raw transactional data processed via Python (Pandas) for missing value imputation and schema standardization.
2. **Relational Staging:** Processed data streamed into PostgreSQL database for SQL aggregation and business queries.
3. **Visual Analytics & Reporting:** Interactive metrics modeled in Power BI and documented in an executive Microsoft Word report.

---

## 📊 Core Business Insights
* **Revenue Drivers:** Male shoppers generated **$157.9K** compared to **$75.2K** from Female shoppers due to higher order volumes.
* **Demographic Target:** **Young Adults** represent the highest revenue-contributing age group (**$62.1K**).
* **Subscription Growth Opportunity:** **73% of customers are non-subscribers**, yet they generate **$170.4K** in sales—making subscription conversion a top growth priority.
* **Discount Elasticity:** Over **49%** of purchases in categories like *Hats, Sneakers, and Coats* were discount-driven.
* **Customer Retention:** Over **80%** of the user base consists of **Loyal Repeat Buyers** (>5 previous orders).

---

## 📁 Repository Deliverables
* `Customer_Shopping_Behavior_Analysis_Report.docx` - Full detailed executive analysis report.
* `Customer_Behavior_Dashboard.pbix` - Interactive Power BI visual dashboard.
* `data_cleaning.py` - Python script for data preprocessing and DB staging.
* `analysis_queries.sql` - PostgreSQL queries used for analytical breakdowns.

---

## 💡 Strategic Recommendations
1. **Scale Subscription Conversion:** Launch post-purchase retention funnels offering free express shipping perks to convert non-subscribers.
2. **Protect Profit Margins:** Set a **$75+ minimum spend threshold** to qualify for discounts on high-demand categories.
3. **Reward Loyal Base:** Introduce a tiered VIP loyalty program for the **3,100+ repeat customers** to maximize average order value (AOV).
