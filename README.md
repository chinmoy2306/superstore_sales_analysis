# Superstore Sales Dashboard
## Overview
This repository contains a Superstore Sales Dashboard developed using Power BI. The dashboard provides insights and visualizations based on a dataset obtained from Datahub.io.
## Screenshots
![](https://github.com/chinmoy2306/superstore_sales_analysis/blob/main/Screenshot.jpg)
## Dataset
The dataset used for this project is sourced from Datahub.io and consists of three tables: -
-	sales
-	product
-	customer

The respective tables contain the following fields:
-	sales: Contains information on order ID, order date, shipping date, shipping mode, customer ID, product ID, and sales figures.
-	product: Includes details on product ID, category, sub-category, and product name.
-	customer: Provides information on customer ID, customer name, segment, country, city, state, postal code, and region.

Please refer to the Datahub.io dataset for more details and specific information on data usage.
## Project Structure
This repository is structured as follows:
-	Readme file: README.md
-	Raw dataset file:
	- [sales.csv](https://github.com/chinmoy2306/superstore_sales_analysis/blob/2e6bef7ebb99b246a424dc0c50b69ba9760ef92d/sales.csv)
	- [product.csv](https://github.com/chinmoy2306/superstore_sales_analysis/blob/2e6bef7ebb99b246a424dc0c50b69ba9760ef92d/product.csv)
	- [customer.csv](https://github.com/chinmoy2306/superstore_sales_analysis/blob/2e6bef7ebb99b246a424dc0c50b69ba9760ef92d/customer.csv)
-	[superstore_dashboard.pbix](https://github.com/chinmoy2306/superstore_sales_analysis/blob/2e6bef7ebb99b246a424dc0c50b69ba9760ef92d/superstore_dashboard.pbix):
	- This power bi file contains the dashboard comprising of various visualizations performed on the dataset.
	- Feel free to explore the superstore_dashboard.pbix file to view the specific visualizations used in this analysis.
## Dashboard Components
The Superstore Sales Dashboard includes the following components:
-	KPI Metrics: Presents key performance indicator metrics such as total sales, average ticket size, total orders, average shipping days, and total customers.
-	Sales Comparison Analysis: Compares total sales with the same period last year sales, highlighting the sales growth or decline.
-	Top five Products & Customers: Identifies the top five products based on sales and the top five customers based on their contribution to sales.
-	Total Sales Pareto Chart: Visualizes the total sales by the sub-categories of products, allowing for the identification of high-impact sub-categories.
-	Sales by Segment and Region: Analyses the total sales by product segment and geographical region, providing insights into the sales distribution across different segments and regions.
-	Geographic Sales Distribution: Displays the total sales by geographical location on a map chart, enabling the identification of sales hotspots and regional performance.
