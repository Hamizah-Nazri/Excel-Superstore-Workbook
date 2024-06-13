# Data Wrangling From Superstore_Workbook

# Analysis Summary
Data: orders, returns
Goal: discover the reason for high volume of returns


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


