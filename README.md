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
Used Excel functions such as IF, TRIM, and DATEVALUE to clean the data.

#### Data Analysis
Used pivot tables to;
Compare sales (revenue and units sold) across different regions and markets
Rank stores by total revenue and units sold
Identifying trends and patterns in the fiscal periods

#### Data Visualization
Created Excel charts (bar charts, line charts, and pie charts) to visualize key metrics, such as revenue trends, top-performing stores, and market performance.
Used conditional formatting to highlight important trends and insights in the data (e.g., top 10 stores, low-performing markets).

### Formulas used
``` excel
=IFS(J3<=20,"Low",J3<=50,"Medium",J3>=50,"High")
```
## Analysis
### Revenue by Region






# Project 2
## Project Title: Sales Analysis Report

### Project Overview
This project investigates product sales across different regions over two years (2023 and 2024), focusing on regional preferences, product popularity, and quarterly and monthly sales patterns. The objective is to provide data-driven insights for improving sales strategy and resource allocation.

### Project Objectives
- Identify which products and regions generate the most sales.
- Analyze seasonal product demand and quarterly trends.
- Examine year-over-year changes in sales across regions and products.
- Offer recommendations for inventory and marketing based on insights.

### Data Collected
The dataset includes:
- Product Types: Hats, Gloves, Jackets, Shirts, Socks, and Shoes.
- Regions: East, North, South, and West.
- Sales Volumes: Total product counts and total sales figures by region, year, and quarter.
- Time Periods: Annual, quarterly, and monthly data for 2023 and 2024.

### Tools used
- Excel for data cleaning, analysis and visualization

### Insights

#### Insight 1: Product Count by Region
Each region recorded a total product count of 12,500 units.
- Hats: East region sold the most hats, while South sold none. North and West sold half the volume of East.
- Gloves: South region had the highest glove sales, while West sold half of South's volume. East and North had no glove sales.
- Jackets: Only East and North sold jackets, with North having double the sales of East.
- Shirts: Only East and North sold shirts, with North recording double the sales of East.
- Socks: Sold exclusively in West and South, with West doubling South's sales.
  
Summary: Each region stocked an equal total of 12,500 products, but specific product sales varied greatly by region. For instance, hats sold highest in the East, while gloves dominated in the South. North and East took the lead in jacket sales, while socks and shirts saw strong regional preferences, with the West leading in sock sales and North excelling in shirt sales. These distinctions suggest each region has unique customer preferences that we could further leverage in our regional marketing strategies.

#### Insight 2: Total Sales by Region
West region leads in total sales with 4.68 million (39% of total), followed by:
- East: 2.45 million (20%)
- South: 1.95 million (17%)
- North: 1.51 million (24%)
  
Summary: The West region significantly outperformed others in total sales, reaching $4.68 million, followed by the East at $2.45 million, the South at $1.95 million, and North trailing with $1.51 million. This suggests that the West region could serve as a benchmark for success strategies, while North may need targeted campaigns to improve performance.

#### Insight 3: Regional Sales by Year
- 2023: South recorded the highest sales while West had the lowest. North's sales were also low, similar to West.
- 2024: South continued to lead, followed by East, with West again showing the lowest sales. North’s performance was slightly above West’s.
Year-over-Year Trend: There is a general reduction in sales across all regions except North and West.

Summary: In 2023, the South region led in sales, with West showing the least sales. North had lower sales levels similar to the West, while East closely mirrored South's performance. In 2024, sales dropped in all regions except North and West, indicating potential economic or consumer preference shifts. These findings could guide us to revisit strategies for each region based on shifting demand.

#### Insight 4: Product Sales by Year
- 2023: Shirts were the highest-selling product, while hats had the lowest sales.
- 2024: There was an increase in hat and shoe sales, while jackets and socks saw significant declines. Gloves maintained similar sales levels across both years.
  
Summary: In 2023, shirts had the highest sales among products, while hats struggled to gain traction. By 2024, we observed dips in jacket and sock sales, while hats and shoes saw an increase. Gloves maintained consistent sales across both years. This points to changing product popularity, highlighting a possible need to adjust our inventory or focus on seasonal trends in product demand.

#### Insight 5: Quarterly Sales by Product

#### 2023:
- Q1: Socks and shoes had the highest sales, while gloves had the least.
- Q2: Increased sales in most products except socks and shoes, which saw a decline.
- Q3: Increased sales for socks, shoes, and shirts; decreased sales for jackets, hats, and gloves.
- Q4: Decline in shoes and shirts, slight increase in hats and gloves, with jackets seeing a strong upward trend.
  
#### 2024:
- Q1: Socks, shoes, and shirts continued to have high sales, outperforming jackets, hats, and gloves.
- Q2: Decline in sales for socks, shoes, and shirts, with an increase in gloves, hats, and jackets.
- Q3: Minor increases in hats and shoes, slight declines in socks and shirts, with gloves experiencing a significant drop.
- Q4: Slight increase in jackets and stable sales for gloves; other products remained steady.

Summary: Quarterly performance showed significant seasonal shifts. In 2023, Q1 was strong for socks and shoes, with gloves lagging. Q3 was particularly favorable for socks, shoes, and shirts, while jackets performed best in Q4. The 2024 trends were similar but with some weaknesses, especially in Q3 for gloves. Understanding these quarterly patterns can inform our seasonal promotions, inventory planning, and product launches.

#### Insight 6: Monthly Sales by Year
#### 2023: February had the highest sales, while April had the lowest.
Sales steadily increased from May to July, followed by a dip in August and moderate increases in September and October before declining again in November and December.
#### 2024: February was again the peak sales month, while July saw the lowest sales.
Sales declined from March to May, rose in June, dipped in July, and then increased through August. Another gradual increase occurred from September to October, followed by a steady decline in the last two months.

Summary: Monthly sales trends indicate February as the peak sales month in both years, with April and July showing consistent dips. In 2024, we observed a steady decline from March to May, followed by a brief recovery in June and another drop in July. These cyclical patterns suggest the need to plan promotional activities and inventory around predictable high and low months.

#### Insight 7: Quarterly Sales Breakdown by Year
- 2024 Q1 sales were higher than 2023 Q1.
- Both years experienced a decline in Q2, though the drop in 2023 was sharper.
- In Q3, 2023 sales rebounded, whereas 2024 saw a continued decline.
- Both years showed a slight decrease in Q4, but 2023 had a more stable performance than 2024.

Summary: Comparing 2023 and 2024 quarterly trends, Q1 sales were higher in 2024, though both years experienced significant drops in Q2—more severe in 2023. While 2023 saw a rebound in Q3, 2024 continued to decline, emphasizing a divergence in mid-year performance. This year-over-year breakdown highlights possible seasonal adjustments in consumer behaviour, prompting a closer look at why Q3 and Q4 performance weakened in 2024.







