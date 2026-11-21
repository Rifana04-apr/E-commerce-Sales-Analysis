# E-commerce-Sales-Analysis
## Project Overview
This project focuses on E-Commerce Sales Analysis Using Microsoft Power BI. The objective is to explore, import, transform and model sales data 
to prepare it for analysis.
## Tools Used
 - CSV files
 - Microsoft Power BI
 - Power Query Editor
## Project Steps
## Import Data
 - Imported List of Orders.csv into Power BI.
 - Opened Power Query Editor using the Transform option.
 - Imported Order Details.csv and Sales Target.csv into power query editor.
## Data Transformation
 - Restricted the "List of orders" table to only 500 rows.
 - Changed the "order date" column in the "List of orders" table to data type 'Date'.
 - Changed the data type of "Amount" and "Target" columns to 'fixed decimal number'.
 - Formatted the "Customer name" column.
 - Using 'custom column' merged the "state" and "city" to a new column named "location".
 - Using 'custom column' created new column named "profit margin".
 - Using 'conditional column' created a new column "Profit status" 
## Merging Data
 - Merged the "list of orders" and "order details" tables into a new single table named "Orders data" based on the "Order ID" relationship.
## Handling and Missing Data
 - Identified missing values in the dataset using power query.
 - Reviewed null values
 - Checked for the duplicate records in the dataset, and removed duplicates.
## Sorting and Filtering
 - In the "orders data" sorted the 'orders date' in descending order.
 - Applied filter to focus only on a specific state(tamil nadu).
## Grouping and Aggregating
 - Both tables duplicates are created.
 - using 'group by' tab, the given data's are created in separate tables.
 - In order to aggregate the total target amount by month of order date, we want to creat  a "month name"column first, after that using 'group by' tab 'total sales target is created'.
## Data Modeling
 - Established relationship between "List of orders" and "Oreder Details" tables using "Order ID"
 - Also build a relationship between "Orders Details " and "Sales Target" tables based on the 'Category' column.
## Conclusion
 - This assignment helped me gain hands on experience with Microsoft Power BI and understand the initial stages of the data analytics process, from importing raw data to prepare datasets for analysis.
Thank you for reading My journey of learning Power BI.
 - 
 - .
