This is a data analysis of real estate market data, containing two tables - customers and properties. 
1. Data cleaning and preprocessing
   We begin by reading the two csv files and examinig them. We notice some inconsistencies with the data columns which we must address, including column names, data types and datetime variables.
   Ultimately we must combine them into one table containing information both on the customers and properties.
   The obvious approach is to merge the two tables using the customer_id column. However, there is a catch.
   Upon close inspection, we see that the format of the id columns differ, so we must unite them before the merge.
2. Statistics
   With the two tables merged, we can run descriptive statistics and run some totals and averages by building, country and state. We also want to see some frequency distribution by state.
3. Data Analysis
   Here we want to understand more about the customer profile. First we create a histogram of customers age, for which we must create an age column and determine customers ages from their date of birth.
   Then, we're interested in the properties and create a histogram of prices distribution. Finally we also wish to understand the relationship between the age of customers and the price of properties bought, to    
   discern, among other things, which age groups buys the highest valued properties.
4. The final part of the analysis centeres around data visualization. Using the statistics and data analysis preparation, we can now utilize this information and present it in a more straightforward way. We create the following five visuals:
   a. A bar chart of deal satisfaction across countries
   ![deal_satisfaction_by_country_bar_chart](https://github.com/ElitsaKal/Real-Estate-Data-Analysis/assets/162779608/bbb46dc3-6985-4694-b848-5030ce3f76c5)

   b. A histogram of customers' age distribution
   ![age_distribution_histogram](https://github.com/ElitsaKal/Real-Estate-Data-Analysis/assets/162779608/9f12bf97-19ac-4a6c-b9af-f67c80968610)

   c. A pareto diagram of the segmentation by state
   ![US_segmentation_by_state_pareto_diagram](https://github.com/ElitsaKal/Real-Estate-Data-Analysis/assets/162779608/ef5c14bc-ef29-479f-8994-38e2af164dc4)

   d. A line chart of the total revenue by year
   ![total_revenue_per_year_in_M_line_chart](https://github.com/ElitsaKal/Real-Estate-Data-Analysis/assets/162779608/984a9355-b786-4acf-b8f9-091c4121e1ec)

   e. A stacked bar chart of total sales per building per year
   ![total_sales_per_year_per_building_stacked_area_chart_v2](https://github.com/ElitsaKal/Real-Estate-Data-Analysis/assets/162779608/1a7c542c-9cde-4822-84e1-bebb1f76b097)
