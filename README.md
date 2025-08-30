# SerbaMart Performance Analysis: Sales, Shipping & Customer Profitability

1. Title: Identifying sales drivers, fixing delivery bottlenecks, and unlocking customer value
  - This project analyzes sales, shipping, and customer data from a retail superstore to uncover product performance, delivery efficiency, and customer purchasing behavior. The goal is to identify the products driving sales, the shipping methods causing delays, and the customer segments contributing most to profitability. These insights can support management in improving fulfillment processes, optimizing sales strategies, and enhancing customer satisfaction.

2. Scoping Your Data Analysis Project

- Big questions:
  - Which products bring in the most sales?
  - Are certain shipping methods causing more delivery delays?
  - Are there regional trends in shipping delays?
  - Which customer segments are the most profitable for the business?
  - How do sales vary by states and over time?

- What are the datasets and data columns that you will be exploring?
  - orders.csv: Order ID, Order Date, Shipping ID, Customer ID, Product Category ID, Sales, Profit
  - product.csv: Product Category ID, Category, Sub-Category
  - customers.csv: Customer ID, Segment
  - shipping.csv: Shipping ID, Ship Mode, Courier, Delivery Timing, State

- What relationships between the data columns will you be exploring?
  - Product Category vs Sales - To identify the top-selling category and sub-category
  - Shipping Method vs Delivery Timing - To compare how different shipping methods and couriers perform
  - State vs Delivery Timing: To understand whether shipping delays are concentrated in specific geographic states.
  - Customer Segment vs Profitability: To assess which segments (Consumer, Corporate, Home Office) generate the highest profit contribution.
  - State vs Sales Trends: To observe how sales vary over time and across states (whether certain states show consistent growth or seasonal spikes).
