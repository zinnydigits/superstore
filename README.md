
## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Tools](#tools)
4. [Data Cleaning/Preparatory](#data-cleaningpreparatory)
5. [Explanatory Data Analysis](#explanatory-data-analysis)
6. [Visualization](#visualization)
7. [Codes](#codes)
8. [Recommendations](#recommendations)

### Project Overview<a name="project-overview"></a>
My project aims to analyze sales data of Superstore to gain insights into sales performance, customer behavior, and market trends. By leveraging data analytics, I seek to identify patterns and opportunities for optimization in business operations.
![superstore](https://github.com/zinnydigits/superstore/assets/53875635/b9c87afa-a76c-495e-bbec-d8bccdb9ab57)

### Data Sources<a name="data-sources"></a>
The data sources for my analysis is a dataset containing information on sales transactions, including categories, customers ID, customers name, orders, products, regions, segments etc. This dataset provides comprehensive information to analyze various aspects of sales performance and customer engagement.
Click to download the [dataset](https://github.com/zinnydigits/superstore/blob/main/superstore_final_dataset%20(1).csv), and the [power BI file](https://github.com/zinnydigits/superstore/blob/main/superstore.pbix).

### Tools<a name="tools"></a>
- Microsoft Excel: Used for data validation and verification to ensure dataset cleanliness.
- DAX (Data Analysis Expressions): Used to create calculated columns, measures and performed advanced data manipulation within Power BI.
- Power BI: Used for data visualization, analysis and reporting.

### Data Cleaning/Preparatory<a name="data-cleaningpreparatory"></a>
The dataset required no cleaning or manipulation as it was already clean upon inspection.

### Visualization<a name="visualization"></a>
Visualizations created using Power BI include:
- Total Sales: A card visualization displaying the total sales amount, no of Shipping, total no of customers and average delivery day.
- Sales Trend: A line chart showing sales trend over month.
- Top Selling Products: A bar chart showing the top-selling products by product count and product sales
- Customer Demographics: A pie chart showing customer distribution by segment.
- Order Frequency: A histogram showing the distribution of order frequency.
- A Doughnut chart displaying sales by product category.
- A Pie Chart displaying sales by ship mode.

### Codes<a name="codes"></a>
```
weekday2 = SWITCH('superstore_final_dataset (1)'[weekday], 
                    1, "Sunday", 
                    2, "Monday",
                    3, "Tuesday",
                    4, "Wednesday",
                    5, "Thursday",
                    6, "Friday",
                    7, "Saturday"
)
```

### Explanatory Data Analysis<a name="explanatory-data-analysis"></a>
During the exploratory data analysis, I delved into the dataset to uncover patterns, and trends. 
Below are the insights derived:
- Sales were always low beginning of the year and increases as the months go by.
- Sales are extremely low on Thursday, and for some of the years, Friday.
- Around 54 per cent of the Shipping are done via standard mode.

### Recommendations<a name="recommendations"></a>
Based on my analysis, I recommend:
- Increased promotions and marketing efforts during December, the peak sales period.
- Adjust inventory levels to avoid overstock during low-sales months like January and February.
- Developed targeted sales strategies for Thursday and Friday.
- Gather customer insights to understand preferences and tailor offerings accordingly.
