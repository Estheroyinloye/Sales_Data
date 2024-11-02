# Data Portfolio
## Project Title: Sales Analysis

### Overview
This project analyzes sales data from various stores across different regions and markets. The dataset includes key metrics such as revenue, units sold, fiscal period, and line of business, providing valuable insights into sales performance across multiple dimensions. The goal of the analysis is to uncover trends, identify areas of improvement, and provide actionable insights to enhance business operations.

### Project Objectives
The main objectives of this project are:  
- To understand the sales performance by analysing the revenue and units sold across various regions, markets, and stores.
- To Identify Top-Performing Stores and Markets by analysing which stores are the highest revenue generators.
- To To determine which business lines and sales models contribute most to overall revenue by analyzing the Line of Business and Sales Models.
- To Provide Data-Driven Recommendations based on the analysis.

### Data Source
The primary source of the data used for this project is ....

### Dataset Description
The Dataset consist of the following columns; 
- Region: Geographical area where the store operates.
- Market: Subdivision within the region to identify specific target markets.
- Store: Unique ilocation of each store
- Trade Date: Date when the transaction occurred.
- Fiscal Period: The accounting period in which the transaction was recorded.
- Line of Business: The unique organization sector that the or transaction falls under.
- Revenue: Total amount generated from sales.
- Units Sold: The number of units sold in each transaction.
- Transaction Category: Classification of the transaction based on the unit sold (Low, medium, high).

### Tools and Methods used
This analysis was done using microsoft excel.

#### Data Cleaning
- Used Excel functions such as IFS, TRIM, and DATE to clean and standardize the data.

#### Data Analysis
Used pivot tables to;
- Compare sales (revenue and units sold) across different regions and markets
- Rank stores by total revenue and units sold
- Identify trends and patterns in the fiscal periods
Used conditional formatting to highlight important trends and insights in the data (e.g., top 10 stores, low-performing markets).


#### Data Visualization
- Created Excel charts (bar charts, line charts, and pie charts) to visualize key metrics, such as revenue trends, top-performing stores, and market performance.


### Formulas used
``` excel
=IFS(J3<=20,"Low",J3<=50,"Medium",J3>=50,"High")
```
## Analysis
### Revenue by Region






# Project 2
## Project Title: Kikelomo Stores Sales Analysis 

### Introduction
This is a Microsoft Excel project on sales analysis of an imaginary store called **Kikelomo Stores**. 
The project is aimed at analysing and deriving insights to answer critical questions and help the store make data driven decusions.
**_Disclaimer_**: _All datasets and reports do not represent any company, institution or country but a dummy dataset to demonstrate the cabability of Microsoft  Excel._

### Problem Statement
Which region generates the highest sales ?
Which region generates the least sales ?
Which product has the highest total sales ?
What is the total sales trend year-on-year ?
What is the total sales trend quarter-on-quarter ?
Which product has the highest sales  year-on-year?
What are the top 3 products by total sales? 
What are the bottom 3 products by total sales?
Who are the top 10 customers?
Any other relevant insights.

### Excel Concept applied
Excel functions; IF, IFS, TRIM, X-LOOKUP, filters, Slicers.

### Data Source
The data was obtained from an open-source data site as a CSV file, after which it was cleaned, analysed, and visualized with Microsoft Excel.

### Data Transformation and cleaning
To clean the data, duplicates and blanks were removed from from the table.
 A new column was created for  **TotalSales** using the formula 
``` excel
 UnitPrice * Quantity
```
### Data Analysis and Visualization
The report comprises of 



![]()








