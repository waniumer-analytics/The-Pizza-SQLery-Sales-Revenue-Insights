                                    The-Pizza-SQLery-Sales-Revenue-Insights
                                            
                                         Domain :- SALES
                                            
This project is a complete end-to-end SQL case study analyzing pizza sales performance using real-world business questions.
It uncovers total orders, revenue patterns, top-performing pizzas, customer preferences, and advanced category-level insights, helping businesses optimize menu strategy and boost profitability.

                                             Project Features

* 13 business-driven SQL questions
* Clean, modular SQL scripts
* Revenue analysis, cumulative trends, category insights
* SQL joins, window functions, aggregates
* Beginner-friendly + interview-ready
* PDF project report included

                                              SQL Concepts Used

1. Joins (INNER JOIN)
2. GROUP BY, ORDER BY
3. Aggregations (SUM, COUNT, AVG)
4. Window Functions (RANK, SUM OVER)
5. Subqueries
6. CTEs
7. Percentage calculations
8. Date & time functions

                                             Business Questions Answered

1. Retrieve the total number of orders
2. Calculate total revenue from sales
3. Identify the highest-priced pizza
4. Find the most common pizza size
5. Top 5 most ordered pizza types
6. Category-wise total quantity ordered
7. Hourly distribution of orders
8. Category-wise pizza distribution
9. Average pizzas ordered per day
10. Top 3 pizzas based on revenue
11. Percentage revenue contribution
12. Cumulative revenue trend
13. Top 3 pizzas by category based on revenue


                                       Example Query (Total Revenue)
SELECT 
    ROUND(SUM(order_details.quantity * pizzas.price), 1) AS Total_Sales
FROM order_details
JOIN pizzas 
    ON pizzas.pizza_id = order_details.pizza_id;

                                           Key Insights 

1. Total Orders: 21,350+
2. Total Revenue: ₹817,860
3. Most ordered size: Large (L)
4. Bestselling pizza (quantity): Classic Deluxe Pizza
5. Highest revenue pizza: Thai Chicken Pizza
6. Top category: Classic
7. Average pizzas/day: 138
8. Peak order hours: 12 PM – 8 PM

                                                 Tech Stack

1. SQL (MySQL )
2.Excel / CSV for dataset
3. GitHub for version control

                                                       Author

Wani Umer — Data Analytics.
www.linkedin.com/in/waniumer-analytics.





