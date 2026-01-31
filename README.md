# Food-Delivery-Data-Analysis-

🍽 Food Delivery Data Analysis Project
This project was completed as part of a hackathon and internship selection process. The goal of this project was to combine data from multiple sources, analyze it, and create business insights using Python and Power BI.

📂 Datasets Used
The project uses three different data sources:

orders.csv – Transactional data containing order details

users.json – User information like city and membership

restaurants.sql – Restaurant master data including cuisine and ratings

These datasets simulate real-world systems where data is stored in different formats.

⚙️ Tools & Technologies
Python (Pandas, SQLite)

Jupyter Notebook

Power BI

GitHub

🔄 Project Workflow
Step 1: Data Loading
CSV, JSON, and SQL data were loaded into Python.

Step 2: Data Integration
Datasets were merged using:

user_id to combine orders and users

restaurant_id to combine orders and restaurants

A LEFT JOIN was used to retain all orders.

Step 3: Feature Engineering
New columns like month and quarter were created from the order date.

Step 4: Final Dataset Creation
A single dataset was created containing:

Order details

User information

Restaurant information

This final dataset was exported as:
final_food_delivery_dataset.csv

Step 5: Business Analysis
The dataset was analyzed to understand:

Revenue trends

City performance

Cuisine performance

Gold vs Regular membership behavior

Rating impact

Seasonal patterns

Step 6: Dashboard Creation
An interactive dashboard was built in Power BI to visualize insights.

📊 Key Insights
Gold members contribute a large share of revenue

Certain cuisines have higher average order values

Higher-rated restaurants generate more revenue

Revenue varies across quarters, showing seasonality

🎯 Skills Demonstrated
Data Cleaning

Data Merging

SQL Execution

Data Analysis

Business Intelligence

Dashboard Design

📁 Files in Repository
Jupyter Notebook (.ipynb)

Final dataset (final_food_delivery_dataset.csv)

README

🚀 Outcome
This project shows the complete data analysis workflow from raw data integration to business insights and dashboard visualization, similar to real industry use cases.

