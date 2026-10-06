# Practical - 10 (Mini Project)

# Retail Sales Analytics

##  Project Overview

This project demonstrates an end-to-end data engineering and business intelligence solution using retail sales data.

The project covers the complete pipeline from raw data ingestion and data quality assessment to data cleaning, transformation, data warehouse design, validation, and business intelligence reporting using Microsoft Power BI.

The final output is an interactive **Retail Sales Analytics** dashboard that provides insights into sales, profit, customers, products, categories, and regional performance.



##  Objectives

- Ingest raw retail sales data
- Perform data profiling and quality assessment
- Identify and handle missing values and duplicate records
- Clean and standardize the dataset
- Perform data transformation using Python and Pandas
- Design a dimensional data warehouse using a Star Schema
- Create fact and dimension tables
- Validate the processed data
- Export warehouse tables
- Build an interactive Power BI dashboard


##  Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing and ETL |
| Pandas | Data cleaning and transformation |
| NumPy | Numerical calculations |
| Google Colab | Development environment |
| CSV | Data storage and exchange |
| Power BI | Data modeling and visualization |
| DAX | KPI and business calculations |
| GitHub | Project documentation and version control |



##  End-to-End Data Pipeline

```text
Raw CSV Dataset
      ↓
Data Ingestion
      ↓
Data Profiling & Quality Assessment
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Star Schema Data Warehouse
      ↓
Data Validation
      ↓
Warehouse Table Export
      ↓
Power BI Data Model
      ↓
DAX Measures
      ↓
Retail Sales Analytics Dashboard

```

## Power BI Dashboard

The final Power BI dashboard, **Retail Sales Analytics**, provides an interactive view of the processed retail sales data.

### Dashboard Components

The dashboard includes:

- **Total Sales** – Overall revenue generated from sales
- **Total Profit** – Overall profit generated
- **Total Orders** – Number of unique orders
- **Total Customers** – Number of unique customers
- **Monthly Sales & Profit Trend** – Tracks sales and profit over time
- **Sales by Region** – Compares sales performance across regions
- **Sales by Category** – Shows the contribution of each product category to total sales
- **Profit by Category** – Compares profitability across categories
- **Top 10 Products by Sales** – Identifies the highest-performing products
- **Interactive Slicers** – Allows users to filter the dashboard by Year, Region, and Category



##  Business Insights

The dashboard was designed to help answer important business questions such as:

- What is the overall sales and profit performance?
- How do sales change over time?
- Which regions generate the highest sales?
- Which product categories contribute the most to sales?
- Which categories generate the highest profit?
- Which products are the top contributors to sales?
- How does performance change when filtering by year, region, or category?

### Key Results

Based on the processed dataset:

| Metric | Result |
|---|---:|
| Total Sales | ₹82.48M |
| Total Profit | ₹21.84M |
| Total Orders | 2,500 |
| Total Customers | 20 |
| Total Quantity Sold | 7,449 |

These results are presented through interactive Power BI visuals to support easier analysis and business decision-making.

##  Dashboard Preview

![Retail Sales Analytics Dashboard](Dashboard%20image/Dashboard.png)

## Conclusion

This project demonstrates an end-to-end data engineering and business intelligence workflow using retail sales data. The raw data was ingested, profiled, cleaned, transformed, validated, and organized into a Star Schema data warehouse.

The processed data was then used to build an interactive Power BI dashboard for analyzing sales, profit, customers, products, categories, and regional performance.

Overall, the project demonstrates how raw business data can be transformed into a structured and meaningful solution that supports data analysis and business decision-making.
