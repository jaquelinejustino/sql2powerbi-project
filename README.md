# SQL to Power BI Project

Welcome to this portfolio project! 🚀

This end-to-end solution demonstrates my ability to design and implement a complete data pipeline from SQL-based data modeling and data warehouse development to interactive dashboard creation in Power BI.
It follows industry best practices in data engineering, modeling (star schema), and business intelligence, with a focus on delivering insights that support decision-making.
The goal is to showcase my technical skills and analytical thinking in real-world business scenarios.

---
## 🏗️ Data Architecture

The project applies the Medallion Architecture framework organizing data across *Bronze*, *Silver*, and *Gold* layers to ensure scalability, quality, and clarity throughout the pipeline:

![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Stores raw, unprocessed data ingested from CSV files into a SQL Server database.
2. **Silver Layer**: Applies data cleansing, normalization, and standardization, preparing data for reliable downstream use.
3. **Gold Layer**: Contains curated, business-ready data modeled in a star schema, optimized for reporting and analytics.

---
## 📖 Project Overview

This project showcases the full data lifecycle, combining technical execution with strategic thinking:

1. **Modern Data Architecture**: Designing and implementing a Medallion-based warehouse to organize and govern data effectively.
2. **ETL Development**: Building robust ETL processes to extract, transform, and load data into the SQL Server database.
3. **Dimensional Modeling**: Creating fact and dimension tables following star schema principles for performance and usability.
4. **Data Analysis & Reporting**: Delivering actionable insights through Power BI dashboards supported by DAX measures and SQL queries.

---
## 📊 Dashboard Insights – 2012 Annual Sales
Overview: Analysis of annual sales performance integrating KPIs for sales, profit, orders, and customers.

🔍 Key Insights
   • Sales: ↓ 17.43% vs. PY – despite 📈 +53.29% orders and +46.89% customers.

   • Profit: ↓ 27.14% – possible cost increase or margin compression.

   • Bikes dominate revenue, but profit margins may be under pressure.

   • Geographic concentration: Majority of sales in Australia and United States.

   • Customer dependency: Top 10 customers represent a large share of total sales.

💡 Recommendations

   • Margin Optimization: Review pricing & cost structure in high-volume products.
   
   • Market Diversification: Grow sales in underperforming regions (e.g., France, Germany).

   • Product Mix Expansion: Increase share of accessories/clothing for margin boost.
  
   • Customer Retention: Loyalty programs & targeted offers for top customers.

---

This dashboard highlights both performance trends and strategic opportunities, demonstrating my ability to combine data visualization with business-oriented analysis.

---
![sales_dashboard](power_bi/sales_dashboard.png)
