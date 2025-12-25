## 📂 Repository Overview 

This repository contains all files related to the Excel-based retail sales analysis project: - `raw_data/`: Original dataset used for analysis - `cleaned_data/`: Preprocessed version of the dataset - `analysis_visualizations/`: Pivot tables, charts, and summary tables - `sales_dashboard.xlsx`: Interactive dashboard with filters and KPIs - `README.md`: Full project documentation


# 📌 Overview:
This project analyzes a multi‑region retail dataset to evaluate sales performance, identify top‑selling products, and uncover trends across customer segments, product categories, and time periods. The analysis was completed entirely in Excel, using pivot tables, charts, formulas, and an interactive dashboard to support data‑driven insights.

The goal of this project is to demonstrate practical data analysis skills using Excel — including data cleaning, trend analysis, dashboard design, and business insight generation.

# 📁 Dataset Summary
The raw dataset contains ~9,800 rows of retail sales data spanning 2015 to 2018, with the following fields:

- Row ID - Unique row identifier

- Order ID	- Unique order identifier

- Order Date	- Date the order was placed

- Ship Date	- Date the order was shipped

- Ship Mode - Shipping method used

- Customer ID	- Unique customer identifier

- Customer Name	- Name of the customer

- Segment	- Customer segment (Consumer, Corporate, Home Office)

- Country	- Country of the customer (likely all U.S.)

- City	- City of the customer

- State	- State of the customer

- Postal Code	- ZIP code

- Region - U.S. region (East, West, Central, South)

- Product ID	- Unique product identifier

- Category - Product category (Furniture, Office Supplies, Technology)

- Sub‑Category - Product sub‑category

- Product Name - Name of the product

- Sales	- Total sales



# 🎯 Objectives
This project focuses on answering key business questions:

- Which regions generate the highest sales and profit

- What are the top 5 products by revenue

- How sales and profit vary across categories and subcategories

- How performance changes month‑to‑month and year‑to‑year

- Which customer segments contribute most to revenue

- How shipping mode and geography influence sales patterns

- How sales differ across U.S. states



# 🧠 Interactive Dashboard Features
The Excel dashboard is fully interactive and allows users to explore sales performance dynamically.

🎛️ Filters
State selector (e.g., OH)

Year slicers (2015–2018)

Region, Category, Sub‑Category, Segment filters

# 📊 Quick Summary Panel
Number of Transactions

Total Sales

Average Sale Value

Region of selected state

# 🥧 Total Sales by Region
Interactive pie chart showing regional sales distribution

Example: East (33%), West (29%), South (19%), Central (19%)

# 🧑‍💼 Sales by Segment and Region
Bar chart comparing Consumer, Corporate, and Home Office sales

Highlights segment‑specific performance in each region

# 🛍️ Top 5 Products by Region
Bar chart showing top‑selling products

Example:

Canon ImageCLASS 2200 Copier (~$30,000 in East)

HON 4‑Drawer Vertical File (~$20,000)

# 📈 Monthly Sales Trends
Line chart visualizing monthly sales across regions

Shows seasonal patterns and regional fluctuations




# 🔍 Process
- 1. Data Cleaning
Removed duplicates

Standardized date formats

Extracted Month and Year from Order Date

Converted numeric fields to proper data types

Validated category and sub‑category labels

Created structured tables for pivot analysis

- 2. Exploratory Analysis
Built pivot tables for region, category, and segment

Created time‑series charts for monthly and yearly trends

Ranked products by revenue and quantity

- 3. Dashboard Creation
Designed an interactive dashboard with slicers

Added KPIs (Total Sales, Total Profit, Avg Order Value)

Used conditional formatting to highlight performance

Built charts for regional, product, and trend analysis


# 🚀 How to Use
- Download the Excel dashboard file

- Open in Excel (desktop recommended)

- Use slicers to filter by region, category, segment, or time period

- Explore pivot tables for deeper analysis


# 📌 Future Improvements
- Add forecasting using Excel’s built‑in forecasting tools

- Incorporate customer lifetime value (CLV) analysis

- Build a Power BI version of the dashboard

- Add more advanced KPIs (e.g., YoY growth, profit margin trends)
