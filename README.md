Microsoft Fabric - Sales Analytics Dashboard
Project Overview
This project showcases a Sales Analytics Dashboard built using Microsoft Fabric and Power BI.
The dashboard provides an interactive view of sales performance, customer trends, product performance, and key business metrics.
Tools & Technologies
	Microsoft Fabric
	Power BI
	DAX
	Power Query
	Data Visualization
	Data Analysis
Steps used to create a project and also rectify errors
	Data Source – GitHub: Stored the raw sales datasets/CSV files in a GitHub repository for centralized and version-controlled access. 
	Data Loading into Fabric: Imported the GitHub CSV data into Microsoft Fabric Warehouse (wh_sales) and created the required analytics schema. 
	Warehouse & Data Modeling: Created fact_sales and dimension tables — dim_date, dim_customer, dim_product, and dim_region — following a Star Schema. 
	SQL Data Validation: Used Fabric SQL to check NULL values, duplicates, data types, table structures, views, and stored procedures. 
	Error Rectification: Identified NULL order_date_key values in fact_sales, corrected the missing keys, and validated all 1,268 records. 
	Power BI Dashboard: Connected Power BI to the Fabric Warehouse and created DAX measures, KPI cards, trend analysis, category/region analysis, and customer rankings. 
	Testing & Final Validation: Refreshed the Power BI model, verified relationships, slicers and visuals, and resolved the monthly trend (Blank) issue.
Dashboard Highlights
The dashboard focuses on:
	Total Sales
	Sales Performance
	Customer Analysis
	Product Performance
	Sales Trends
	Key Performance Indicators (KPIs)
	Interactive Data Visualizations
Dashboard Screenshots
Sales Analytics Dashboard
[Microsoft Fabric Sales Analytics Dashboard](Sales_Data_Analysis_Screenshots.pdf)
Key Insights
The dashboard helps users understand sales trends and business performance through interactive visualizations and KPIs.
It enables users to identify:
	Top-performing products
	Sales trends over time
	Customer purchasing patterns
	Overall business performance
Skills Demonstrated
	Data Analysis
	SQL
	Pyspark
	Data Visualization
	Dashboard Development
	Power BI
	DAX
	Power Query
	Microsoft Fabric

