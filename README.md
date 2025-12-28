🛍️ Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights into purchasing patterns, customer segments, product performance, and subscription behavior. The goal is to transform raw consumer data into actionable business insights that support data-driven decision-making in marketing, customer engagement, and revenue optimization.

The analysis combines Python, SQL, and Power BI to deliver an end-to-end analytics solution, from data preparation to visualization and business recommendations.

🎯 Business Problem

Retail organizations often collect large volumes of customer transaction data but struggle to convert it into meaningful insights. The business faces challenges in:

Understanding customer purchasing behavior

Identifying high-value customer segments

Evaluating product and category performance

Measuring the impact of discounts and subscriptions

Improving customer retention and loyalty

Key Business Question

How can the company leverage customer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

📂 Dataset Information

Records: 3,900 transactions

Columns: 18

Data Includes:

Customer demographics (Age, Gender, Subscription Status)

Purchase details (Item, Category, Amount, Season)

Behavioral metrics (Discount Applied, Previous Purchases, Review Rating, Shipping Type)

Data Quality:

37 missing values in the review rating column (handled during preprocessing)

🛠️ Tools & Technologies

Python (Pandas, NumPy) – Data cleaning, preprocessing, feature engineering

PostgreSQL / SQL – Business analysis & querying

Power BI – Interactive dashboard & data visualization

Microsoft Word / PDF – Final analytical report

🔄 Project Workflow
1️⃣ Data Preparation & Feature Engineering (Python)

Cleaned raw data and handled missing values

Standardized column names

Engineered new features such as:

age_group

purchase_frequency_days

Loaded cleaned data into PostgreSQL for analysis

2️⃣ SQL-Based Business Analysis

Key business questions answered using SQL:

Revenue contribution by gender and age group

High-spending customers who used discounts

Top-rated and most purchased products

Subscription vs non-subscription spending behavior

Customer segmentation (New, Returning, Loyal)

Discount dependency across products

📎 All SQL queries are included in the report appendix.

3️⃣ Power BI Dashboard

An interactive Power BI dashboard was built to visualize:

Key KPIs (Total Customers, Avg Purchase Amount, Avg Rating)

Revenue and sales by category

Customer age group analysis

Subscription distribution

Discount usage patterns

📊 The dashboard enables dynamic filtering by:

Gender

Subscription status

Product category

Shipping type

📈 Key Insights

Clothing is the highest revenue-generating category

Young Adult and Middle-Aged customers contribute the most revenue

Non-subscribed customers form the majority, indicating strong subscription growth potential

Discount usage increases purchase frequency but requires margin optimization

Loyal customers generate higher lifetime value

💡 Business Recommendations

Promote subscription plans with exclusive benefits

Implement customer loyalty programs for repeat buyers

Optimize discount strategies to balance growth and profitability

Focus marketing on high-performing categories and age groups

Use data-driven insights for targeted campaigns

📄 Project Deliverables

📊 Power BI Dashboard

📑 Professional Analytics Report (PDF & Word)

🧠 Business Insights & Recommendations

🧾 SQL Queries (Appendix)

🚀 How to Use This Repository

Review the SQL queries to understand the analysis logic

Explore the Power BI dashboard for visual insights

Read the final report for business context and recommendations

📌 Author

Abhijith S

Data Analyst | Business Analytics Enthusiast
