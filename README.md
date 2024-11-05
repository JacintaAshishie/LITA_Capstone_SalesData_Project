# Sales_Performance_Analysis

## Project Overview
This project aims to analyze sales data to identify trends, patterns, and insights for business decision-making. The project focuses on data cleaning, analysis, and visualization to extract valuable insights from the data set used. The primary goal is to provide actionable recommendations based on data-driving findings.: In this project, you are tasked with analyzing the sales performance of a retail store. You will need to explore sales data to uncover key insights such as top-selling products, regional performance, and monthly sales trends. The goal is to produce an interactive Power BI dashboard that highlights these findings.


### Data Sources
The primary Data used here is SalesData.xslx. This data provide the LITA at IncubatorHub and was made available for download from CANVAS. Other Similar datasets can be freely downloaded from an open source oinline such as Kaggle or FRED or any other repository sites. 

### Tools Used
- Microsoft Excel 
  1. For data cleaning,
  2. For Analysis
  3. For Visualization

- SQL -Structured Query Language for Quering of Data
- Power BI for data visualization

   ## Methodology:
1. Data Cleaning
2. Data Analysis (SQL queries)
3. Data Visualization (Power BI)
4. Findings and Recommendations.

In the initial stage of the data cleaning and preparations, we performed the following actions;
- Data loading and inspection
- Handling missing values
- Removing duplicates
- Data Sorting
- Data normalization
- Data transformation

  ## Exploratory Data Analysis (EDA)
  ```
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


## Findings and Recommendations
- Key findings
- Recommendations

## License
This project is licensed under the MIT License.


  





