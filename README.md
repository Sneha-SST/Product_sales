Product Sales Data Cleaning and Analysis

This repository contains a hands-on exercise aimed at improving your data cleaning and analysis skills, bringing you one step closer to becoming a Data Analyst. The task involves cleaning, merging, and analyzing a dataset related to product sales using the product_sales.xlsx file, which contains three tables: Orders, Products, and Customer.

Dataset Description
The product_sales.xlsx file includes the following tables:

Orders: Contains details about orders placed by customers.

Columns: order_id, date, customer_id, product_id, qty
Products: Contains information about the products offered by the company.

Columns: product_id, product_name, nutritional information (calories, protein, carbs, fat), price (in Rs)
Customer: Contains information about the customers who have placed orders.

Columns: customer_id, customer_name
Tasks Overview
Task 1: Cleaning the Bad Data
Orders Table
Remove Duplicates: Eliminate duplicate order_id entries to prevent double-counting in analysis.
Data Type Conversion: Convert product_id from a numeric type to text.
Correct Quantity Data:
Replace entries in the qty field ending with "Q" to corrected values.
Substitute empty values in the qty column with the text Not Available.
Products Table
Trim Spaces: Remove leading and trailing spaces in product_name.
Extract Price Values:
Split the price (in Rs) column at the ₹ symbol and extract numeric values.
Rename columns appropriately.
Customer Table
Standardize Names: Convert all customer names to lowercase.
Permanent Changes: Copy the cleaned names and paste them using 'Paste Special' -> 'Values'.
Task 2: Merging Data
Retrieve Customer Names:

Use the VLOOKUP() function to retrieve customer names corresponding to their customer_id in the orders table.
Retrieve Product Names:

Use the INDEX-MATCH() function to get product names for their product_id in the orders table.
Retrieve Product Prices:

Use the XLOOKUP() function to obtain the corresponding price (in INR) for products listed in the orders table.
Calculate Total Price:

Add a new column, total_price, in the orders table to calculate the product of qty and price (in INR).
Getting Started
Prerequisites
To complete this exercise, you’ll need:

Microsoft Excel or a compatible spreadsheet tool.
Basic understanding of data cleaning and Excel functions (TRIM, VLOOKUP, INDEX-MATCH, XLOOKUP).
Steps to Follow
Open the product_sales.xlsx file in Excel.
Follow the cleaning steps described in Task 1 for each table.
Use the specified formulas in Task 2 to merge and enrich the data.
Save the final cleaned and merged dataset for further analysis.

Outcome
After completing this exercise, you will have:

A cleaned and well-structured dataset ready for analysis.
Experience using advanced Excel functions like TRIM, VLOOKUP, INDEX-MATCH, and XLOOKUP.
A better understanding of data cleaning, integration, and preparation techniques essential for data analysis.
