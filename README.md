# SQL Challenge #2: Pizza Runner 🍕

This repo contains my own SQL solutions for Case Study #2 (Pizza Runner), part of the [8 Week SQL Challenge](https://8weeksqlchallenge.com/case-study-2/) created by Danny Ma. The full problem statement, dataset and questions can be found on the official website.

## About
Danny launched a "Uber Eats for Pizza" concept called Pizza Runner from his home. He hired runners to deliver pizzas and built a basic delivery app, but the data he has collected is messy and needs to be cleaned up before it can be used to answer questions about runner performance, customer experience, ingredient optimisation and pricing.

## 🗂️ Data Model
Six tables are used:
- **runners** — registration dates of delivery runners
- **customer_orders** — pizza orders placed by customers, including exclusions/extras
- **runner_orders** — delivery details for each order (pickup time, distance, duration, cancellations)
- **pizza_names** — names of the two available pizzas
- **pizza_recipes** — standard toppings for each pizza
- **pizza_toppings** — topping ID to topping name mapping

## 🛠️ SQL Techniques Used
- Data Cleaning (handling NULLs, inconsistent strings, data type conversions)
- JOIN (INNER JOIN,LEFT JOIN)
- String manipulation (STRING_SPLIT/STRING_TO_ARRAY, TRIM, REPLACE)
- GROUP BY, aggregate functions (SUM, COUNT, AVG)
- Window Functions
- Subqueries/CTEs
- CASE WHEN
- Temporary tables/table variables for cleaned data
