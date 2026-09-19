# Mobile Sales Dashboard - Power BI

## Overview
This project analyzes mobile phone sales data (sourced from Kaggle) using Power BI. It covers revenue trends by brand, location, and time, customer age patterns, and payment method distribution.

## Data
- Source: Kaggle (mobile phone sales dataset)
- Fields: TransactionID, Date, Brand, Mobile Model, Price, Units Sold, Total Revenue, Customer Age, Customer Gender, Location, Payment Method
- Cleaned using Power Query: fixed data types, removed duplicates, handled nulls, trimmed text, validated revenue logic, checked outliers


### Page 1 - Overview

- KPI Cards: Total Revenue, Units Sold, Transactions, Average Price
- Gauge: Average Order Value vs Target
- Combo Chart: Top Brands by Revenue with Average Customer Age
- Waterfall: Revenue by Year/Quarter/Date
- Donut Chart: Payment Method Breakdown

### Page 2 - Detail

- Treemap: Revenue by Location
- Full Transaction Table
- Mobile Model Slicer (applies to both pages)

## Files
- Dashboard.pbix — full Power BI report file
- Dashboard.pdf — exported report (view without Power BI installed)

## Tools Used
Power BI Desktop, Power Query (M)
