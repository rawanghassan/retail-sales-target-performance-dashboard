# Retail Sales & Target Performance Dashboard using Power BI

## Project Overview

This project is an interactive Power BI dashboard designed to analyze retail sales performance, revenue trends, product categories, sales channels, marketing campaigns, and target achievement. The dashboard transforms raw retail data into clear business insights through KPI cards, interactive filters, charts, and target comparison analysis.

The report includes four main pages:

1. Executive Overview
2. Sales Trend Analysis
3. Channel & Category Analysis
4. Target Analysis

---

## Business Problem

Retail businesses need to monitor revenue, profitability, order performance, customer activity, product category performance, channel contribution, campaign effectiveness, and progress against revenue targets.

This dashboard helps answer key business questions such as:

- What is the total revenue and gross profit?
- Which product categories generate the highest revenue?
- Which sales channels contribute most to revenue?
- How do revenue and orders change over time?
- Which campaigns perform better?
- Is the business meeting its revenue targets?
- What is the gap between actual revenue and target revenue?

---

## Tools Used

- Power BI Desktop
- Microsoft Excel
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

## Dataset

Dataset name:

Retail Sales & Target Performance Dataset

Source file:

Retail_Sales_Target_Performance_Dataset.xlsx

The dataset contains retail business data related to sales transactions, products, customers, calendar dates, and monthly targets.

Main tables used in the Power BI model:

- Sales
- Products
- Customers
- Calendar
- Targets
- DimMonth
- Measures Table

---

## Data Model

The dashboard uses a structured data model with fact and dimension tables. The main fact table is the Sales table, connected to product, customer, and calendar dimensions.

Key relationships include:

- Products[ProductID] to Sales[ProductID]
- Customers[CustomerID] to Sales[CustomerID]
- Calendar[Date] to Sales[OrderDate]
- DimMonth[MonthStart] to Calendar[MonthStart]
- DimMonth[MonthStart] to Targets[MonthStart]

A dedicated Measures Table was created to organize all DAX measures used in the dashboard.

---

## Key DAX Measures

The following DAX measures were created for the dashboard:

- Total Revenue
- Total Cost
- Gross Profit
- Gross Margin %
- Total Orders
- Total Quantity
- Customer Count
- Average Order Value
- Revenue per Customer
- Target Revenue
- Target Orders
- Revenue Gap
- Target Achievement %

These measures support sales analysis, profitability tracking, order analysis, and target performance monitoring.

---

## Dashboard Pages

### 1. Executive Overview

The Executive Overview page provides a high-level summary of overall business performance.

Main visuals:

- Total Revenue KPI
- Gross Profit KPI
- Gross Margin % KPI
- Customer Count KPI
- Total Orders KPI
- Target Achievement % KPI
- Revenue by Category
- Revenue by Channel
- Year slicer

Purpose:

This page gives decision-makers a quick summary of sales performance, profitability, customer activity, and target achievement.

Suggested screenshot path:

screenshots/executive_overview.png

---

### 2. Sales Trend Analysis

The Sales Trend Analysis page focuses on time-based performance.

Main visuals:

- Total Revenue KPI
- Average Order Value KPI
- Total Orders KPI
- Monthly Revenue Trend
- Monthly Orders Trend
- Year slicer

Purpose:

This page helps analyze how revenue and orders change over time and identify monthly performance patterns.

Suggested screenshot path:

screenshots/sales_trend_analysis.png

---

### 3. Channel & Category Analysis

The Channel & Category Analysis page analyzes revenue by sales channel, product category, and campaign.

Main visuals:

- Revenue by Category
- Revenue by Channel
- Revenue by Campaign
- Year slicer
- Category slicer
- Channel slicer

Purpose:

This page helps identify the strongest revenue-generating categories, channels, and campaigns.

Suggested screenshot path:

screenshots/channel_category_analysis.png

---

### 4. Target Analysis

The Target Analysis page compares actual revenue against revenue targets.

Main visuals:

- Target Revenue KPI
- Total Revenue KPI
- Revenue Gap KPI
- Target Achievement % KPI
- Actual vs Target Revenue
- Target Achievement % by Month
- Year slicer

Purpose:

This page helps track whether actual sales performance is meeting planned revenue targets and highlights the gap between actual and target revenue.

Suggested screenshot path:

screenshots/target_analysis.png

---

## Key Insights

- Total revenue reached approximately $1.37M across the analyzed period.
- Gross profit reached approximately $611.52K.
- Gross margin was approximately 44.77%.
- The dashboard tracked around 3K total orders and 400 customers.
- Website and Mobile App were among the strongest sales channels by revenue contribution.
- Product categories such as Home Office, Sports, Electronics, Fashion, and Beauty were compared by revenue performance.
- Target achievement was approximately 19.94%, showing a significant gap between actual revenue and target revenue.
- Target analysis highlighted a revenue gap of approximately $5.48M.

---

## Project Files

Recommended repository structure:

```text
retail-sales-target-performance-dashboard/
│
├── README.md
├── Retail_Sales_Target_Performance_Dashboard.pbix
├── Retail_Sales_Target_Performance_Dashboard.pdf
├── Retail_PowerBI_Project_Documentation.pdf
├── Retail_Sales_Target_Performance_Dataset.xlsx
│
└── screenshots/
    ├── executive_overview.png
    ├── sales_trend_analysis.png
    ├── channel_category_analysis.png
    └── target_analysis.png
```

---

## How to Open the Project

1. Download the `.pbix` file from this repository.
2. Open it using Power BI Desktop.
3. If needed, update the data source path to the Excel dataset file.
4. Refresh the data model.
5. Explore the four dashboard pages using the slicers and visuals.

---

## Skills Demonstrated

- Power BI dashboard development
- Data modeling
- Relationship building
- DAX measure creation
- KPI design
- Sales analytics
- Revenue analysis
- Target performance analysis
- Time-series analysis
- Interactive report design
- Business intelligence storytelling

---

## Project Summary

This Power BI project demonstrates how retail business data can be transformed into a clear, interactive, and professional business intelligence dashboard. It combines data modeling, DAX calculations, KPI tracking, visual storytelling, and target analysis to support data-driven decision-making.

---

## Author

Rawan Abu Hattab

Data Analyst | Business Intelligence | Power BI | Excel | DAX

