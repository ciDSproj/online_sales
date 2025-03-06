# Online Sales
The goal of this project is the analysis of the global online sales transactions across various products between January and August 2024. The project covers retrieving data from a database, data manipulation, visualizations and answering business questions.

## Overview
- Explored the SQLite database and retrieved data in a Pandas dataframe
- Aggregated Sales by Date and Month to evaluate the overall and seasonal monthly trends
- Created pivot table of monthly Sales by Product Category to explore the seasonal patterns of different products
- Grouped Sales by Payment Methods to see the most popular payment method by region
- Created pivot table of Sales by Region to find which are the most popular product categories in each region

## Resources Used
- SQLite3 module for creating, accesing and exploring the database
- Python 3.7
- Numpy and Pandas libraries for data manipulation
- Matplotlib and Seaborn libraries for data visualization

## Dataset
The Online Sales dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data). Each entry contains information about a single transaction:

- Transaction ID: Unique identifier for each sales order.
- Date: Date of the sales transaction.
- Product Category: Broad category of the product sold (e.g., Electronics, Home Appliances etc.).
- Product Name: Specific name or model of the product sold.
- Units Sold: Number of units of the product sold in the transaction.
- Unit Price: Price of one unit of the product.
- Total Revenue: Total revenue generated from the sales transaction (Quantity * Unit Price).
- Region: Geographic region where the transaction occurred (e.g., North America, Europe, Asia).
- Payment Method: Method used for payment (e.g., Credit Card, PayPal, Debit Card).

## Data Preparation

-  Retrieve data from the SQLite database into a Pandas data frame
-  Convert Date to datetime
-  Made a new column for Month
-  Created a pivot table of monthly sales for each product category to analyze the seasonal patterns of different product categories
- Aggregate Total Revenue by:
     - Date to see the overall sales trend for the entire period
     - Month to obtain the seasonal monthly trend on sales
     - Product Category to find the product categories with the highest sales
     - Region to see which region has the highest sales
     - Payment Methods and Region to obtain the distribution of payment methods by region
- Created a pivot table of sales by product categories and region to find which is the most popular payment method by region


## Exploratory Analysis

