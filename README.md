# Online Sales
The goal of this project is the analysis of the global online sales transactions across various products between January and August 2024. The project covers retrieving data from a database, data manipulation, visualizations and answering business questions.

## Overview
- Explored the SQLite database and retrieved data in a Pandas dataframe
- Aggregated Sales by Date and Month to evaluate the overall and seasonal monthly trends
- Created pivot table of monthly Sales by Product Category to explore the seasonal patterns of different products
- Grouped Sales by Payment Methods to see the most popular payment method by region
- Created pivot table of Sales by Region to find which are the most popular product categories in each region

## Resources
- SQL3Lite for accesing and exploring the database
- Python 3.7
- Numpy and Pandas libraries for data manipulation
- Matplotlib and Seaborn libraries for data visualization

The project is primarily based in Python and some SQLite3. 

It uses Numpy and Pandas libraries for data manipulation, SQLite3 for accesing the database and Matplotlib and Seaborn for visualizations.

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

