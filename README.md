# Pizza_Sales_Analysis_Dashboard

This is a Pizza Sales Analysis Dashboard project, where we leverage SQL for data analysis and Power BI for creating interactive visualizations. This project provides in-depth insights into pizza sales data, including daily and monthly trends, sales by pizza category and size, and identifying top-selling and least_selling pizzas based on revenue, quantity, and total orders.
![PizzaSalesDashboard1](https://github.com/Sushma1134/Pizza_Sales_Analysis_Dashboard/assets/153356425/7b755638-d6c1-481f-aca0-6043742c008a)
![PizzaSalesDashboard2](https://github.com/Sushma1134/Pizza_Sales_Analysis_Dashboard/assets/153356425/8acfb60c-877d-4dd1-bbf7-fb85089bb7d3)


## Data Source:
Pizza_Sales Data: The primary dataset used for the project is the "pizza_sales.csv" file, which contains all the information about Pizzas orders..

## Dataset Overview
The dataset includes the following columns:

- `pizza_id`: Unique identifier for each pizza.
- `order_id`: Unique identifier for each order.
- `pizza_name`: Name of the pizza.
- `quantity`: Number of pizzas ordered.
- `order_date`: Date when the order was placed.
- `order_time`: Timestamp indicating the time of the order.
- `unit_price`: Price per pizza.
- `total_price`: Total revenue generated for each pizza.
- `pizza_size`: Size of the pizza.
- `pizza_category`: Category type of the pizza
- `pizza_ingredients`: Ingredients used in the pizza
- `pizza_name`: Name of the pizza

## Tools 
- SQL Server - Data Analysis is done using MS SQL server.

- Power BI - Creating reports and visualizing the Key Insights.

### Data Cleaning / Preparation
In the initial data preparation phase, we have to perform the following tasks:
1. Data Loading and inspecting the data
2. Remove Unwanted or Unnecessary columns 
3. Data cleaning

## Key Questions Explored
1. **Total Revenue**: Total Revenue generated over the period.
2. **Average Order Value**: Average order value throughout the year.
3. **Total Pizza Sold**: Total number of Pizzas sold.
4. **Total Orders**: Total Orders placed.
5. **Average Pizzas Per Order**: Average Pizzas ordered per order.
6. **Daily Trend for Total Orders**: By days of the week, trend for sales throughout the year.
7. **Monthly Trend for Total Orders**: Monthly Trend for Total Orders to analuze seasonality.
8. **% of Sales by Pizza Category**: Percentage of total sales, each 4 Categories contributes.
9. **% of Sales by Pizza Size**: Percentage of total sales, each of 5 sizes Contributes.
10. **Total Pizzas sold by Pizza Category**: Total Number of Pizzas sold based on Pizza category
11. **Top 5 Best Sellers by Revenue, Total Quantity & Total Orders**: Top 5 Best selling Pizza by Revenue, Total Quantity & Total Orders.
12. **Bottom 5  Sellers by Revenue, Total Quantity & Total Orders**: Bottom 5 selling Pizzas by Revenue, Total Quantity & Total Orders.

### Data Analysis
 
 Data Analysis is done by connecting data from "pizza_sales.csv" to the SQL server and Getting the analytical results, and created PowerBI dashboard of pizza sales and validated both results.

 ### Results 
- Total Revenue generated is 817.86K,Average order Value is 38.31,Total number of pizzas sold are 49574 in the order count of 21350 total orders.It means Average pizzas Per order is around 2.32
- Classic is most selling category where as Chicken is less selling category based on Total Pizzas sold by Category
- Customer prefererring L size (large size) of pizza most.
- Based on No of orders,The Classic Deluxe Pizza is the top selling pizza where as The Brie Carre Pizza is least selling.
- Based on Revenue,The Thai Chicken Pizza is the top selling where as The Brie Carre Pizza is least selling.
- Based on Total Quantity,The Classic Deluxe Pizza is the top selling pizza where as The Brie Carre Pizza is least selling.
- Bussiest days are Fridays and Saturday and Bussiest Months are May and July

