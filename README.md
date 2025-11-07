# amazon-sales-excel-dashboard
# Amazon Sales — Excel Dashboard

## Project overview
This is an Excel-based sales dashboard analyzing Amazon-like retail sales.  
The dashboard focuses on sales, product-line performance, region-wise trends, customer ratings and returns insights.

## Files
- `amazon_sales_excel.xlsx` — Excel dashboard (interactive)  
- `amazon_sales_excel.csv` — Dataset used for analysis (1000 rows)  
- `screenshots/` — Dashboard images (preview)

## Tools & techniques
- Microsoft Excel (PivotTables, Slicers, Pivot Charts, conditional formatting)
- Data cleaning using Excel (Text to Columns, Remove Duplicates)
- Analysis metrics: SUMIFS, AVERAGEIFS, COUNTIFS, INDEX/MATCH (or XLOOKUP),
  and basic Power Query steps if used.

## Key metrics (computed)
- Total Sales: **₹322,966.75** (sum of `total`)  
- Total Orders: **1,000**  
- Total Quantity Sold: **5,510**  
- Average Customer Rating: **6.97**

## Top insights
- **Top product lines** by revenue: Food and beverages; Sports and travel; Electronic accessories.
- **Top cities** by revenue: Los Angeles, San Diego, Chicago.
- **Best-performing branch**: Branch D (highest sales).

## Suggested KPIs & questions (what to answer with this dashboard)
- What is the trend in **monthly sales**? Are there seasonal peaks?  
- Which **product_line** contributes most to revenue and which has the highest average unit_price?  
- Which **city/branch** has the highest Average Order Value (AOV = total / quantity)?  
- How does **customer_type** (Member vs Normal) affect average order value and rating?  
- Is there a correlation between **rating** and **returns** (if returns data exists)?  
- What are the top 10 SKUs / product lines driving 80% of revenue (Pareto analysis)?

## How to reproduce / run
1. Open `amazon_sales_excel.xlsx` in Excel.  
2. Use the slicers for `product_line`, `city`, or `date` to filter views.  
3. Refresh PivotTables (Data → Refresh All) if using Power Query.

