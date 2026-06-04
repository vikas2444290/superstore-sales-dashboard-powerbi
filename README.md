# 📊 Super Store Sales Dashboard | Power BI

## Overview

This project is an interactive Power BI dashboard built using the Super Store dataset to analyze sales performance, profit trends, customer segments, shipping modes, and regional performance.

The dashboard provides business insights through interactive visualizations and includes a 15-day sales forecasting model for future trend analysis.

---

## Business Problem

Retail businesses generate large amounts of transactional data but often struggle to answer questions such as:

- Which region generates the highest sales?
- Which product categories are most profitable?
- How do customer segments contribute to revenue?
- Which shipping modes are most frequently used?
- What are the expected sales trends in the near future?

This dashboard helps transform raw sales data into actionable insights for better business decision-making.

---

## Tools & Technologies Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Time Series Forecasting

---

## Key Metrics Tracked

- Total Sales
- Total Profit
- Total Quantity Sold
- Number of Orders
- Sales by Region
- Sales by Category
- Sales by Sub-Category
- Sales by Customer Segment
- Sales by Payment Mode
- Sales by Shipping Mode
- State-wise Sales Distribution

---

# Dashboard Preview

## Main Dashboard

![Main Dashboard](Dashboard%20Screenshots/Dashboard.png)

---

## Regional Analysis

### Central Region

![Central Region](Dashboard%20Screenshots/Central.png)

#### Insights
- Total Sales: 341K
- Consumer segment contributes the highest sales.
- Office Supplies category leads revenue generation.

---

### East Region

![East Region](Dashboard%20Screenshots/East.png)

#### Insights
- Total Sales: 450K
- Strong performance across Office Supplies and Technology categories.
- High concentration of sales in major eastern states.

---

### South Region

![South Region](Dashboard%20Screenshots/South.png)

#### Insights
- Total Sales: 252K
- Consumer segment contributes over half of total sales.
- Phones are the highest-performing sub-category.

---

### West Region

![West Region](Dashboard%20Screenshots/West.png)

#### Insights
- Total Sales: 522K
- Highest-performing region overall.
- Strong contribution from Technology and Office Supplies categories.

---

## Sales Forecast Dashboard

![Sales Forecast](Dashboard%20Screenshots/Sales%20Forecast.png)

### Forecast Features

- Historical sales trend visualization
- 15-Day Sales Forecast
- Forecast confidence interval
- Future sales estimation based on historical data

---

## Dashboard Features

✅ Interactive Region Filtering

✅ Dynamic KPI Cards

✅ Sales Trend Analysis

✅ Profit Trend Analysis

✅ Category & Sub-Category Analysis

✅ Customer Segment Analysis

✅ Payment Mode Analysis

✅ Shipping Mode Analysis

✅ Geographic Sales Visualization

✅ Sales Forecasting

---

## DAX Measures Used

Examples of measures used in this project:

```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Quantity = SUM(Orders[Quantity])

Total Orders = DISTINCTCOUNT(Orders[Order ID])
```

---

## Project Structure

```text
├── Dashboard Screenshots
│   ├── Central.png
│   ├── Dashboard.png
│   ├── East.png
│   ├── Sales Forecast.png
│   ├── South.png
│   └── West.png
│
├── Dataset
│
├── LICENSE
├── README.md
└── SuperStore_Sales_Dashboard.pbix
```

---

## What I Learned

Through this project, I gained hands-on experience with:

- Data Cleaning using Power Query
- Creating Data Models in Power BI
- Writing DAX Measures
- Designing Interactive Dashboards
- Business-Oriented Data Analysis
- Forecasting Techniques in Power BI
- Storytelling with Data

---

## Future Improvements

- Add Profit Margin Analysis
- Add Customer Retention Metrics
- Add Drill-Through Pages
- Publish Dashboard to Power BI Service
- Connect Dashboard to Live Data Sources

---

## Author

### Vikas Yadav

BS Degree in Data Science and Applications

Indian Institute of Technology Madras

LinkedIn: https://www.linkedin.com/in/data-scientist-vikas/
