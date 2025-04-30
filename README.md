Alt Mobility Data Analysis Project
Project Overview
This repository contains the SQL queries, visualizations, and findings for the Alt Mobility Data Analyst Intern assignment. The analysis explores payment and order data to provide insights into order fulfillment, revenue trends, customer behavior, and payment processing.
Dataset Description
The analysis is based on two primary datasets:
1.	payments.csv: Contains payment transaction data including payment IDs, payment dates, amounts, methods, and status.
2.	customer_orders.csv: Contains order information including order IDs, customer IDs, order dates, amounts, shipping addresses, and status.
Approach
1. Data Exploration and Preparation
•	Verified data structure and checked for any quality issues
•	Identified relationships between datasets (mainly through order_id)
•	Prepared SQL queries to extract meaningful insights
2. Order and Sales Analysis
•	Analyzed the distribution of order statuses
•	Identified monthly sales trends
•	Examined average order values across different order statuses
•	Analyzed order patterns by day of the week
3. Customer Analysis
•	Determined customer ordering frequencies
•	Segmented customers based on purchase behavior
•	Analyzed average order values by customer segment
•	Calculated the time between orders for repeat customers
4. Payment Status Analysis
•	Examined overall payment status distribution
•	Analyzed payment success rates by payment method
•	Tracked monthly payment success rates
•	Identified patterns in failed payments based on order amount
5. Order Details Report
•	Created a comprehensive order details report
•	Analyzed order fulfillment times
•	Identified payment discrepancies
•	Performed aging analysis on pending orders
6. Customer Retention Analysis
•	Established customer cohorts based on first purchase month
•	Tracked customer activity over subsequent months
•	Calculated retention rates for different cohorts
Visualization Approach
For the customer retention visualization (Task 5), I created a cohort analysis heatmap that shows:
•	Customer cohorts along the y-axis (grouped by month of first purchase)
•	Months since first purchase along the x-axis
•	Color intensity representing retention rate
•	Actual retention percentages displayed in each cell
The visualization clearly demonstrates how well Alt Mobility retains customers from each cohort over time, allowing the company to:
•	Identify which cohorts have the highest retention rates
•	Spot trends in customer retention over time
•	Determine critical points where customer churn increases
Repository Structure
•	SQL_Queries.sql: Contains all SQL queries used for analysis
•	README.md: This file explaining the approach and findings
•	Visualizations/: Directory containing visualization images
•	Summary_of_Findings.pdf: Concise summary of key findings and recommendations
Tools Used
•	SQL for data analysis
•	Python/Tableau for visualization (specify which one you're using)
•	GitHub for version control and documentation

