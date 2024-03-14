# Produce Cost

### Project Overview

This project's objective is to provide insights on the cost of various produce and how prices compare and contrast. By analyzing some KPIs from the dataset, we look to identify any trends and make data-driven recommendations.

### About the Data

The primary dataset can be found on <https://www.kaggle.com/datasets/maximsakhan/rc-superstore-grocery-data>. This dataset has data regarding current and previous prices and number of units per produce. 

### Tools Used

- Python - Data Cleaning & Data Analysis
- Tableau - Data Visualization

### Data Cleaning/Preparation

1. Data Cleaning
2. Data Sorting and Filtering
3. Data Formatting and Transforming

### Exploratory Data Analysis (EDA)

EDA was performed to answer key questions, such as, but not limited to:

1. Price comparison between current and previous prices
2. Which type of category yielded the most sales?
3. Which type of category had the largest/smallest percent price increase/decrease?

### Results/Findings

1. This graph shows there is a big price difference amongst 'Pantry' items with a total cumalative price difference of over 250$.'Bakery', 'Dairy & Eggs', 'Natural & Organic Foods', and 'Prepared Meals' appears to show the least amount of price differences between current and old prices. Another analysis may be needed to see if price difference in items of each respective category influcences total categorical sales.

![TotalPriceDifference](https://github.com/DavidsDatabase/Produce-Cost/assets/156726833/1fc77d1d-d2dd-4fd2-b971-f3a8c8f910f5)

2. As the graph shows, 'Beverages' , 'Deli', and 'Pantry' appears to have the most total sales amongst the general categories with each surpassing $1.6 million in total sales. The 'Fish & Seafood' and 'Fruits & Vegetables' categories appear to have the least amount of total sales. This could mean that there were more products/quantity of products or higher prices per quanity in the 'Beverages', 'Deli', and 'Pantry' categories thus resulting in more 'total' sales, whereas less products/quantity of products or lower prices in 'Fish & Seafood' and 'Fruits & Vegetables' categories.

![TotalSales](https://github.com/DavidsDatabase/Produce-Cost/assets/156726833/541f79e8-fee4-46da-b524-7a8b68d39812)

3. 'International Foods' appear to have the largest percent decrease in comparison to the other categories with nearly 3.3%  decrease. 'Dairy & Eggs' , 'Meat', and 'Prepared Meals' all appear to have less than .5%, so it would mean that prices amongst these categories did not change much. 

![PricePercent](https://github.com/DavidsDatabase/Produce-Cost/assets/156726833/52c7d937-702c-497e-a3fb-75be2e90b297)

### Recommendations

Based on the analysis, we recommend the following actions:

- Selling the top 'total sales' category items may be the best approach to yield the most sales/profits, such as beverages and pantry items.
- There may be lower risks in losing profits on items that are a low average percentage.

### Limitations

These initial findings may spark some interest, but further analysis would be needed for more concrete results. For example, it would be helpful to have some data about dates of when 'Current Price' and 'Previous Price' were noted for a more time-based analysis. Additionally, more data regarding dates of any other previous prices may prove to be effective in this dataset. Lastly, instead of these 13 'self-grouped' categories to group up the individual 118-count of categories, a more thorough grouping of categories may prove to have a better conclusion regarding the produce's price differences, total sales, percent increase/decrease rates, etc. 

### Complimentary Visualization

<https://public.tableau.com/app/profile/david.lee7724/viz/ProduceDashboard_17039113256920/Dashboard1>











