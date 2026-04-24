# Data-Driven-Consumer-Insights-Platform
📊 Customer Shopping Behavior Analysis

📌 Project Overview
This project analyzes customer shopping behavior using a dataset of 3,900 transactions across multiple product categories. The goal is to uncover patterns in customer spending, preferences, and engagement to support data-driven business decisions.

The project combines Python (EDA), SQL (analysis), and Power BI (visualization) to generate actionable insights.


🎯 Objectives
Analyze customer purchasing behavior across demographics
Identify key drivers such as discounts, reviews, and subscriptions
Segment customers based on loyalty and purchase frequency
Evaluate product performance and category trends
Provide actionable business recommendations


📂 Data Overview
Rows: 3,900
Columns: 18
Key Features:
Customer Info: Age, Gender, Location, Subscription Status
Purchase Details: Item, Category, Purchase Amount, Season, Size, Color
Behavioral Data: Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type
Data Cleaning:
Handled missing values in Review Rating using median imputation
Removed redundant column (promo_code_used)
Standardized column names to snake_case


🛠️ Tech Stack
Python: Pandas, NumPy (Data Cleaning & EDA)
SQL (PostgreSQL): Data Analysis & Querying
Power BI: Dashboard & Visualization
GitHub: Version Control & Documentation


🧱 Data Model Overview

The dataset is structured as a single transactional table (customer), where each row represents a purchase.

Key Columns:
customer_id
age, gender, location
item_purchased, category
purchase_amount
subscription_status
review_rating
shipping_type
discount_applied
previous_purchases
Engineered Features:
age_group → Customer segmentation
purchase_frequency_days → Standardized frequency


📊 Dashboard Preview

Dashboard Highlights:
KPI Cards: Avg Purchase, Total Customers, Avg Rating
Revenue by Category
Sales Distribution
Subscription Breakdown
Revenue by Age Group

<img width="972" height="648" alt="Screenshot 2026-04-24 114619" src="https://github.com/user-attachments/assets/aed4d49a-fe04-4126-8e35-ac3f36b46c7b" />


📈 Key Insights
Male customers generate higher revenue than female customers
Customers using discounts often spend above average
Express shipping users spend more, indicating premium behavior
Majority of customers are loyal (repeat buyers)
Young adults contribute the highest revenue
Subscription base is smaller but consistent
Some products (e.g., hats, sneakers) are highly discount-driven


💡 Recommendations
1.Target young adults and loyal customers for marketing campaigns
2. Optimize discount strategies for high-performing products
3. Convert repeat buyers into subscribers with incentives
4. Promote express shipping for premium users
5. Invest in acquiring new customers
