### Project Overview
This project aims to analyze sales data of Superstore to gain insights into sales performance, customer behavior, and market trends. By leveraging data analytics, I seek to identify patterns and opportunities for optimization in business operations.
![superstore](https://github.com/zinnydigits/superstore/blob/main/superstore.PNG)

### Data Sources
The data sources for my analysis is a dataset containing information on sales transactions, including categories, customers ID, customers name, orders, products, regions, segments etc. This dataset provides comprehensive information to analyze various aspects of sales performance and customer engagement.
Click to download the [dataset](https://github.com/zinnydigits/superstore/blob/main/superstore.xlsx), and the [power BI file](https://github.com/zinnydigits/superstore/blob/main/superstore.pbix).

### Tools
- Microsoft Excel: Used for data validation and verification to ensure dataset cleanliness.
- Power Query: Used to create calculate delivery duration for each order.
- DAX: Used calculate product returns %
- Power BI: Used for data visualization, analysis and reporting.

### Data Cleaning/Preparatory
The dataset required no cleaning or manipulation as it was already clean upon inspection.

### Visualization
Visualizations created using Power BI include:
- Cards: To visualize total sales, total orders, total discount, total customer, product return %, and avg delivery days.
- Sales Trend: A line chart showing sales trend over month.
- Column Chart: Used to visualize top customers by sales, top selling products by sales and total sales by week day.
- Donut chart: Displaying profit by Region, Sales by Segment, and Sales by Ship Mode.
- Slicer: Used to select years.

### DAX
```
      product return % = COUNT(Orders[Order ID])/COUNT(Returns[Returned])         
```

### Explanatory Data Analysis
Below are the insights derived from the exploratory data analysis:
- Sales were always low beginning of the year and increases as the months go by.
- Sales are extremely low on Thursday, and for some of the years, Friday.
- Around 54 per cent of the Shipping are done via standard mode.
- Delivery takes 4 days on average.
- 2.96% of orders are returned.
- 51% of sales are consumer product category.
- West region brings the most profit which is 38% of total profit.

### Recommendations
- Increased promotions and marketing efforts during December, the peak sales period.
- Adjust inventory levels to avoid overstock during low-sales months like January and February.
- Developed targeted sales strategies for Thursday and Friday.
- Gather customer insights to understand preferences and tailor offerings accordingly.
