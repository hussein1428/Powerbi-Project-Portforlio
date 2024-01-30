# Sales Analysis

### Project Overview
This data analysis project aims to explore sales trends over time, identify the best-selling products, calculate revenue metrics such as total sales and profit margins, and create visualizations to present findings.
![Screenshot (39)](https://github.com/hussein1428/Powerbi-Project-Portforlio/assets/97979006/35eefd95-25f1-4676-a09a-afa216679b1f)

### Data source
Sales Data: The primary dataset used for this analysis is the “Sales Data.csv” file containing detailed information about each sales made.

### Tools
-	Excel – Data cleaning
-	Microsoft Power BI – creating reports [Download]( https://www.microsoft.com/store/productId/9NTXR16HNW1T?ocid=pdpshare)

### Data Cleaning/Preparation
In the initial Data preparation phase the following tasks were performed:
1.	Data loading and inspection
2.	Handling missing values
3.	Data cleaning and formatting

### Exploratory Data Analysis
EDA involved exploring the sales data to answer any questions such as:
-	What is the overall sales trend?
-	What are the top-selling products?
-	What are the top cities by sales?

### Data Analysis
At this point, DAX is used to create new measures and column in Power BI as follows:
- Days of the week = WEEKDAY(‘Sales Data’[Order Date])
- Days of the week = FORMAT(‘Sales Data’[Order Date],”dddd”)
- PROFIT MARGIN = (([TOTAL SALES]-[TOTAL COST])/[TOTAL SALES])*100
- TOTAL COST = SUM('Sales Data'[Price Each])
- TOTAL SALES = SUM('Sales Data'[Sales])

  ### Result of the findings
  The analysis results are summarized as follows:
  -	The sales was relatively steady through out the year with noticeable peak during the festive season in December
  -	The five best selling products include iPhone, 24in 4k Gaming Monitor, Google phone, Macbook Pro Laptop and ThinkPad Laptop.
  -	Top 5 cities with highest sales include San Fransisco, Los Angeles, New York City, Boston and Atlanta
  
### Recommendation
Based on the Analysis we recommend the following actions:
-	Invest in marketing and promotion during the peak sales season to maximize revenue
-	Focus on expanding and promoting highest selling products
-	Increase marketing activities and promotion in cities with highest sales

