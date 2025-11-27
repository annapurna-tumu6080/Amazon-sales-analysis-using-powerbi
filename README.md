# Amazon-sales-analysis-using-powerbi

**summary:**

I built an interactive Amazon Product Sales Analysis dashboard using Power BI, performing data cleaning, modeling, and creating DAX measures for KPIs.The report includes category-wise revenue, top products, monthly trends, and geographic insights to help understand sales performance and business growth.

📊 **Amazon Sales Analysis Dashboard**
1. Project Title :

🛒 Amazon Analytics: Product Sales Insights Dashboard
A dynamic and interactive Power BI dashboard designed to analyze Amazon product sales, uncover revenue patterns, identify top-performing categories, and track customer purchasing trends.

2. Short Description :

The Amazon Sales Analysis Dashboard provides a comprehensive view of sales performance by combining product, revenue, profit, and customer data. It helps businesses identify sales trends, evaluate product profitability, and make data-driven decisions for growth.

3. Tech Stack :

This dashboard was built using the following tools and technologies:

•Power BI Desktop – For dashboard creation and interactive visualizations

•Power Query – For data cleaning, transformation, and shaping

•DAX (Data Analysis Expressions) – For calculated measures, KPIs, and logic

•Data Modeling – Establishing relationships among Sales, Products, Category & Customers tables

•Excel / CSV Dataset – Source data used for building the report

4. Key Features

📌 KPI Cards: Total Sales, Total Profit, Units Sold, Average Rating

•📊 Category-wise Analysis: Revenue distribution across product categories

•🏆 Top-Selling Products: Best performers by revenue and quantity

•🌍 Geographical Insights: Customer location-based sales map

•📅 Monthly Trend Analysis: Seasonality and sales growth patterns

•🔍 Interactive Filters: Category, seller, location, date, product

5. DAX Measures Used

Examples of custom DAX measures implemented:

Total Sales = SUM('Amazon'[Total Revenue])

Total Profit = SUM('Amazon'[Profit])

Units Sold = SUM('Amazon'[Units Sold])

Average Rating = AVERAGE('Amazon'[Rating])

Sales Growth % =
VAR PrevMonth = CALCULATE([Total Sales], DATEADD('Date'[Date], -1, MONTH))
RETURN DIVIDE([Total Sales] - PrevMonth, PrevMonth)

6. Insights & Findings

  1.Electronics and Home Appliances contributed the highest revenue share

  2.Top 10 products accounted for more than 60% of total sales

  3.Major sales came from metro locations like Bangalore, Mumbai, and Delhi

  4.Sales peaked during the festive season months (Oct–Dec)

  5.High-profit margins observed in accessories and household categories

7. Files Included

  1.📁 Dataset (Excel/CSV)

  2.📊 Power BI Report (.pbix)

  3.📝 Documentation

8. How to Use

  1.Download the .pbix file

  2.Open it in Power BI Desktop

  3.Interact with the visuals to explore insights
