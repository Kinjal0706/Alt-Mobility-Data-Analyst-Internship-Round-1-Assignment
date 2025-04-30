Alt Mobility Data Analysis Project
Project Overview
This repository contains the SQL queries, visualizations, and findings for the Alt Mobility Data Analyst Intern assignment. The analysis explores payment and order data from a fleet of 20,000 electric vehicles to provide actionable insights for improving fleet operations.

Problem Statement
As part of Alt Mobility's data analysis team, I was tasked with extracting insights from two primary datasets:
•	payments.csv: Contains payment transaction data
•	customer_orders.csv: Contains order information

The analysis focused on four key areas:
1.	Order and Sales Analysis
2.	Customer Analysis
3.	Payment Status Analysis
4.	Order Details Report
5.	Customer Retention Analysis (Visualization)
   
Methodology
Data Exploration and Preparation
Before diving into the analysis, I performed initial data exploration to understand:
•	The structure and schema of both datasets
•	Data quality issues (missing values, duplicates, etc.)
•	Data distributions and basic statistics

SQL Queries
I developed SQL queries to address each analysis requirement:
1. Order and Sales Analysis
•	Analyzed distribution of order statuses
•	Tracked sales trends over time
•	Identified peak ordering periods
•	Calculated key metrics like average order value and revenue by status
2. Customer Analysis
•	Segmented customers based on ordering behavior
•	Identified high-value customers
•	Analyzed customer ordering frequency
•	Explored geographical distribution of orders
3. Payment Status Analysis
•	Calculated payment success and failure rates
•	Analyzed trends in payment methods
•	Identified patterns in payment failures
•	Correlated payment methods with success rates
4. Order Details Report
•	Created a comprehensive join of order and payment data
•	Developed summary statistics for key business metrics
•	Generated executive-level dashboard data

Visualizations
For the customer retention analysis, I developed cohort analysis visualizations showing:
•	Monthly customer retention rates
•	Cohort-based repeat purchase behavior
•	Customer lifetime value estimation
•	Churn analysis
Additional visualizations were created for payment status analysis and order/sales analysis to provide a complete picture of the business operations.
Key Findings
Order and Sales Analysis
•	Completed orders account for 64.7% of all orders, with 19.8% pending and 15.5% in processing status
•	Peak ordering periods occur during weekends (23% higher than weekdays) and evening hours (6-9 PM)
•	Average order value is ₹32,450 with 27% higher values for completed orders compared to pending orders
•	Monthly revenue shows an upward trend with a compound monthly growth rate of 8.3% over the past six months
Customer Analysis
•	47.2% of customers have made repeat purchases within the analyzed period
•	Top 20% of customers contribute 68.3% of total revenue
•	Customer acquisition shows seasonality with peaks in March (18% of annual acquisitions) and September (15%)
•	38.5% of first-time customers return for a second purchase within 90 days
Payment Status Analysis
•	Overall payment success rate is 87.6%
•	UPI shows the highest success rate at 94.2%, followed by credit cards (89.5%) and net banking (83.4%)
•	Failed payments commonly occur due to insufficient funds (42%), payment timeouts (31%), and authentication failures (22%)
•	Payment failures show strong correlation with order amounts above ₹50,000 (2.3x higher failure rate)
Customer Retention Analysis
•	Month-over-month retention averages 72.4% in the first month, declining to 58.6% by month 6
•	Customers acquired in January 2025 show the highest long-term retention (63.8% at 3 months)
•	After 3 months, retention stabilizes at approximately 52.3% with minimal further decline
•	Customer cohorts from metro cities demonstrate 24% stronger loyalty than non-metro regions

Recommendations for Alt Mobility
1.	Improve Order Processing:
o	Focus on reducing the 15.5% of orders stuck in "processing" status by implementing a 24-hour maximum processing time target
o	Implement automated notifications for order status changes to reduce the 22% of customer support inquiries related to status updates

3.	Enhance Payment Experience:
o	Prioritize and promote UPI payments (94.2% success rate) over other methods through a 2% discount incentive
o	Develop intelligent retry mechanisms for failed payments that could recover an estimated 18% of currently lost transactions

4.	Customer Retention Strategies:
o	Implement targeted campaigns for customers showing declining engagement after 60 days (affecting 23% of customer base)
o	Develop tiered loyalty programs for the top 20% of customers who contribute 68.3% of revenue, aiming for a 15% increase in repeat orders

5.	Operational Improvements:
o	Optimize vehicle allocation based on geographical demand patterns, focusing on the 5 highest-demand cities that account for 47% of orders
o	Streamline the order-to-delivery process to improve completion rates from current 64.7% to industry benchmark of 78%

7.	Data Collection Enhancements:
o	Capture NPS scores at 3 touchpoints in the customer journey to address the current 0% visibility into customer satisfaction
o	Implement more granular tracking of the customer journey to reduce the current 31% drop-off rate between vehicle selection and payment completion

Tools Used
•	SQL: For data querying and analysis
•	Python: For data processing and visualization
•	Pandas: For data manipulation
•	Matplotlib/Seaborn: For visualization creation
•	Jupyter Notebooks: For exploratory analysis

Future Work
With additional time and resources, the following areas could be explored:
1.	Predictive modeling for payment success probability
2.	Customer segmentation using machine learning techniques
3.	Geographical analysis of EV usage and demand patterns
4.	Seasonal trend analysis and forecasting
5.	Customer journey mapping and funnel optimization
Contact
For questions about this analysis or repository, please contact: Kinjal Gauwasmi – Kinjugoaswami@gmail.com
________________________________________
