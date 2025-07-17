Query SQL
--1. Write a SQL query that orders the items by price.
SELECT item_id, price
FROM superstore

 
--2. Write your own SQL query that will show a statistic about the item prices,
SELECT SUM(stock_quantity)
FROM price


--3. Write your own SQL query that will show a statistic about the price for items in the category of "Kitchen Supplies".
SELECT SUM(price), category
FROM superstore
GROUP BY category






 




# SQL
