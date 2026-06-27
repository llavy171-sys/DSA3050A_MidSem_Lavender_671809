## DSA3050A Midsemester Exam
### Name: Lavender Achieng' Onyango-671809

## Data Source
### Dataset: Bike Sales in Europe
### Source: **Bike Sales in Europe** by Sadiq Shah

https://www.kaggle.com/datasets/sadiqshah/bike-sales-in-europe

## Dataset Summary
### Number of Rows: 113,037
### Number of Columns: 18
### Time Period: 2011–2016

## Business Problem

The company needs to understand the factors driving bike sales performance across different countries, product categories, and customer segments between 2011 and 2016. Specifically, the analysis aims to identify which products generate the highest revenue and profit, which customer age groups contribute most to sales, how sales performance changes over time, and which markets are the most profitable. These insights support data-driven decisions on marketing, inventory management, product strategy, and resource allocation to improve overall business objectives.

## Power Query Transformations Performed
### Basic Data Cleaning
### Renamed unclear column names.
### Changed column data types.
### Removed duplicate records.
### Removed blank rows.
### Trimmed and cleaned text columns.
### Replaced inconsistent text values.
### Removed redundant columns (Day, Month, and Year).

## Intermediate Transformations
### Merged Country and State into a Location column.
### Split the Location column back into Country and State.
### Created a custom column (Profit Margin).
### Created a conditional column (Business Category).
### Extracted Year, Month, Quarter, and Day from the Date column.
### Filtered rows using multiple conditions.
### Sorted data by Revenue (Descending).
### Added an Index column.

## Advanced Power Query Tasks
### Grouped data by Country with multiple aggregations (Revenue, Profit, Order Quantity).
### Created a Reference Query for summarized analysis.
### Extracted text before and after a delimiter.
### Used nested conditional logic to create business categories.
### Used Column Profiling to assess data quality.

## Visuals Created

- KPI Card – Total Profit
- KPI Card – Total Revenue
- KPI Card – Total Cost
- Slicer – Country
- Slicer – Product Category
- Slicer – Age Group
- Clustered Column Chart – Total Revenue by Age Group
- Clustered Column Chart – Total Profit by Country
- Clustered Bar Chart – Total Unit Cost by Product
- Clustered Bar Chart – Revenue by Product Category
- Line Chart – Revenue Trend (2011–2016)
- Pie Chart – Total Profit by Country
- Table – Sales Details
- Matrix – Total Revenue by Country and Category
- Map – Total Profit by Country

## Business Insights

1. **Bikes are the highest revenue-generating product category.**
   - The Revenue by Product Category chart shows that Bikes contribute significantly more revenue than Accessories and Clothing, indicating that bicycle sales are the primary driver of business performance.

2. **Revenue is concentrated among Adult customers.**
   - The Total Revenue by Age Group chart indicates that the Adult (35–64) age group generates the highest revenue, suggesting this demographic represents the company's largest customer segment and should remain a key target for marketing and sales initiatives.

3. **Revenue fluctuated over the 2011–2016 period, with a noticeable peak around 2015.**
   - The Revenue Trend line chart shows sales growth over time followed by a decline in the final year, highlighting changes in sales performance that may warrant further investigation into market conditions, seasonality, or business strategies.






