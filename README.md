# Customer Shopping Behavior Analysis  
**End-to-End Data Analytics Project**

## Overview
This project analyzes customer shopping behavior for a retail business using transactional data to uncover insights into purchasing patterns, customer segments, and revenue drivers. The objective was to transform raw customer data into actionable insights that support data-driven marketing, product strategy, and customer retention decisions.

The project follows a complete end-to-end analytics workflow, starting from data cleaning and feature engineering, moving through SQL-based business analysis, and concluding with interactive data visualization and stakeholder-ready insights.

---

## Business Problem
Retail leadership observed shifts in purchasing behavior across demographics, product categories, and sales channels. They wanted to understand:
- What factors influence customer spending
- How discounts and subscriptions affect purchase value
- Which customer segments drive the most revenue
- How insights can be used to improve engagement and loyalty

---

## Dataset
- **Total Records:** 3,900 purchase transactions  
- **Total Features:** 18 columns  
- **Data Type:** Retail transactional data  

**Key Attributes**
- Customer demographics (age, gender, location, subscription status)
- Purchase details (item, category, season, purchase amount)
- Behavioral indicators (discount usage, shipping type, review ratings, purchase frequency)

**Data Quality**
- 37 missing values in the review rating column, handled during preprocessing

---

## Tools & Technologies
- **Python:** Pandas, NumPy (data cleaning, feature engineering)
- **SQL (PostgreSQL):** Business analysis, segmentation, aggregations
- **Power BI:** Interactive dashboards and KPI visualization
- **Excel:** Data validation and exploratory checks

---

## Data Preparation & Feature Engineering
Data preparation was performed in Python to ensure consistency and analytical readiness. Key steps included:
- Standardizing column names for readability
- Handling missing review ratings using median imputation by product category
- Creating derived features such as age groups and purchase frequency indicators
- Validating discount and promotion fields to remove redundancy
- Loading the cleaned dataset into PostgreSQL for structured SQL analysis

---

## SQL-Based Business Analysis
SQL was used to answer business-focused questions and simulate real-world analytics workflows. Key analyses included:
- Revenue comparison by gender
- Identification of high-spending customers who used discounts
- Top-rated products based on average customer reviews
- Comparison of average purchase value by shipping type
- Subscriber vs. non-subscriber spending behavior
- Customer segmentation into New, Returning, and Loyal groups
- Revenue contribution by age group
- Relationship between repeat purchases and subscription adoption

All SQL queries used in the analysis are included in this repository.

---

## Power BI Dashboard
An interactive Power BI dashboard was developed to visualize insights and support stakeholder decision-making. The dashboard highlights:
- Total customers
- Average purchase amount
- Average review rating
- Revenue by product category
- Subscription status distribution
- Sales and revenue by age group
- Interactive filters for dynamic exploration

---

## Key Insights
- Subscription customers demonstrate stronger loyalty and repeat purchasing behavior
- Express shipping users spend more per transaction compared to standard shipping users
- Discounts do not necessarily reduce purchase value when applied strategically
- Loyal customers account for the majority of transactions
- Revenue contributions are relatively balanced across age groups, indicating broad market appeal

---

## Business Recommendations
- Promote subscription benefits to increase customer lifetime value
- Implement loyalty programs to convert returning customers into loyal customers
- Optimize discount strategies to balance sales growth with margin protection
- Highlight top-rated and best-selling products in marketing campaigns
- Target express shipping users with premium and personalized offers

---

## Repository Structure
```text
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── Customer_Behavior_Analysis.ipynb
├── sql/
│   └── SQLQuery1.sql
├── powerbi/
│   └── Customer_Behavior_Dashboard.pbix
├── presentation/
│   └── Customer-Shopping-Behavior-Analysis.pptx
├── reports/
│   └── Customer_Shopping_Behavior_Analysis.pdf
└── README.md
