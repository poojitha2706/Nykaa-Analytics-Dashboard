# 💄 Nykaa E-Commerce Analytics Dashboard

## Overview
End-to-end business analytics project on Nykaa's product and sales data 
using Python, SQL, and Power BI.

## Tools Used
Python | Pandas | Seaborn | SQLite | Power BI

## Dataset
- 551 real Nykaa products (Kaggle)
- 3,000 synthetic orders generated in Python

## Key Business Insights
- Makeup drives 37% of total revenue (₹11.3L)
- Premium products (₹3242 avg) rate 4.42 vs 4.17 for mid-range
- 59% of orders include discounts — platform discount-dependent
- Bobbi Brown leads brand revenue among luxury segment
- December & March are peak revenue months

## Dashboard Pages
1. Executive Overview — KPIs, revenue trend, category breakdown
2. Product Intelligence — brand ranking, price vs rating, segment analysis
3. Discounts & Insights — discount impact, monthly orders, AOV
## Dashboard Preview

### Page 1 — Executive Overview
![Executive Overview](charts/page1_executive.png)

### Page 2 — Product Intelligence  
![Product Intelligence](charts/page2_products.png)

### Page 3 — Discounts & Insights
![Discounts](charts/page3_discounts.png)

## Project Structure
Nykaa-Analytics-Dashboard/
├── data/                  ← CSV files
├── charts/                ← Python visualizations
├── Nykaa_EDA.ipynb        ← Google Colab notebook
└── Nykaa_Dashboard.pbix   ← Power BI dashboard
