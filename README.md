This is a data analysis of real estate market data, containing two tables - customers and properties. 
1. Data cleaning and preprocessing
   We begin by reading the two csv files and examinig them. We notice some inconsistencies with the data columns which we must address, including column names, data types and datetime variables.
   Ultimately we must combine them into one table containing information both on the customers and properties.
   The obvious approach is to merge the two tables using the customer_id column. However, there is a catch.
   Upon close inspection, we see that the format of the id columns differ, so we must unite them before the merge.
2. Statistics
   With the two tables merged 
