# SalesAnalyticsDotNet

This is a **C# notebook project** for analyzing sales data. It calculates total revenue, top customers, best-selling products, and monthly revenue.

## Notebook File

`SalesAnalysisNotebook.csx` — contains all code and sample data in a notebook style.

## Features

1. **Load Sales Data**
   - Uses embedded CSV sample data.
   - Loads into a C# object model (`Sale` class).

2. **Add Revenue Column**
   - Calculates revenue per sale (`Quantity * Price`).

3. **Total Revenue**
   - Calculates total revenue across all sales.

4. **Best Selling Product**
   - Finds the product with the highest total quantity sold.

5. **Top 3 Customers**
   - Groups sales by customer.
   - Calculates total spent per customer.
   - Shows the top 3 customers.

6. **Monthly Revenue**
   - Groups sales by month.
   - Calculates total revenue per month.
   - Orders results for trend analysis.
