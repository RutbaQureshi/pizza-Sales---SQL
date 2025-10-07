**Pizza Sales Analytics using SQL & Power BI**
A complete end-to-end analytics project that explores pizza sales data using MySQL and Power BI. This repository includes SQL scripts for data import, transformation, and analysis — followed by Power BI visualizations to uncover sales insights and performance trends.



**Project Overview**
This project demonstrates how to:
1. Import and manage data from CSV files in MySQL.
2. Perform business analysis through SQL queries.
3. Visualize key metrics in Power BI.


**🗂️ Dataset**
The dataset consists of four CSV files located in the /data folder:
File Name	Description
1. orders.csv	            Contains order timestamps and order IDs
2. order_details.csv	    Maps each order to the pizzas and quantities purchased
3. pizzas.csv	            Lists pizza sizes, types, and prices
4. pizza_types.csv      	Defines pizza categories and type names


**📘 SQL Workflow**
All SQL scripts are in the /sql folder:
- create_tables.sql → Creates database schema.
- import_data.sql → Imports CSV data into MySQL.
- queries.sql → Contains SQL for analysis (basic, intermediate, advanced).


**📊 Power BI Dashboard**
The Power BI file connects directly to the MySQL database to visualize:
- Sales revenue trends
- Top-performing pizza categories
- Size preferences
- Hourly order patterns
You can find connection and setup steps in /powerbi/README.md.


**🛠️ Tech Stack**
- Database: MySQL
- Visualization: Power BI
- Data Source: CSV (order, pizza, and sales data)
- Language: SQL

**📈 Key Insights**
- Identify best-selling pizza types and categories
- Understand customer ordering patterns by time
- Analyze revenue distribution across pizza sizes and categories
- Track cumulative revenue growth over time
