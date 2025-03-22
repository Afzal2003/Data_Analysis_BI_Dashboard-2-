# 🍽️ Food and Beverages Sales Analysis | Power BI Dashboard

## 📌 Project Overview

This project analyzes sales performance in the food and beverage industry using Power BI. The dashboard provides insights into total revenue, product category sales, sales channels, and team performance, helping businesses make data-driven decisions.

📊 Tools Used: Power BI

📂 Data Source: Sales & Product Data (Power BI Dataset)

🎯 Goal: Identify sales trends, revenue drivers, and performance by category, channel, and salesperson.

## 📈 KPIs & Metrics Used

✔ Total Revenue – Overall sales performance

✔ Total Quantity Sold – Measure of product demand

✔ Total Orders – Number of orders placed

✔ Revenue by Year & Channel – Performance across online, retail, and distributor sales

✔ Top Salespersons & Managers – Identifying key contributors

✔ Product Category Insights – Food vs. Drink performance

## ⚡ Steps to Create the Power BI Dashboard

### Step 1: Data Collection & Preparation

1️⃣ Import the Sales & Product data (Excel/CSV) into Power BI.

2️⃣ Clean the data using Power Query – remove duplicates, handle missing values, and format columns.

3️⃣ Create relationships between Sales and Product datasets.

### Step 2: Data Modeling & DAX Measures

4️⃣ Define key metrics using DAX (Data Analysis Expressions), such as:

Total Revenue = SUM(Sales[Revenue])

Total Orders = DISTINCTCOUNT(Sales[Order ID])

Revenue per Category = CALCULATE(SUM(Sales[Revenue]), FILTER(Product[Category] = "Food"))

5️⃣ Create calculated columns for Year, Month, and Sales Channels.

### Step 3: Dashboard Visualization

6️⃣ Add KPI cards to display Total Revenue, Orders, and Quantity Sold.

7️⃣ Use Bar Charts for Yearly Sales & Top Salespersons.

8️⃣ Use Pie Charts for Product Category Contribution.

9️⃣ Use a Treemap to analyze Revenue by Supervisor.

🔟 Add Filters & Slicers for interactive analysis (Year, Category, Salesperson).

### Step 4: Finalizing & Publishing

🔹 Format the dashboard with colors, labels, and tooltips.

🔹 Add company branding & themes for a professional look.

🔹 Publish the report to Power BI Service and share insights.

## 📊 Dashboard Design & Features
### The dashboard is built with a clean and interactive layout, including:

🔹 Revenue Breakdown: Year-wise & channel-wise revenue trends

🔹 Sales Team Performance: Sales by supervisors, managers & salespersons

🔹 Category Analysis: Food vs. Drink sales insights

🔹 Order & Quantity Metrics: Understanding total sales volume

🔹 Geographical & Managerial Performance: Contribution analysis


## 📊 Insights & Findings

🔍 Revenue Trends: Sales peaked in 2020 with $10.2M revenue, but a decline was observed in 2021.

🔍 Top Contributors: Diego Araujo & Diego Carvalho led the revenue generation.

🔍 Channel Performance: Distributors drove the highest sales, followed by online and retail channels.

🔍 Category Insights: 91.1% of sales came from Food products, while Drinks contributed 8.9%.

🔍 Salesperson Performance: Carla Ferreira was the top-performing salesperson with $4.7M revenue.

## ✅ Conclusion
This Power BI dashboard provides deep insights into sales performance for the food & beverage industry. It helps businesses track revenue trends, product performance, and sales efficiency. Future improvements can include customer segmentation, seasonal trend analysis, and predictive modeling for better decision-making.
