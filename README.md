# Coffee-Data-Analysis
Data Cleaning, Analysing and Visualization using `Microsoft Excel` alone. Pivot Table is used for analysing the data.

Dataset : [Coffee Sales](https://github.com/mochen862/excel-project-coffee-sales/blob/main/coffeeOrdersData.xlsx)

`NOTE`: The data uploaded along with the file is cleaned.

This dataset on Coffee beans contains 3 different tables customers, products and orders. 

Explore the sheets and find out the issues with the data. Some of the issues:

1. Missing Data - Populate the Order table with missing data. 5 columns in the order table of raw data are null. If you look into the other 2 tables, these information can be retrieved from them. 

       Used the xlookup function to populate the table.

2. Computed the Sales column , Sales = Unit Price * Quantity

3. Added columns to expand the abbreviation in Coffee Type, Roast Type

4. Changed the format:

        Order date format to dd-mmm-yyyy  (16-Aug-2000)
   
        Size format to 1.0 kg

        Unit price as $ 10

5. Checked for duplicates. 
   
         No duplicates found

7. Made Pivot Table to analyse data and build charts for the dashboard.

          1. Total Sales 
          2. County Bar Chart
          3. Top 5 Customers

