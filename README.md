# Athletic Sales Analysis
# Sales Analysis Insights

## Cities with the Most Athletic Wear Sales 
The combined data from two years has been cleaned and merged using an inner join, and the index has been reset to ensure a unified dataset for analysis.
The "invoice_date" column has been successfully converted to a datetime data type for accurate time-based analysis.

## Region Sales Analysis 
Utilizing either a groupby or pivot_table function, a multi-index DataFrame has been created with the "region," "state," and "city" columns.
The aggregated column has been appropriately renamed to reflect the total sales or products sold in each region.
Results have been sorted in descending order to identify the top five regions, including their respective states and cities, with the highest sales or product volume.

## Retailer Sales Analysis 
A groupby or pivot_table function has been employed to generate a multi-index DataFrame with detailed information including the "retailer," "region," "state," and "city" columns.
The aggregated column has been renamed to accurately represent the total sales achieved by each retailer.
The analysis results have been sorted in descending order to showcase the top five retailers along with their regions, states, and cities that contributed the most to overall sales.

## Women's Athletic Footwear Sales Analysis
A filtered DataFrame has been created specifically for women's athletic footwear sales data, ensuring focused analysis on this segment.
The use of a groupby or pivot_table function has facilitated the creation of a detailed multi-index DataFrame encompassing the "retailer," "region," "state," and "city" columns.
The aggregated column has been renamed to reflect the total sales of women's athletic footwear for each retailer.
Results have been sorted in descending order to highlight the top five retailers, including their regions, states, and cities, that excelled in selling women's athletic footwear.

## Day and Week Analysis for Women's Athletic Footwear Sales 
A pivot table has been constructed with the "invoice_date" column set as the index and the "total_sales" column for values, providing a daily sales overview.
The aggregated column has been renamed to accurately represent the total sales of women's athletic footwear for each day.
The resample function has been applied to aggregate sales data into daily bins, aiding in identifying the days with the highest women's athletic footwear sales.
Similarly, weekly sales analysis has been conducted using the resample function, sorting the data to reveal the weeks with the most significant women's athletic footwear sales.

## Findings
Overall, this comprehensive analysis provides valuable insights into the top-performing regions, retailers, and specific product segments within the athletic wear market, along with key trends related to women's athletic footwear sales on both a daily and weekly basis.

