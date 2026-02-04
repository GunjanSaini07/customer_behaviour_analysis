# customer_behaviour_analysis
Data analytics project showcasing customer behaviour analysis using python, SQL and power BI

🔹 Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights about spending patterns, product performance, customer segments, and subscription trends.

The objective is to help businesses make data-driven decisions related to:

-Customer retention

-Discount strategy

-Product positioning

-Revenue growth

-Marketing optimization

The complete workflow includes Python (EDA & cleaning) → PostgreSQL (SQL analysis) → Power BI (dashboard visualization).

🔹 Dataset

Rows: 3,900 transactions

Columns: 18 features

Includes:

-Customer demographics (Age, Gender, Location, Subscription Status)

-Purchase details (Item, Category, Amount, Season, Size, Color)

-Behavior data (Discount, Frequency, Review Rating, Shipping Type)

-Missing values: 37 in Review Rating column 

-Customer Shopping Behavior Anal…

🔹 Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning & EDA
PostgreSQL	SQL analysis
SQLAlchemy	Python–DB connection
Power BI	Dashboard & visualization
Jupyter Notebook	Development

🔹 Project Workflow / Steps
1️⃣ Data Loading (Python)

Imported dataset using Pandas

Checked structure using .info() and .describe()

2️⃣ Data Cleaning

Handled missing values (median imputation by category)

Renamed columns to snake_case

Removed redundant fields (promo_code_used)

3️⃣ Feature Engineering

Created:

age_group (customer segmentation)

purchase_frequency_days

Standardized categorical values

4️⃣ Database Integration

Connected Python to PostgreSQL using SQLAlchemy

Loaded cleaned DataFrame using to_sql()

5️⃣ SQL Analysis

Solved real business questions using SQL:

Revenue by gender

High-spending discount users

Top rated products

Shipping comparison

Subscriber vs non-subscriber spend

Discount dependent products

Customer segmentation (New/Returning/Loyal)

Top 3 products per category

Repeat buyers vs subscriptions

Revenue by age group

6️⃣ Visualization

Built interactive Power BI dashboard

Added KPIs, filters, and category drill-downs

🔹 Dashboard Features (Power BI)

Revenue trends

Customer segments

Top products

Discount impact analysis

Subscription comparison

Category-wise sales

Age group contribution

Interactive slicers allow dynamic business exploration.

🔹 Key Results & Insights

✅ Loyal customers generate highest revenue
✅ Some products depend heavily on discounts
✅ Subscribers spend more on average
✅ Top-rated products align with higher sales
✅ Specific age groups contribute majority revenue
