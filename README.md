**Electronic Devices Sales Data Analysis**

**Overview**

This project involves analyzing sales data for electronic devices using Python in a Jupyter Notebook. The dataset comprises multiple CSV files, which have been merged and processed to derive meaningful insights into sales patterns. The analysis includes identifying the best month for sales, the city with the highest sales, optimal times for advertisements, the most popular products, and frequently sold product pairs.

**Project Structure**

*Data*: Merged CSV files containing sales data for electronic devices.

*Notebook*: Jupyter Notebook containing the complete data analysis process and visualizations.

**Tasks and Analysis**

**1. Data Merging and Preparation**
   
*Merged 12 CSV Files:* Combined multiple CSV files into a single DataFrame using a for loop and concatenation.

*Data Cleaning:* Dropped NaN values and converted 'price each' and 'quantity ordered' columns to integers.

*Sales Column:* Created a new column for sales by multiplying price and quantity ordered. Saved the cleaned and merged data into a single CSV file.

**2. Sales Analysis by Month**
   
*Best Month for Sales:* Grouped data by month and summed sales.

*Visualization:* Bar chart visualizing sales by month using Matplotlib.

*Results:* December had the highest sales ($4.61 million), likely driven by the holiday season and end-of-year spending. In contrast, January had the lowest sales ($1.82 million), possibly due to post-holiday spending reductions and adjustments in consumer budgets at the start of the yea

**3. Sales Analysis by City**
   
*City Sales Analysis:* Added a city column by extracting city names from addresses.

*Visualization:* Bar chart comparing sales by city using Matplotlib.

*Results:* San Francisco had significantly higher sales ($8.26 million) compared to Austin ($1.82 million).

**4. Optimal Times for Advertisements**

*Time Analysis:* Converted timestamps to datetime, created hour and minute columns, and grouped by these time components.

*Visualization:* Line graph showing order quantities by time using Matplotlib.

*Results:* Peak order times are around 12 PM and 7 PM. This suggests that businesses should focus on advertising during these peak hours, as these times likely coincide with lunch breaks and post-work shopping. Time-specific promotions and enhanced mobile shopping experiences during these periods could further boost sales.

**5. Most Popular Products**
   
*Product Sales Analysis:* Created a chart displaying sales figures for various products, including overlaying a second Y-axis.

*Results:* AAA batteries were the top-selling item, with 31,017 units sold, while the LG Dryer only sold 646 units.This could be due to their higher price points, which might make them less accessible to certain customers.

**6. Frequently Sold Product Pairs**

*Product Pair Analysis:* Identified frequently sold product pairs by finding duplicates and counting occurrences.

*Results:* The most commonly ordered pair was iPhone with Lightning Charging Cable (1005 occurrences), while the least ordered pair was Lightning Charging Cable with Wired Headphones (92 occurrences).


This analysis of electronic devices sales data reveals key insights into sales trends and consumer behavior. December emerged as the peak month for sales, likely driven by holiday shopping, while January saw a dip due to post-holiday budget adjustments. San Francisco led in sales, reflecting its larger market size and higher income levels. Optimal advertisement times are around 12 PM and 7 PM, aligning with lunch breaks and evening hours. AA Batteries (4-pack) were the most popular product, suggesting high demand for affordable essentials, while the LG Dryer had lower sales, potentially due to its higher price and less frequent necessity. Additionally, the iPhone and Lightning Charging Cable were frequently purchased together, highlighting strong product pairing preferences.
