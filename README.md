# SALES-REPORT-POWER-BI-BASED
In this sales report,i have shown how was the sales in 2016-2019 of different product 

dataset 

 SALES REPORT POWER BI BASED PROJECT

DESCRIPTION 


dataset

Sales (folder by year)
Categories (Excel)
Geography (Excel)
Product (CSV / Database)
SalesRep (Excel)
SubCategories (Excel)

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

