# Supply-Chain-Data-Analysis
This project implements a relational database design and analytics pipeline in MySQL to analyze supply chain performance across products, sales, inventory, suppliers, and logistics.It demonstrates database normalization and advanced SQL queries to generate business insights on revenue, inventory turnover, supplier quality, logistics efficiency, and profitability.

# Database Design
Created a Supply Chain database with 5 normalized tables:

Products → Product details (SKU, type, price)

Sales → Units sold, revenue, customer demographics

Inventory → Availability, stock levels, order quantities

Suppliers → Supplier details, costs, defect rates, inspection results

Logistics → Shipping costs, routes, carriers, lead times

# Key Business Insights
Revenue & Sales Analysis
Total revenue by product type with highest average revenue per sale.
Identified top 10 products by revenue per unit sold.
Sales distribution across customer demographics.

Inventory & Operations
Ranked products by units sold with performance flags (above/below average).
Calculated conversion rate (sales vs. availability).
Measured inventory turnover ratio, flagged slow-moving products.
Identified stockout risks (stock < 10% of order quantity).

Supplier Performance
Ranked suppliers by defect rate and inspection results.
Calculated manufacturing cost per unit & flagged costly suppliers.
Built a supplier performance score (production, defect rate, lead time).
Analyzed supplier dependency risk by location (high vs. low concentration).

Logistics & Cost Efficiency
Average lead & shipping times by transportation mode.
Shipping cost per unit across carriers & products.
Delivery risk analysis → flagged high-risk routes (delivery > 30 days).
Ranked routes by efficiency score (cost vs. time).

Profitability
Calculated supply chain cost vs. revenue per product.
Derived profit margin % to identify most profitable products.
Linked demographics → product type → supplier quality to measure impact.

# Tools & Skills Used
MySQL (DDL, DML, Joins, CTEs, Subqueries, Window Functions)
Business Intelligence (KPI tracking: revenue, profit margin, inventory turnover, defect rate)
Data Analytics (Cost optimization, supplier evaluation, logistics efficiency)

# Key Contributions
Designed and implemented end-to-end relational database for supply chain analysis.
Developed 25+ advanced SQL queries for insights on revenue, inventory, suppliers, logistics, and profit margins.
Delivered a comprehensive framework for monitoring supply chain efficiency and risks.





