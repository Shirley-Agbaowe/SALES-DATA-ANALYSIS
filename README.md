# SALES-DATA-ANALYSIS


# PROJECT OVERVIEW
#### This project is aimed at analyzing the sales data for the sales performance of each product category across the sales region over some time
to bring forth sights and actionable plans to improve sales performance across regions.

# Objectives
- Customer analysis: To identify customer segments and regions
- Product performance: reviewing product performance and profitability
- Revenue analysis: To identify revenue generated across the region, order date, and customer demographics

# Data sources
#### The primary data source used here is data sales.xlsx, this is open source data that can be downloaded freely from an Open source online such as Kaggle or any other data repository site.

Data Description or Characteristics
-Datasets Raw Dataset (LITA CAPSTONE DATASET.XLSX) https://drive.google.com/drive/u/0/home

It contains the original sales data including fields such as:

OrderID: The order identification number

Customer_ID: Identification number of the customer

Product: Name of the product sold

Region: Geographic region of the sale

Order Date: The date on which the product was ordered

Quantity: Number of units sold

Unit Price: Price per unit


# Tools used
#### Microsoft Excel
- For Data loading, preparation and exploration
- For Data formatting checking data types and removing duplicates
- For Data analysis using Excel functions (SUM, COUNT, AVERAGE, AVERAGEIF, AND SUMIF) for statistical calculations like total revenue, and average revenue.
- Pivot table for summarization and visualization
#### Power BI
- Data cleaning and formatting using power query editor to clean the data, change the data type, create conditional columns, etc
- Data analysis expressions (DAX)
- Dashboard creation for visualization

#### SQL
- for querying the dataset
-  Data Import: Load the data into a SQL database (SQL Server).

ii. Inspect Table Structure: USE sales data or SELECT * FROM [dbo].[SALESDATA]

iii. Basic Queries:

Create DATABASE SALESADATA DB

SELECT * FROM [dbo].[SALESDATA DB]

#### GitHub
-  For portfolio building

 
# Exploratory data analysis
#### Exploratory data analysis involves exploring the data set to format the data and to answer questions about the dataset such as;
-Using Excel  https://docs.google.com/spreadsheets/d/1GJ9ygB0GNIJoW58nH4p7eezGd2ldQ4Yg/edit?gid=1154912660#gid=1154912660
- What is the total sales?
- What is the average sales?
- What are the product sales by region?
- What are the sales by region?
- Average sales by region
- Percentage sales by revenue
- Percentage sales by product

-Using SQL
- Queries to extract key insights based on the following questions.

- Retrieve the total sales for each product category.

- Find the number of sales transactions in each region.

- Find the highest-selling product by total sales value.

- Calculate total revenue per product.

  Calculate monthly sales totals for the current year.

- Find the top 5 customers by total purchase amount.

- Calculate the percentage of total sales contributed by each region.

- Identify products with no sales in the last quarter.

Some of the queries:
https://docs.google.com/document/d/13Ywhd9AYT6XPL7McxxT2MiyDKfXa-JBZ/edit?rtpof=true


# Data analysis
### DAX
- TOTAL SALES=SUM(SALESDATA[SALES])
- AVERAGE SALES=AVERAGE(SALESDATA[SALES])
  
#### This is a pivot table summarization of sales by region
https://docs.google.com/document/d/1ppb0vHHpQTqRJUDUBScrhDn2BNmbYbGOc0jPyjKYtH0/edit?tab=t.0

#### This is a pivot table summarization of sales by product
https://docs.google.com/document/d/1rTwlzBoUtUNI2yEBwVoNMH4m8IlJmtzn/edit?rtpof=true

#### Pivot table summarization of average sales by region
https://docs.google.com/document/d/1ecsE20IdzHdjT2FInbWJuGfktagWScgM/edit

#### Pie Chart showing percentage sales by region























# Data visualization
-SALES BY REGION
https://docs.google.com/document/d/1qBLS2itzE4EnsFxr_Td4E4f7NKCX-dd4Cju_RYaH09U/edit?tab=t.0

-SALES BY PRODUCT
https://docs.google.com/document/d/1-LIwrsLgcgAKSTNjbeWfPtwGHNdBeoE4/edit

-AVERAGE SALES BY REGION
https://docs.google.com/document/d/19DIqWHzh2jTCfEwtsChgV1xzPX_85wiU/edit

-PERCENTAGE SALES BY REGION
https://docs.google.com/document/d/1Jh4s5_fszsOky1k8ahT6YGtpAl6cHg8h/edit

-SALES DATA ANALYSIS DASHBOARD VISUALIZATION
https://docs.google.com/document/d/1YXypENyOv4MxA_hQi7YlRj9J1XvCOEXb/edit


# Sales analysis report
#### The sales report depicts four sales regions (North, South, East, and West) with 6 products(Shirts, Shoes, Socks, Hats, Jackets, Gloves).
Total sales $2,101,090 
Average sales $211.78

Total sales by region: 
- North-$387.000 (18.42%)
- South-$927.820 (44.16%)
- East-$485,925 (23.13 %)
- West-$300.345 (14.29%)

#### The south region generated a higher sales value of $927.820 (44.16%), the north $387.000 (18.42%),  the west region $300.345 (14.29%), the East generated $485,925(14.29%)
with the highest sales generation  from the south and the least sales from the West having  the count of the number of products sold as 9.921k and the total number of customers as 500.

- Sales generated by-products;
- Shirt-$180.785 (23.11%)
- Shoes-$618.380 (29.19%)
- Hat-$316.195  (15.05%)
- Socks-$180.785 (8.6%)
- Jacket-$208.230 (9.91%)
- Gloves-$296.900 (14.13%)

The shoe category of products generated $618.380 (29.19%) as the highest income generation brand while  the hat product brand generated $316.195(15.05%) and the least sales generated by the socks line of products generating $180.785(8.6%)



















