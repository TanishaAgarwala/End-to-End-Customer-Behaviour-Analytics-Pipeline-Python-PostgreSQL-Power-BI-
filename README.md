# Customer-Behaviour-Analytics-Pipeline-Python-PostgreSQL-Power-BI-

Customer behaviour analytics project is about analyzing 3,900 retail transactions using Python for data cleaning, PostgreSQL for business analysis, and Power BI for interactive dashboards to uncover spending patterns, customer segmentation, and revenue drivers.

This project analyzes customer shopping behavior using 3,900 retail transactions to uncover insights about purchasing patterns, product performance, discount effectiveness, and customer loyalty.

The project demonstrates an end-to-end analytics workflow using:

Python → Data Cleaning  
PostgreSQL → Business Analysis using SQL  
Power BI → Interactive Dashboard

## Project Architecture

Raw Dataset  
↓  
Python Data Cleaning (Pandas)  
↓  
Data Ingestion Pipeline (SQLAlchemy)  
↓  
PostgreSQL Database  
↓  
SQL Business Analysis  
↓  
Power BI Dashboard Visualization

## Dataset Overview

The dataset contains 3,900 retail transactions with 18 attributes describing customer demographics, purchase details, and shopping behavior.
Key features include:

- Age
- Gender
- Location
- Product Category
- Purchase Amount
- Discount Applied
- Previous Purchases
- Review Rating
- Shipping Type

  ## Data Cleaning (Python)

Data preprocessing was performed using Python (Pandas) in Jupyter Notebook.

Steps included:

- Handling missing values in the review_rating column
- Standardizing column names to snake_case
- Creating new features such as age_group
- Removing redundant columns (promo_code_used)
- Preparing the dataset for SQL analysis

  ## SQL Business Analysis

PostgreSQL was used to answer key business questions such as:

- Revenue contribution by customer segments
- Impact of discounts on average order value
- Subscription behavior across customer loyalty groups
- Top performing product categories
- Revenue distribution across age groups

- ## Key Insights

- Non-discounted purchases generated 57% of total revenue, while discounted purchases generated 43%.
- Subscription adoption increases slightly with customer loyalty.
-The top 35% of customers generate around 50% of total revenue, indicating moderate revenue concentration.
- Revenue distribution across age groups is relatively balanced.
- Certain products within categories dominate revenue, such as Jewelry and Sunglasses in Accessories.

## Power BI Dashboard

An interactive Power BI dashboard was created to visualize customer behavior insights.

Key dashboard metrics include:

- Total Revenue
- Total Customers
- Average Purchase Amount
- Average Review Rating

Visualizations include:

- Revenue by Category
- Revenue by Age Group
- Subscription Distribution
- Sales by Age Group
  
 <img width="883" height="480" alt="Customer_behaviour_analysis" src="https://github.com/user-attachments/assets/804bda0c-d635-4142-bb51-3c11e63547ca" />

## Technologies Used

Python  
Pandas  
PostgreSQL  
SQLAlchemy  
Power BI  
DAX

## Author

Tanisha Agarwala
