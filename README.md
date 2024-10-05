# Tableau-Sales-Dashboard

## Overview

This Tableau dashboard serves as a comprehensive tool for analyzing sales, product performance, and customer behaviour within the Superstore dataset. By utilizing various visualizations and KPIs, stakeholders can gain valuable insights that inform strategic decisions and drive business growth.
This project focuses on cleaning and analyzing the Superstore dataset by merging it with customer age data. The data is cleaned and processed using Python, and the processed data is used to create a Tableau Sales dashboard that provides valuable insights into an overview of the superstore, customer demographics and Product Overview.


## Technologies Used


**Python**: Python is used for data cleaning and preparation using Pandas.

**Tableau**: For visualizing and analyzing the processed data.



## Project Files



1.SuperstoreUnprocessed.csv: The unprocessed Superstore dataset.

2.CustomerInformation.csv: Additional customer information dataset.

3.Superstore_Cleaning.ipynb: Google Colab containing the Python code for data cleaning.

4.Sales Dashboard.twb: Tableau dashboard file.


## Data Cleaning Process

The detailed data cleaning process, including the following steps, is documented in the Google Colab (Superstore_Cleaning.ipynb):

1. Importing the raw Superstore and customer data.

2. Merging the datasets to create a new dataset.

3. Correcting data types 

4. Handling missing values.

5. Creating new columns.

6. Saving the processed data to a CSV file for use in Tableau.


### To view the full data cleaning process, open and run the 'Superstore_Cleaning.ipynb' file in Jupyter Notebook.

## Tableau Dashboard

The processed dataset was used to build the Sales Dashboard.

## Summary Page
The Summary Page provides an overview of the key performance indicators (KPIs) for the Superstore data analysis. The KPIs displayed include:



1. Total Sales: This metric shows the overall revenue generated from all transactions within the dataset.


2. Products Sold: This indicates the total number of products sold, reflecting the volume of transactions.


3. Average Order Value (AOV): This calculates the average amount spent per order, providing insights into customer purchasing behaviour.

4. Profit: Displays the total profit generated from sales.
   

5. New vs Returning customers: This visualization distinguishes between new and returning customers, helping to identify customer retention and acquisition trends.

6. Top 5 performing products: Shows the Top 5 Performing Products based on sales volume, allowing for quick identification of bestsellers.

7. Sales Contribution by Category: A bar chart that visualizes the revenue contribution of different product categories, highlighting areas of strength and opportunity.

8. Transactions by Year: A bar chart illustrating the number of transactions over the years, highlighting sales growth or decline.

9. Map of Countries by Sales: This geographic visualization displays sales figures by country.


## Products Overview Page


### The Products Overview Page delves deeper into product performance and logistics, showcasing:



1. Average Shipping Time: This KPI measures the average time to ship products to customers, which is crucial for customer satisfaction.



2. Top and Bottom Performing Products: Highlights the products generating the highest and lowest profit margins, providing insights for inventory management and marketing strategies.



3. Profit by Year: A time series visualization that tracks profit trends over the years, allowing for an evaluation of business growth.



4. Sales by Order Month: A bar chart that presents sales figures month by month, highlighting seasonal trends in purchasing behaviour.



5. Sales by Age Range: This visualization breaks down sales data according to customer age ranges, helping to identify which demographics are the most profitable.



## Customer Overview Page


### The Customer Overview Page focuses on customer demographics and behavior




1. Payment Method Visualization: This visualization shows the distribution of different payment methods used by customers, indicating preferences in transaction types.


3. Top 5 Customers by Transactions: Lists the customers with the highest transaction volumes.



4. New Customers by First Purchase Month: A visualization that tracks the acquisition of new customers over time, highlighting growth trends in the customer base.



5. Revenue Contributions by Age: This metric shows how different age groups contribute to overall revenue, assisting in targeted marketing efforts.



6. Count of Customers by Region: Displays the total number of customers segmented by geographic region, providing insights into market penetration and regional performance.




