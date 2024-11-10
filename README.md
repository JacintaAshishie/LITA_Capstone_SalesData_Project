# Sales_Performance_Analysis

## Table Outline
- [Project Overview](#project-overview)
- [Project Scope](#project-scope)
- [Key Performance Indicators](#key-performanceindicators)
## Project Overview
This project aims at conducting a comprehensive analysis of a retail store sales data from 2023 to 2024 to assess product performance and identify top-selling items, compare monthly sales trends across regions, and uncover customer preferences and regional patterns. This analysis provides actionable insights to inform data-driving decisions, optimize product offerings, and enhance customer retention strategies. In doing this, we will be focusing on data cleaning, analysis and visualization using Excel, SQL, and Power BI respectively.

## Project Scope:

- Explore sales data for key insights
- Identify top-selling products and regional performance
- Analyze monthly sales trends
- Develop an interactive Power BI dashboard

## Key Performance Indicators (KPIs):

- Total Sales
- Sales Growth Rate
- Top-Selling Products
- Regional Sales Performance
- Monthly Sales Trends



### Data Sources

The primary data used in this analysis is the SalesData.xlsx file, kindly provided by LITA the IncubatorHub and made available for download on CANVAS.
Alternative Data Sources

For those interested in exploring similar datasets, freely available options can be downloaded from open-source online repositories, including:

- Kaggle ((https://www.kaggle.com/code))
- FRED (Federal Reserve Economic Data, (https://fred.stlouisfed.org/))
- Other reputable data repository sites

### Tools Used
- Microsoft Excel for data cleaninng, analysis and visualization
- SQL -Structured Query Language for Quering of Data
- Power BI for data visualization
- GitHub for portfolio management

  ## Dataset Column Headers and Definitions
Here's a sample outline of terminology and definitions for key column headers specific to the retail sales dataset:

1. Sales Data

    - Date: Date of sale (YYYY-MM-DD)
    - Region: Geographic region where sale occurred (e.g., North, South, East, West)
    - Store ID: Unique identifier for each store
    - Product ID: Unique identifier for each product

2. Product Information

    - Product Name: Name of product sold
    - Category: Product category (e.g., Electronics, Clothing, Home Goods)
    - Subcategory: Product subcategory (e.g., Smartphones, Laptops, TVs)

3. Sales Metrics

    - Sales Amount: Total sales amount for each transaction
    - Quantity Sold: Number of units sold
    - Revenue: Total revenue generated from sales

4. Customer Information

    - Customer ID: Unique identifier for each customer
    - Customer Type: Type of customer (e.g., Individual, Business)

5. Additional Metadata

    - Seasonality: Indicator for seasonal fluctuations (e.g., Holiday, Summer, Back-to-School)
    - Promotion: Indicator for promotional activities (e.g., Discount, Bundle Deal)

Key Terms and Definitions

- Top-selling product: Product with highest sales amount or quantity sold.
- Regional sales performance: Comparison of sales across different regions.
- Product category analysis: Examination of sales trends within specific product categories.

   ## Methodology:
1. Data Cleaning
2. Data Analysis (SQL queries)
3. Data Visualization (Power BI)
4. Findings and Recommendations.
5. 
## Sata Cleaning and Preparations 
In the initial stage of the data cleaning and preparations, we performed the following actions;
- Data loading and inspection
- Handling missing values
- Removing duplicates
- Data Sorting
- Data normalization
- Data transformation

  ## Exploratory Data Analysis (EDA)

  EDA involved the exploring of the data to answer queestions about the data such as;
  
- What is the Total sales Per product?
- Total Sales by region ?
- Total sales per Month?
- Average sales per product?
- Total revenue by region?
- What is the total sales for each product category?
- What is the number of sales transactions in each region?
- What is the highest-selling product by total sales value?
-The total revenue per product?
- What is the monthly sales totals for the current year?
- Find the top 5 customers by total purchase amount.
- What is the percentage of total sales contributed by each region?
- Identify products with no sales in the last quarter?


## Data Analysis
```
This is where we include some basic lines of code or queries or even some of the Excel functions and we use Pivot tables to generate some sales reports;
- Excel;
   AVERAGEIF(C:C,C:C,H:H)
   =SUMIF(C:C,C:C,H:H)---SUMIF(range, criteria, [sum_range])
  
  ```SQL
  SELECT
   Region,
   COUNT(CustomerID) AS TotalCustomers
   FROM Capstone_SalesData
   GROUP BY Region
```

## Outcomes:

- Actionable recommendations for business growth
- Improved sales forecasting
- Enhanced product portfolio management
- Data-driven decision-making


### Data Vsualization
((https://github.com/JacintaAshishie/LITA_Capstone_SalesData_Project/blob/main/LITA_CAPSTONE_SALESDASHBOARD.png))
  
((https://github.com/JacintaAshishie/LITA_Capstone_SalesData_Project/blob/main/LITA_CAPSTONE_SALESDASHBOARD%202.png))




