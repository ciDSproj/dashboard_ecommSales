# Power BI E-commerce Sales Transactions 
The project covers creating Power BI Dashboard and Reports for analyzing sales performance and distribution across products and regions for an e-commerce dataset. This dashboard is an example focusing on sales trends, performance of the products and regions,  and discovering the most profitable segment customers. It offers an easy way to view the most important KPI’s and results at a glance.


## Dataset
This analysis uses the Kaggle E-commerce Sales dataset, a sales transaction data of UK-based e-commerce (online retail) for one year. The dataset contains 536350 records and 8 attributes. The following is the description of each column:

1.	TransactionNo: a six-digit unique number that defines each transaction. The letter “C” in the code indicates a cancellation.
2.	Date: the date when each transaction was generated.
3.	ProductNo: a five or six-digit unique character used to identify a specific product.
4.	Product: product/item name.
5.	Price: the price of each product per unit in pound sterling (£).
6.	Quantity: the quantity of each product per transaction. Negative values are related to cancelled transactions.
7.	CustomerNo: a five-digit unique number that defines each customer.
8.	Country: name of the country where the customer resides.

## Preparation
I started by importing the company’s sales data into Power BI, then use Power Query to clean and organize fields and do further transformations.


## Data Visualization and Analysis
When creating visualizations for Dashboard, Sales. Product and Customer Reports, I looked for answers to the following questions:

1. How was the sales trend over the months?
2. What are the most frequently purchased products?
3. How was the sales amount by country?
4. What are the most profitable segment customers?
5. Based on the findings, what strategy could be recommended to the business to gain more profit?

## Visualizations:
-	Area chart for tracking sales trends, to spot seasonality and growth patterns over time
-	Stacked bar charts to uncover top customers and topmost products
-	For a global view, used a filled world map of product orders per country
-	Pie chart of sales by customers to visualize the strong performers
-	Sales by country  using a stacked column chart
-	Yearly sales amount using a pie chart
-	Gauge of the average sales per customer
