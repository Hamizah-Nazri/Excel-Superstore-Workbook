# Data Wrangling From Superstore_Workbook
This repository contains an Excel project on Superstore's Sales Workbook that demonstrates various features and functionalities of Excel, including data analysis, visualization using Excel formulas and functions.

# Analysis Summary
* Data: orders, returns
* Goal: discover the reason for high volume of returns

# Contents
* Project_1.1_Superstore_Workbook.xlsx and Project_1.2_Superstore_Workbook.xlsx: Showcases various Excel formulas for different scenarios.
* Data_Visualisation.xlsx: Demonstrates data analysis techniques using pivot tables, filters, conditional formatting, dynamic charts, and pivot charts.

# Steps to replicate cleaning
* Replaced blanks with '-' using Find and Select
* Separate city and state using Data -> Text to Column
* Remove extra space in front using =TRIM() function
* Remove duplicate using Data ->> Remove Duplicate
* Reformatting the date using  'ddd', 'mmm' format
* Calculate profit margin by dividing profit over sale
* Combine order_info_id and order_id_number to make new column order_id using CONCAT() function
* Categorise size of items using IF(OR()) function
* Find days of shipping by substracting ship_date from order_date
* Find top customer whom order more than 50 this year using IF(COUNTIF()) function
* Return category, sales, profit and profit margin from the orders sheet to the returns sheet using VLOOKUP and INDEX/MATCH function
* Reason for return is added to the orders table using IFNA(INDEX(MATCH()) function
* Categorise shipping speeds and profit margin in the orders table using VLOOKUP or INDEX/MATCH function
