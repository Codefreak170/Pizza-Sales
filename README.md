# Pizza-Sales-Data-Analysis
This Pizza Sales Analysis project demonstrates proficiency in using SQL and Power BI to analyze and visualize data effectively, to uncover actionable insights into sales trends and product performance for a pizza restaurant.

## Problem Statement
A popular pizza store wants to optimize its sales and marketing strategies to increase revenue and customer satisfaction.To achieve this, the company needs to analyze its sales data to uncover insights into customer preferences, sales trends, and product performance.The goal is to uncover insights from the data and develop actionable recommendations to drive business growth. The Client divided the problem statement into two sections;

## KPI’s requirement
We need to analyze the key indicators for our Pizza sales data to gain insights into our business performance, we want to calculate the following metrics :

•	Total Revenue
•	Total Orders
•	Average Order Value
•	Total Pizzas Sold
•	Average Pizzas Per Order

Charts requirement We would like to visualize various aspects of our Pizza sales data to gain insights and understand key trends. We have identified the following requirements for creating charts :

•	Daily trend for Total Orders
•	Monthly trend for Total Orders
•	Percentage of sales by pizza Category
•	Percentage of sales by pizza Size
•	Total pizzas sold by pizza Category
•	Top 5 best selling & Bottom 5 worst selling pizzas
## Objectives
Conduct a comprehensive sales performance analysis for a pizza store using SQL queries and visualize the findings using Power BI. The objective is to gain insights into sales trends, revenue distribution, and top performing products to inform strategic decision-making and optimize sales strategies.

## Delivarables
1. SQL Queries:
• Extract and aggregate sales data from the pizza sales dataset to calculate key metrics such as total sales revenue, average order value, Total Orders.

• Analyze sales trends over time (hourly, daily, monthly) to identify peak sales periods and seasonal variations.

• Calculate sales performance metrics for individual products, including best-selling pizzas, popular pizza sizes, and revenue contribution by product category.

2. Power BI visualizations:
• Develop interactive dashboards and visualizations to present the analysis findings in a clear and visually appealing manner according to business requirement.

• Create line charts to visualize sales trends over time, with filters for different time periods.

• Generate pie charts to illustrate revenue distribution by product category and size, highlighting top-selling items and revenue contribution.

• Incorporate slicers and filters to allow users to dynamically explore the data and uncover insights based on their specific criteria and interests.

SOFTWARE USED

• Microsoft Power BI 2024

## Data Understanding
1. Dataset description
Source : Kaggle

Format : .csv

There are 4 datasets which contain detailed information about pizza orders, including specifics about the pizza variants, quantities, pricing, dates, times, and categorization details. The data spans a period of one year, from January 2015 to December 2015.

2. Data structure
Data type : .csv
Tables : 4
Fields : 12
Records : 48,620
Data Span : Jan 2015 - Dec 2015
Source : Maven Analytics
#1 ‘pizzas.csv’ dataset

   rows : 97
   columns : 4

 
   •	pizza_id : A unique identifier linking to a specific name of the pizza. (PK)


   •	pizza_type_id : Links pizza_types dataset. (FK)


   •	size : Represents the size of the pizza (e.g., small, medium, large).


   •	unit_price : The cost of a single unit of the specific pizza variant.
#2 ‘pizza_types.csv’ dataset

   rows :  32 
   columns : 4


   •	pizza_type_id : A unique identifier. (PK)


   •	name : Specifies the name of the specific pizza variant ordered.


   •	Category : Indicates the category of the pizza, such as vegetarian, non-vegetarian, etc.


   •	Ingredients : Provides a list or description of the ingredients used in the pizza.
#3 ‘orders.csv’ dataset

   rows : 21350
   columns : 3


   •	order_id : A unique identifier for each order made, which links to multiple pizzas. (PK)


   •	date : The date when the order was placed.


   •	time : The time when the order was placed
#4 ‘order_details.csv’ dataset

rows : 48620
columns : 4

 
•	order_details_id : unique identifier for all the orders made. (PK)


•	order_id : Links ‘orders’ dataset. (FK)


•	pizza_id : Links ‘pizzas’ dataset. (FK)


•	quantity : The number of units of a specific pizza variant ordered within an order.
3. Data Quality Assessment
The datasets appears to be relatively clean, with no missing values or obvious data errors. However, further exploration may reveal outliers or inconsistencies that need to be addressed during data cleaning.

