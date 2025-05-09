# 📚 Amazon Sales Intelligence: From EDA to Business Solutions

# 🚀 Project Overview #

This project focuses on performing an Exploratory Data Analysis (EDA) and solving critical business problems using a dataset of 50,000+ rows. By analyzing the data from various interconnected tables, I aim to uncover insights, detect anomalies, and provide actionable solutions to optimize business processes for Amazon's operations. 🛒

# 🛠️ Technologies Used #
- PostgreSQL: Used for database querying and analysis.
- SQL: Wrote advanced queries for data exploration and problem-solving.
- Power Query: ETL (Extract, Transform, Load) for Power BI integration and new measures calculation.
- Power BI 📊: Interactive dashboards for data visualization and reporting.
# 💡 What Makes This Project Unique? #
-Real-World Problems: Tackles realistic challenges faced in large-scale e-commerce operations.
-Scalable Dataset: Demonstrates the ability to handle large datasets effectively.
-Actionable Insights: Provides data-driven recommendations to optimize key business processes.
-Interactive Dashboard: Features an attractive and interactive dashboard design, making it easier to demonstrate and explore insights efficiently.
-Detailed Power BI Analysis: Connected all SQL queries to Power BI and designed a 6-page interactive dashboard:
 -Overview: Highlights key metrics like total revenue, sales, profit, and trends.
 -Sales: Focuses on trends, target vs. actual sales, and category contribution.
 -Customer: Analyzes customer behavior, retention, and segmentation.
 -Product: Details product performance, profit margins, and return percentages.
 -Logistics: Provides insights into shipping delays, inventory, and delivery metrics.
 -Insights: Consolidates high-level metrics like successful orders, inactive sellers, and payment breakdowns.

# 🔑 Objectives #

# 🎯 Primary Goals:
- Data Exploration: Understand the structure and relationships of data across multiple tables.
- Data Quality Checks: Ensure data consistency, accuracy, and completeness.
- Insight Generation: Extract key metrics like revenue, profit, sales trends, and customer behavior.
- Problem-Solving: Solve critical business issues through SQL-based analysis.

# 💼 Business Problems Solved 

🔍 1. Data Overview & Quality Checks 🧹
- Explored all tables to understand their structure and content.
- Checked for missing values, duplicate primary keys, and foreign key mismatches.
- Ensured data integrity across interconnected tables.

📦 2. Inventory Management 🚛
- Problem: Real-time stock updates after sales and returns.
- Automated stock reduction in the inventory after a sale.
- Automated inventory updates when products are returned.

💰 3. Revenue Forecasting 📈
- Problem: Predict next quarter's revenue based on historical trends.
- Calculated average monthly revenue from the previous quarter.
- Projected revenue for the next quarter.

🛒 4. Dynamic Pricing Adjustments 💸
- Problem: Optimize pricing based on sales performance.
- Increased prices by 10% for products with high demand (>500 units sold).
- Reduced prices by 5% for slow-moving products (<100 units sold).

📊 5. Profit Analysis 💹
- Problem: Monthly profit tracking for each product.
- Automated monthly profit calculations (sales revenue - COGS).
- Stored results in a dedicated monthly_profit table.

📝 6. Comprehensive Sales Reporting 📃
- Problem: Generate detailed sales reports.
- Quarterly sales report for each seller, summarizing:
- Total Revenue
- Total Orders
- Top-Selling Products

🧐 7. Anomaly Detection 🚨
- Detected products with unusually high or low prices (outliers).
- Identified orders with missing shipping or payment information.

📈 8. Trend Analysis 📆
- Analyzed monthly sales trends and state-wise customer distribution.
- Detected changes in customer behavior and sales growth over time.

🤝 9. Customer Insights 👤
- Segmented customers into Returning and New based on return frequencies.
- Analyzed top customers in each state and their total spend.
- Suggested cross-sell opportunities (e.g., customers who purchased Product A but not Product B).

📊 Dataset Details
The dataset consists of 50,000+ rows spread across multiple tables:

- Category: Contains details about product categories.
- Customers: Information about Amazon's customers, including names, states, and addresses.
- Sellers: Data about sellers and their origin.
- Products: Product details, including price, cost, and category.
- Orders: Records of customer orders with dates and statuses.
- Order_items: Information on products ordered, quantities, and prices.
- Payments: Payment statuses and details for each order.
- Shipping: Shipping details, including providers and delivery status.
- Inventory: Stock details for each product and warehouse information.

⚙️ Steps Followed

🛠️ Exploratory Data Analysis (EDA):
- Data Overview: Displayed all records and key statistics for initial understanding.
- Data Quality Checks: Validated data consistency and resolved anomalies.
- Descriptive Statistics: Computed metrics like average price, order quantity, and revenue.
- Relationship Exploration: Explored key relationships between tables (e.g., customers, orders, and products).
- Trends Analysis: Analyzed trends over time, monthly revenue, and customer segmentation.
- Anomalies and Outliers: Detected and flagged unusual data points.
- Visualization Preparation: Prepared summarized data for graphical representation.

🚀 Key Highlights
- 📂 Dataset Scale: Analyzed over 50,000+ rows across multiple interconnected tables.
- 🧮 Complex Queries: Wrote advanced SQL queries involving joins, subqueries, and window functions.
- 🔄 Automation: Automated inventory updates for sales and returns.
- 📈 Insights Delivered: Provided actionable business insights for revenue growth, pricing strategies, and customer retention.
- 🛠️ Problem-Solving: Addressed real-world business problems, improving operational efficiency.

📌 Future Scope
- Advanced Machine Learning: Build predictive models for sales forecasting and customer segmentation.
- Deeper Analysis: Explore additional dimensions like regional sales performance or seasonality.
