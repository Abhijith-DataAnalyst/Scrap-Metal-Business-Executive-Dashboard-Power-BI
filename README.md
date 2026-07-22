# Scrap-Metal-Business-Executive-Dashboard-Power-BI
This project is an interactive Power BI Executive Dashboard developed for a Scrap Metal Recycling business to monitor and analyze key business metrics across Sales, Purchases, Inventory, Expenses, Profitability, Customers, and Suppliers.


📊 Scrap Metal Business Executive Dashboard | Power BI
📌 Project Overview

This project is an interactive Power BI Executive Dashboard developed for a Scrap Metal Recycling business to monitor and analyze key business metrics across Sales, Purchases, Inventory, Expenses, Profitability, Customers, and Suppliers.

The dashboard enables business users to track operational performance, compare Year-over-Year (YoY) results, and make informed decisions using interactive visualizations.

🎯 Business Objectives
Monitor overall business performance
Compare current year with previous year
Analyze monthly sales and purchase trends
Track inventory movement and stock utilization
Monitor expenses by category
Identify top customers and suppliers
Analyze payment status and pending collections
Enable interactive customer-level analysis using Drill-through
📊 Dashboard Preview

<img width="1061" height="731" alt="image" src="https://github.com/user-attachments/assets/275e985b-5de4-4cd2-81a3-ebb8bc7b750d" />


images/
│
├── Executive_Dashboard.png
├── Customer_Details.png
📈 Executive KPIs
KPI	Description
Total Sales	Total revenue generated
Total Purchase	Total purchase value
Net Profit	Sales − Purchase − Expenses
Profit Margin %	Net Profit ÷ Total Sales
Closing Stock	Current inventory available
Total Expenses	Overall operating expenses
Pending Amount	Outstanding customer payments
Customer Count	Total active customers
Supplier Count	Total suppliers

Each KPI includes:

Current Year Value
Previous Year Comparison
Growth Percentage
Conditional Formatting
📊 Dashboard Features
Executive Dashboard
KPI Cards
Dynamic Year-over-Year Comparison
Monthly Sales Trend
Monthly Net Profit Trend
Purchase vs Sales Comparison
Sales by Material
Purchase by Material
Payment Status Analysis
Top Customers
Top Suppliers
Expenses by Category
Inventory Summary
Stock Utilization Gauge
Interactive Features
Year Slicer
Quarter Slicer
Month Slicer
Material Slicer
Supplier Slicer
Customer Slicer
Payment Status Slicer
Report Page Tooltips
Customer Drill-through
Dynamic Last Refresh
Cross-filtering between visuals
🗂 Data Model

The project follows a Star Schema.

                Calendar
                   |
      --------------------------
      |          |            |
    Sales    Purchases    Expenses
      |
   Material
      |
  Inventory

Dimension Tables

Calendar
Material

Fact Tables

Sales
Purchases
Expenses
Inventory
📐 DAX Measures Used
Sales
Total Sales
Previous Year Sales
Sales Growth %
Sales Growth Text
Previous Year Sales Text
Purchase
Total Purchase
Previous Year Purchase
Purchase Growth %
Profit
Gross Profit
Net Profit
Profit Margin %
Previous Year Profit Margin
Inventory
Closing Stock
Previous Year Closing Stock
Stock Utilization %
Expenses
Total Expenses
Previous Year Expenses
Customers
Customer Count
Suppliers
Supplier Count
📈 Business Insights
Sales and Purchase performance can be compared month-over-month and year-over-year.
Profitability is monitored through Net Profit and Profit Margin KPIs.
Inventory movement is tracked using Opening Stock, Purchased, Sold, and Closing Stock.
Payment Status visualization helps identify pending collections.
Top Customers and Suppliers are highlighted for business decision-making.
Expense analysis identifies major operational cost categories.
🛠 Tools & Technologies
Microsoft Power BI
Power Query
DAX
Microsoft Excel
Data Modeling
Star Schema
Interactive Dashboards
📁 Dataset

The project contains multiple datasets:

Sales
Purchases
Inventory
Expenses
Calendar Table
Material Dimension
🎨 Dashboard Highlights
Executive Dashboard Design
Professional KPI Cards
Responsive Layout
Interactive Slicers
Drill-through Navigation
Report Page Tooltips
Conditional Formatting
Dynamic Year-over-Year Analysis
Last Refresh Indicator
📸 Screenshots
Executive Dashboard

<img width="1061" height="731" alt="image" src="https://github.com/user-attachments/assets/4b613c07-ad93-46ac-bd6d-1be4490b6bb9" />


Customer Drill-through

<img width="995" height="730" alt="image" src="https://github.com/user-attachments/assets/fbc75a38-2121-44c0-b4ff-0e18c3fe167f" />


🚀 Future Improvements
Sales Forecasting
Inventory Forecasting
Supplier Performance Scorecard
Customer Segmentation
Profit Forecast Dashboard
Mobile Layout Optimization
👨‍💻 Author

Abhijith
