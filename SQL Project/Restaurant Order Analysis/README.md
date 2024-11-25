# Introduction

This project focuses on analyzing eCommerce data using SQL to uncover key business insights. The dataset consists of five dimension tables—customer, item, store, time, and transactions—alongside a fact table that consolidates sales metrics. By leveraging SQL queries, this analysis explores patterns in customer behavior, product performance, store efficiency, and sales trends over time. The goal is to transform raw data into actionable insights that support strategic decision-making in an eCommerce environment.

## Quick Links

[Objective 1 SQL](SQL Project/Restaurant Order Analysis/Objective 1.sql)

[Objective 2 SQL](SQL Project/Restaurant Order Analysis/Objective 2.sql)

[Objective 3 SQL](SQL Project/Restaurant Order Analysis/Objective 3.sql)

## Scenario

I've been hired as a Data Analyst for the Taste of the World Cafe, a restaurant that has diverse menu offerings and serves generous portions. I've been asked to dig into the customers data to see which menu items are doing well / not well and what the top customers seem to like best.

## Objectives

There are three objectives in this project.

### Objective 1

The first objective is to explore the items table, then answer the following questions.

- How many items are on the menu?
  - There are 32 items on the menu.
- WHat are the least and most expensive items on the menu?
  - The least expensive item is Edamame; the most expensive item is Shrimp Scampi.
- How many Italian dishes are on the menu? What are the least and most expensive Italian dishes on the menu?
  - There are 9 Italian dishes on the menu.
  - The least expensive Italian dish is Spaghetti at 14.50; the most expensive Italian dish is Shrimp Scampi at 19.95.
- How many dishes are in each category? What is the average dish price within each category?
  - There are 6 American dishes, 8 Asian dishes, 9 Mexican dishes, and 9 Italian dishes.
  - The average price of American dishes is 10.07; 13.48 for Asian, 11.80 for Mexican, and 16.75 for Italian.

### Objective 2

The second objective is to explore the orders table and answer the following questions using SQL.

- What is the date range of the table?
  - The date range from 2023-01-01 to 2023-03-31.
- How many orders were made within this date range? How many items were ordered within this date range?
  - There are 5370 orders within this date range.
  - There are 12234 items ordered.
- Which orders had the most number of items?
  - Order id 4305, 3473, 1957, 330, 440, 443, and 2675 had the most items ordered.
- How many orders had more than 12 items?
  - 20 orders had more than 12 items.

### Objective 3

The third objective is to analyse customer behaviour. Then complete the following task and answer the following questions.

- Combine the menu item table and order details table.
  - A single table is created using left join to combine the order_details table and menu_items table.
- What were the least and most ordered items? What categories were they in?
  - The most ordered item is Hambuger which belongs to American dish with 622 purchases.
  - The least ordered item is Chicken Tacos which belongs to Mexican dish with 123 purchases.
- What were the top 5 orders that spent the most money?
  - The top 5 orders are 440, 2075, 1957, 330, and 2675.
  - The spending is 192.15, 191.05, 190.10, 189,70, and 185.10 respectively.
- View the details of the hightest spend order. What insights can you gather from the results?
  - Order 440 had 14 items ordered where Italian dishes account for the most, i.e. 8 dishes. It is a good idea to keep and even promote Italian dishes to maximise profit.
- View the details of the top 5 highest spend orders. What insights can you gather from the results?
  - From the result of the query, American and Asian dishes are always to most popular where Mexican dishes are the least popular. Orders with the most spending are always order many Italian dishes. The restaurant may consider reduce the number of Mexican dishes and add more Italian dishes.

## Conclusion

These findings provide valuable insights into potential areas for improvement in the restaurant. For example, they suggest adjusting the menu to highlight American and Asian dishes while reassessing the supply or promotion strategy for Mexican cuisine. Additionally, awareness of the popularity of expensive Italian dishes highlights the potential profitability of retaining these items among the target customers.  

This project demonstrates the transformative power of data analysis in understanding customer behaviour, optimising business operations, and driving strategic decisions.
