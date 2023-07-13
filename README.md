# Superstore Sales Dashboard
## Overview
This repository contains a Superstore Sales Dashboard developed using Power BI. The dashboard provides insights and visualizations based on a dataset obtained from Datahub.io.
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
## Screenshots
![image](https://github.com/chinmoy2306/superstore_sales_analysis/blob/2e998729d7d9f8d5024f9410ea8f1f3ab70ae8d6/Screenshot.jpg)
## Usage
To explore the Superstore Sales Dashboard:
1.	Clone the repository: git clone https://github.com/chinmoy2306/superstore_sales_analysis.git
2.	Open Power BI Desktop or Power BI Online.
3.	Import the dataset files (sales_table.csv, product_table.csv, customer_table.csv) located in the repository.
4.	Open the Power BI project file (superstore_sales_dashboard.pbix) located in the repository.
5.	In Power BI, refresh the data connection to ensure the dashboard is using the latest dataset.
6.	Interact with the different dashboard components to gain insights into the Superstore sales data.
7.	Customize the dashboard as per your requirements by modifying the visuals, adding new insights, or connecting additional data sources.
## Dependencies
To work with the Superstore Sales Dashboard, you will need the following:
-	Power BI Desktop or Power BI Online: The dashboard was designed using Power BI and requires Power BI Desktop or Power BI Online to explore the visuals and interact with the data.
-	Dataset: Obtain the dataset files (sales_table.csv, product_table.csv, customer_table.csv) located in the repository and import them into Power BI.
-	Please ensure that you have the appropriate software and dataset available before using the dashboard.
## License
The dataset used in this project is sourced from Datahub.io and is subject to the licensing terms provided by the dataset author. Please refer to the Datahub.io dataset documentation for more information on licensing and usage restrictions.
## Acknowledgments
Special thanks to Datahub.io for providing the Superstore sales dataset, enabling us to create this analytics dashboard. We appreciate their efforts in collecting and sharing the data for analysis.
