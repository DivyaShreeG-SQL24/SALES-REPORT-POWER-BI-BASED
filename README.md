# SALES-REPORT-POWER-BI-BASED
In this sales report,i have shown how was the sales in 2016-2019 of different product 


DESCRIPTION 

Sales of Beverages Table

This table contains data related to the sales of beverages. It includes key columns such as:

Product Name: The name of the beverage product.
Sales Date: The date on which the sale was made.
Quantity Sold: The quantity of the product sold.
Sales Amount: The total sales amount for the product.
Region: The region where the sale was made.

DATASET

Sales (folder by year),
Categories (Excel),
Geography (Excel),
Product (CSV / Database),
SalesRep (Excel),
SubCategories (Excel).

QUESTION

1.Create a mechanism to load all the files from the sales folder in a single Sales fact table.
The mechanism needs to be resilient as:
	-removing a file from the sales folder does not create an error for missing files.
	-adding a new yearly sales file will automatically be loaded in the fact query upon refresh.

2.Data Modeling: 

2.1. Do the respective transformations to the Sales fact table in order to split the Country form the City in field “Location”. Make sure you set up the correct Data Type to allow Geo maps.
Do the necessary updates in the Date field to make sure you can setup the Date format.

Task 2.2  Create unique key (GeoKey) in Sales and Geography table

Task 2.3: The Dimensional queries SalesRep and Sub Category need additional treatment. Some ID columns have the following format:
Create a small function that removes the “ID - ” part of these columns that you can invoke and reuse for these two queries to clean the IDs.

Task 2.4: 
Create the Data Model connecting all tables and using the Calendar table already set up in the pbix.

3.DAX calculations

Task 3.1. Calculate Total Revenue in Sales table, using the Product’s Retail Price, and multiplying it by the Units.

Task 3.2. Calculate Total Cost in Sales table, using the Product’s Standard Cost, and multiplying it by the Units.

Task 3.3. Calculate Gross Profit in Sales: Total Revenue – Total Cost

Task 3.4. Calculate a Gross profit MoM growth Change% measure that could benefit us in decision making

Task 3.5. Breakdown Analysis by Product (drop or increase)
          Calculate the following time measures:
          This is QBR Report. So QoQ Growth is required.


DASHBOARD

https://github.com/DivyaShreeG-SQL24/SALES-REPORT-POWER-BI-BASED/blob/main/Screenshot%202025-02-03%20225704.png
