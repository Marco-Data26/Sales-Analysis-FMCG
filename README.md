# Sales-Analysis-Dashboard

![gif](Chocolate_Sales.gif)
![gif](Chocolate_Profit.gif)

## Description

This project features two interactive Power BI dashboards for a chocolate company, built using Power Query and DAX.

The first dashboard focuses on sales performance, breaking down revenue by category, store type, region, and time.

The second dashboard analyzes profit performance over time, showing the relationship between profit and cost across categories and regions, as well as the relationship between profit, discount, and quantity. 

## Data & Tools Used

**Data** -  Sales Data containing over 1,000,000 records across 2023 and 2024.

**Data Cleaning & Analysis** - Power Query & DAX

**Data Visualization** - Power BI ([Chocolate.pbix](Chocolate.pbix))

## Objective

Provide a clear, data-driven view of the company's sales and profit performance.

It aims to help stakeholders identify top-performing products, analyze profitability by region and category, and support strategic decisions to optimize revenue and margins. 

## Dashboard Features

- Interactive filters by year, gender, age group, loyalty membership, store type, and brand.
- Drill-down analysis across time periods, brands, categories, and products.
- Scatter chart to analyze the relationship between profit and discount, with quantity represented by point size.
- Map visualization showing revenue distribution by city.

## Data Model 

- Fact Table: Sales.
- Dimension Tables: Products, Customers, Stores, and Date.
- Relationships built using customer_id, product_id, store_id, and order_date.  

## Key Insights

- The total revenue over 2023 and 2024 was $25.5M, with a profit $10.2M. Both years achieved the same quantity and order numbers: 1.5M units and 500k orders in each year. the difference was in revenue: in 2023, revenue was $12.7M, while in 2024, revenue was $12.8M. However, the profit remained equal at $5.1M for both years.
- The top product by revenue is the Dark Chocolate 50%, generating $1.8M, afterthat, Truffle Chocolate 80% achieved $1.6M, followed by Milk Chocolate 70%, with $1.4M.
- The Airport store is the highest in revenue, contributing about 30% ($7.6M), while the retail store had the lowest share at 19% ($4.9M).
- The top city by revenue is Toronto, with $4.6M, while the lowest revenue city id Berlin, with $2.6M due to th difference in the number of stores in each city.
- The top brand by revenue is ferrero, with $4.7M, while the lowest revenue brand is Hershey, with $3.5M.
- Jan 2023 was the highest month, achieving $1.1M in revenue, while Feb 2023 was the lowest, with $969K.
- Quarter 3 was the highest quarter in both years, achieving the greatest revenue in each year, while quarter 1 and quarter 2 were the lowest.
- The highest day of the week in revenue was Tuesday, while the lowest day was Thursday 
  
## Recommendations

