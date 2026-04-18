# E-Commerce Sales Insights Dashboard

## Overview
This project is an interactive Power BI dashboard developed to analyze e-commerce sales data and generate business insights related to sales performance, profitability, product contribution, and regional trends.

## Problem Statement
Large volumes of e-commerce data make manual analysis difficult. This project addresses that challenge by transforming raw sales data into interactive visualizations and actionable insights using Power BI.

## Features
- Total Sales, Profit, Orders, and Profit Margin KPIs
- Sales Trend Analysis
- Category-wise Sales Analysis
- Product Contribution Analysis
- Region-wise Sales Visualization
- Interactive Filters (Year, Category, Region)
- Data Cleaning using Power Query
- DAX Measures for analytical calculations

## Tech Stack
- Power BI Desktop  
- Power Query  
- DAX  
- CSV Dataset  

## Dashboard Visuals
- KPI Cards  
- Line Chart  
- Bar Chart  
- Donut Chart  
- Map Visual  
- Slicers  

## DAX Measures Used
```DAX
Total Sales = SUM(Sales)

Total Profit = SUM(Profit)

Total Orders = DISTINCTCOUNT(Order ID)

Profit Margin = DIVIDE([Total Profit],[Total Sales],0)
```

## Project Structure
```text
E-Commerce-Sales-Insights/
│
├── Dataset/
│   └── ecommerce_sales_dataset.csv
│
├── PowerBI_File/
│   └── Ecommerce_Sales_Insights.pbix
│
├── Documentation/
│   └── Project_Report.pdf
│
└── README.md
```

## Key Insights
- Sales trends vary across time periods
- Certain products contribute more revenue
- Regional sales performance differs
- Profitability varies across categories

## Future Improvements
- Sales Forecasting
- Real-Time Data Integration
- Customer Segmentation
- Advanced DAX Analytics

## Conclusion
This project demonstrates how Power BI can transform raw e-commerce data into meaningful business insights through interactive dashboards and data-driven analysis.
