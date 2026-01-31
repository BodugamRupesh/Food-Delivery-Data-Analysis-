# Food-Delivery-Data-Analysis-

# 🍽 Food Delivery Data Analysis Project  

This project was completed as part of a Hackathon and Internship Selection Process.
The goal was to integrate multiple data sources, analyze them, and generate business insights using Python and Power BI.

# 📂 Datasets Used

This project combines data from three different real-world style systems:

1️⃣ orders.csv (Transactional Data)
Contains order-level information such as:

Order ID

User ID

Restaurant ID

Order Date

Total Amount

2️⃣ users.json (User Master Data)
Contains user details including:

User ID

City

Membership Type (Gold / Regular)

3️⃣ restaurants.sql (Restaurant Master Data)
Contains restaurant-related information:

Restaurant ID

Cuisine Type

Restaurant Rating

⚙️ Tools & Technologies

Python (Pandas, SQLite) – Data processing and merging

Jupyter Notebook – Data analysis workflow

Power BI – Dashboard and visualization

GitHub – Project version control and submission

# 🔄 Project Workflow

🟢 Step 1 — Data Loading
Different file formats (CSV, JSON, SQL) were loaded into Python.

🟢 Step 2 — Data Integration
Datasets were merged using keys:

user_id → Join Orders with Users

restaurant_id → Join Orders with Restaurants

A LEFT JOIN was used to keep all order records.

🟢 Step 3 — Feature Engineering
New time-based features were created:

Month

Quarter

Year

🟢 Step 4 — Final Dataset Creation
All datasets were combined into one master dataset containing:

Order Details

User Information

Restaurant Information

Exported as:

final_food_delivery_dataset.csv

🟢 Step 5 — Business Analysis
Data was analyzed to answer business questions such as:

City-wise revenue performance

Cuisine trends

Membership impact

Rating influence

Seasonal revenue trends

🟢 Step 6 — Dashboard Creation
An interactive dashboard was built in Power BI to visualize insights.

# 📊 Key Insights

Gold members contribute a significant portion of revenue

Higher-rated restaurants generate more sales

Some cuisines have higher average order values

Revenue trends vary by quarter, showing seasonality

# 🎯 Skills Demonstrated

Data Cleaning

Data Integration

SQL Execution

Data Analysis

Business Intelligence

Dashboard Design

📁 Files Included in Repository
📓 Jupyter Notebook (.ipynb)

📊 Final Dataset (final_food_delivery_dataset.csv)

📄 README

# 🚀 Project Outcome

This project demonstrates an end-to-end data analysis workflow — from raw data processing to business insights and dashboard reporting — similar to real-world industry scenarios.

