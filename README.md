# SQL Analysis of Dominos Pizza
PPT link: [Dominos pizza SQL analysis.pptx](https://github.com/user-attachments/files/17894235/Dominos.pizza.SQL.analysis.pptx)

# Explanation of the Datasets

I have been working with four datasets from Domino's Pizza to analyze their business operations. These datasets are as follows:

## Order Details Table:
Contains details of each order, including:
- order_details_type: Type of order details.
- order_id: Unique identifier for the order.
- pizza_id: Identifier linking to the specific pizza.
- quantity: Number of pizzas ordered.

## Orders Table:
Tracks overall orders with:
- order_id: Unique identifier for orders.
- order_date: Date of the order.
- order_time: Time of the order.

## Pizza Types Table:
Provides descriptive details about the pizzas:
- pizza_types_id: Unique identifier for pizza types.
- name: Name of the pizza.
- category: Classification of pizzas (EX- classic, chicken pizza).
- ingredients: List of ingredients used.

## Pizzas Table:
Contains detailed information about pizzas:
- pizza_id: Unique pizza identifier.
- pizza_type_id: Links to the pizza type.
- size: Size of the pizza (e.g., S, M, L).
- price: Cost of the pizza.
# Steps I Followed to Clean and Analyze the Datasets

## Data Cleaning:
- Using the order_id, pizza_id, and pizza_type_id foreign keys, I made sure that every table was correctly linked.
- I looked for inconsistent or missing data, such as null values in important fields like price or quantity.
- To guarantee uniformity for analysis, I standardized text fields such as pizza names and classifications.

Analyzing Data:
- I found important metrics that would aid in comprehending revenue generation, consumer preferences, and sales patterns.
- To compute these metrics, I made sure to join the pertinent tables correctly using SQL queries.
- Patterns like the popularity of various pizza sizes or the distribution of orders by time were depicted by myself.
# Explanation of SQL Queries and Their Importance
## Total Number of Orders Placed:

SQL Query

![image](https://github.com/user-attachments/assets/cd8ee2e1-b517-4824-b5d1-3ad19f42d039)

Result: 21,350 orders placed.
- Importance: I identified the overall scale of the business operations, which helps in benchmarking monthly or yearly growth.

## Total Revenue Generated from Pizza Sales:

SQL Query

![image](https://github.com/user-attachments/assets/cac975ff-eda1-455a-b717-0b3392f65d3c)

Result: $817,860.05.
- Importance: I calculated the total revenue generated, which is crucial for financial analysis and profitability tracking.

## Top 5 Most Expensive Pizzas:

SQL Query

![image](https://github.com/user-attachments/assets/9c71d465-1753-4a80-9ef1-50732e48c57a)

Result: The Greek Pizza ($35.95) is the most expensive.
- Importance: I identified high-value products that could be promoted to maximize profits.

## Most Ordered Pizza Size:

SQL Query

![image](https://github.com/user-attachments/assets/85b71d86-c17e-4046-af58-984cf0730ad8)

Result: Large pizzas are the most ordered (18,526 orders).
- Importance: This insight helps me and the business prioritize inventory and pricing strategies for large pizzas.

## Top 5 Most Ordered Pizza Types:

SQL Query

![image](https://github.com/user-attachments/assets/a20f5041-de71-48de-b1dd-a7ad9d995a60)

Result: The Classic Deluxe Pizza is the most ordered (2,453 orders).
- Importance: I identified customer favorites, guiding marketing and menu decisions.

## Total Quantity Ordered by Category:

SQL Query

![image](https://github.com/user-attachments/assets/5860f374-c189-4824-8aae-35553701b7e3)

Result: The Classic category generated the most revenue ($220,053).
- Importance: I analyzed category performance, helping in promotional and pricing strategies.

## Distribution of Orders by Hour:

SQL Query

![image](https://github.com/user-attachments/assets/45e2c41e-0637-44ec-9fe3-5d34ac37036f)

Result: Peak order times are 12:00 PM–1:00 PM and 6:00 PM–7:00 PM.
- Importance: I identified peak hours, aiding in staffing and operational planning.

## Average Number of Pizzas Ordered per Day:

SQL Query

![image](https://github.com/user-attachments/assets/c45323fb-4f9d-46dc-9e60-0ed5ec5af64b)

Result: 138 pizzas/day.
- Importance: I established daily demand, critical for inventory and resource management.

## Top 3 Revenue-Generating Pizzas:

SQL Query

![image](https://github.com/user-attachments/assets/e15f0a62-de69-43c3-bd23-aa959d82899f)

Result: Thai Chicken Pizza is the top revenue generator ($220,053).
- Importance: I identified which pizzas to promote for revenue maximization.

## Pizza Category Contribution to Revenue:

SQL Query

![image](https://github.com/user-attachments/assets/abeac412-2c45-4c09-a0d0-7507395b1933)

Result: Classic pizzas contribute 26.91% to revenue.
Importance: I provided a detailed revenue breakdown by category for strategic planning.

## Cumulative Revenue Over Time:

SQL Query

![image](https://github.com/user-attachments/assets/26a7dff3-683f-4454-9f1b-3947687f1445)

Result: Revenue trends over time.
- Importance: I tracked performance growth, helping with forecasting.

## Top 3 Ordered Pizza Types by Category Based on Revenue:

SQL Query

![image](https://github.com/user-attachments/assets/c46457f4-f317-40a0-8950-287045816001)

Result: Thai Chicken Pizza is the top in the Chicken category.
- Importance: I helped refine marketing strategies by highlighting category-specific leaders.

# Impact of SQL Analysis on the buniness
- Provided actionable insights into sales trends, customer preferences, and revenue performance.
- Identified peak order hours, high-revenue items, and popular pizza categories.
- Enabled optimization of operations, inventory management, and marketing strategies.
- Supported sustainable business growth through data-driven decision-making.
- Enhanced customer satisfaction by aligning offerings with customer preferences.
