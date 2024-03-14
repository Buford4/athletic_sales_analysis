# Athletic Sales Analysis
# Challenge
## Combine and Clean
1. Import the two CSV files, athletic_sales_2020.csv and athletic_sales_2021.csv, and read them into DataFrames.
2. Check that the columns in the two DataFrames have similar names and data types.
3. Combine the two DataFrames by the rows using an inner join, and reset the index.
4. After combining the DataFrames, do the following:

    a. Check if there are any null values.

    b. Check each column's data type.

    c. Convert the data type has been changed.

## Determine which Region Sold the Most Products
1. Use either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and "city" columns.
2. Rename the aggregated column to reflect the aggregation odf the data in the column.
3. Sort the results in ascending order to show the top five regions, including the state and city that have the greatest number of products sold.

## Determine which Region had the Most Sales
1. Use either the groupby or pivot_table function to create a multi-index DataFrame with the "region", "state", and "city" columns.
2. Rename the aggregated column to reflect the aggregation of the data in the column.
3. Sort the results in ascending order to show the top five regions, including the state and city that generated the most sales. 

## Determine which Retailer had the Most Sales
1. User either goupby or pivot_table function to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns.
2. Rename the aggregated column to reflect the aggregation of the data in the column.
3. Sort the results in ascending order to show the top five retailers along with their region, state, and city that generated the most sales.

## Determine which Retailer Sold the Most Women's Athletic Footwear
1. Filter the combined DataFrame to create a DataFrame with only women's athletic footwear sales data.
2. Use either the goupby or pivot_table function to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns.
3. Rename the aggregated column to reflect the aggregation of the data in the column.
4. Sort the results in ascending order to show the top five retailers along with their region, state, and city that sold the most women's athletic footwear.

## Determine the Day with the Most Women's Athletic Footwear Sales
1. Create the pivot table with with "invoice_date" column as the index and the "total_sales" column as the values parameter.
2. Rename the aggregated column to reflect the aggregation of the data in the column.
3. Apply the resample function to the pivot table, place the data into daily bins, and get the total sales for each day.
4. Sort the resampled DataFrame in ascending order to show the top 10 days that generated the ost women's athletic footwear sales.

## Determine the Week with the Most Women's Athletic Footwear Sales
1. Apply resample to the pivot table above, place the data into weekly bins, and get the total sales for each week.
2. Sort the resampled DataFrame in ascending order to show the top 10 weeks that generated and most women's athletic footwear sales.

# Requirements
## Combine and Clean
* The two DataFrames have been combined on the rows using the inner join and the index has been reset.
*   The "invoice_date" column has been converted to a datetime data type.
## Determine which Region Sold the Most Products
* A groupby or pivot_table function has been used to create a multi-index DataFrame with the "region", "state", and "city" columns.
* The aggregated column has been renamed to reflect the aggregation of the data in the column
* The results are sorted in ascending order to show the top five regions, including the state and city that sold the most products.
## Determine which Region had the Most Sales
* A groupby or pivot_table function has been used to create a multi-index DataFrame with the "region", "state", and "city" columns
* The aggregated column has been renamed to reflect the aggregation of the data in the column.
* The results are sorted in ascending order to show the top five regions, including the state and city that generated the most sales.
## Determine wich Retailer had the Most Sales
* A groupby or pivot_table function has been used to create a mulit-index DataFrame with the "retailer", "region", "state", and "city" columns.
* The aggregated column ahs been reneamed to reflect the aggregation of the data column.
* The results are sorted in ascending order to show the top five retailers along with their region, state, and city that generated the most sales.
## Determine which Retailer Sold the Most Women's Athletic Footwear
* A filtered DataFrame is created that shows only women's athletic footwear sales data.
* A groupby or pivot_table function has been used to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns.
* The aggregated column has been renamed to reflect the aggregation of the data in the column.
* The results are sorted in ascending order to show the top five retailers along with their region, state, and city that had the most womens' athletic footwear sales.
## Determine the Day with the Most Women's Athletic Footwear Sales
* A pivot table is created that has the "invoice_date" column as the index and the "total_sales" column assigned to the values parameter.
* The aggregated column has been renamed to reflect the aggregation of the data in the column.
* The resample function is used on the pivot table, the data is placed into daily bins, and the total sales for each day is calculated.
* The results are sorted in ascending order to show the days that generated the most women's athletic footwear sales.
## Determine the Week with the Most Women's Athletic Footwear Sales
* The resample function is used on the pivot table, the data is placed into weekly bins, and the total sales for each week is calculated.
* The results are sorted in ascending order to show the weeks that generated the most women's athletic footwear sales.

