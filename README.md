📊 Customer Behaviour Analysis
Data Analytics Project | Python • SQL • Power BI
🔹 Overview

This project analyzes retail customer transaction data to uncover insights into shopping behavior, spending patterns, product performance, and customer segments.

The goal is to help businesses make data-driven decisions that improve:

Customer retention

Discount strategies

Product positioning

Revenue growth

Marketing optimization

The complete workflow follows:

Python (Cleaning & EDA) → PostgreSQL (SQL Analysis) → Power BI (Visualization)

🔹 Dataset

📌 Rows: 3,900 transactions

📌 Columns: 18 features

Includes:

Customer demographics

Age, Gender, Location, Subscription Status

Purchase details

Item, Category, Amount, Season, Size, Color

Behavior metrics

Discount usage, Purchase frequency, Review rating, Shipping type

Data issues handled

37 missing values in Review Rating

🔹 Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning & EDA
PostgreSQL	SQL analysis
SQLAlchemy	Python–Database connection
Power BI	Dashboard & visualization
Jupyter Notebook	Development
🔹 Project Workflow
1️⃣ Data Loading

Imported dataset using Pandas

Inspected structure using .info() and .describe()

2️⃣ Data Cleaning

Handled missing values using median imputation by category

Renamed columns to snake_case

Removed redundant fields (promo_code_used)

3️⃣ Feature Engineering

Created:

age_group → customer segmentation

purchase_frequency_days

Standardized categorical values

4️⃣ Database Integration

Connected Python to PostgreSQL using SQLAlchemy

Loaded cleaned data using to_sql()

5️⃣ SQL Analysis

Solved real business questions using:

CTEs

Window functions

Aggregations

Examples:

Revenue by gender

High-spending discount users

Top-rated products

Subscriber vs non-subscriber spend

Discount-dependent products

Customer segmentation (New/Returning/Loyal)

Top 3 products per category

Revenue by age group

6️⃣ Visualization

Built an interactive Power BI dashboard

Added KPIs, filters, slicers, and drill-down analysis

🔹 Dashboard Features (Power BI)

Revenue trends

Customer segmentation

Top products

Discount impact analysis

Subscription comparison

Category-wise sales

Age group contribution

Interactive slicers for dynamic exploration

🔹 Key Results & Insights

✅ Loyal customers generate the highest revenue
✅ Subscribers spend more on average
✅ Some products heavily depend on discounts
✅ Higher-rated products correlate with higher sales
✅ Specific age groups contribute the majority of revenue

🔹 Skills Demonstrated

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

SQL Query Writing (CTEs, Joins, Window Functions)

PostgreSQL Integration

Feature Engineering

Dashboard Design (Power BI)

Business Insight Generation

Data Storytelling

🔹 Project Structure
customer_behaviour_analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
├── screenshots/
└── README.md
🔹 How to Run
1. Clone repository
git clone <repo-link>
2. Install dependencies
pip install pandas numpy sqlalchemy psycopg2
3. Run notebook

Open Jupyter Notebook and execute the analysis.

4. Open Power BI

Load the .pbix file to view the dashboard.

🔹 Author

Gunjan Saini
Aspiring Data Analyst
SQL • Python • Power BI
