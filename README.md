# Veda-Technology-Task-19
# Top 10 Products by Sales – Task 19
**
Data Analytics Internship Task | Veda Technology
Level 1 · Day 19
**
## Overview

This project identifies the top 10 best-selling products from the Superstore dataset based on total sales. The task focuses on practicing data ranking and sorting techniques using Python.

## Objective

Identify the top 10 products by sales and rank them accurately, including handling of tied values.

## Dataset

The dataset used is a Superstore sales dataset containing details such as Category, Sub-Category, Product Name, Region, Sales, Quantity, Discount, and Profit.

## Tools Used

- Python
- Pandas
- Matplotlib

## Approach

1. Loaded the dataset into a Pandas DataFrame.
2. Grouped records by Product Name and aggregated total Sales.
3. Sorted the results in descending order to identify the top performers.
4. Checked for tied sales values using the `rank()` function.
5. Visualized the results using a bar chart and a category-wise pie chart.

## Deliverables

- `top10_products_table.csv` – Table of the top 10 products by sales
- `top10_products_chart.png` – Bar chart of top 10 products
- `Task19_Top10_Products_Report.pdf` – Full report with insights and conclusion

## Key Insights

- Konica Copier recorded the highest total sales, followed closely by Canon Copier.
- Technology products (Copiers, Printers, Mouse, Keyboard, Phones) dominate the top 10 list, indicating this category generates the highest revenue per unit.
- No exact ties were found among the top 10 rankings.
- High-value items outperform high-volume but lower-priced office supplies in total sales, showing that price per unit plays a bigger role than quantity sold.

## Conclusion

Technology products, particularly copiers and printers, are the biggest contributors to overall sales in the Superstore dataset. Focusing marketing efforts and inventory planning on these high-value items could help further improve total revenue.
