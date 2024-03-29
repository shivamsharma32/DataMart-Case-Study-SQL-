 # Data Mart Analysis
 ![image](https://github.com/Royalsivm/DataMart-Case-Study-SQL-/assets/153700930/345a0727-aadf-4e5b-8899-ccdb2f9ee080)

  # INTRODUCTION:
Data Dart is my latest venture and I want your help to analyze the sales and performance of my venture. In June 2020 - large scale supply changes were made at Data Mart. All Data Mart products now use sustainable packaging methods in every single step from the farm all the way to the customer.
I need your help to quantify the impact of this change on the sales performance for Data Mart and its separate business areas.

# SCHEMA USED: WEEKLY_SALES TABLE
![image](https://github.com/Royalsivm/DataMart-Case-Study-SQL-/assets/153700930/c9073227-7767-4afc-941c-6225fa0fb095)

# CASE STUDY QUESTIONS

 # # A. Data Cleansing Steps
In a single query, perform the following operations and generate a new table in the data_mart schema named clean_weekly_sales:
1.	Add a week_number as the second column for each week_date value, for example any value from the 1st of January to 7th of January will be 1, 8th to 14th will be 2, etc.
2.	Add a month_number with the calendar month for each week_date value as the 3rd column
3.	Add a calendar_year column as the 4th column containing either 2018, 2019 or 2020 values
4.	Add a new column called age_band after the original segment column using the following mapping on the number inside the segment value
segment	age_band
1	Young Adults
2	Middle Aged
3 or 4	Retirees
5.	Add a new demographic column using the following mapping for the first letter in the segment values:
segment | demographic |
C | Couples |
F | Families |

6.	Ensure all null string values with an "unknown" string value in the original segment column as well as the new age_band and demographic columns
7.	Generate a new avg_transaction column as the sales value divided by transactions rounded to 2 decimal places for each record


# # B. Data Exploration
1.	Which week numbers are missing from the dataset?
2.	How many total transactions were there for each year in the dataset?
3.	What are the total sales for each region for each month?
4.	What is the total count of transactions for each platform?
5.	What is the percentage of sales for Retail vs Shopify for each month?
6.	What is the percentage of sales by demographic for each year in the dataset?
7.	Which age_band and demographic values contribute the most to Retail sales?

