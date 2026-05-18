Customer Shopping Behavior Analysis
Overview

This project analyzes customer shopping behavior using transactional retail data. The workflow covers data cleaning and exploratory data analysis (EDA) in Python, SQL-based business analysis, and dashboard creation in Power BI. A professional presentation and report were also created using Gamma and Power BI visuals.

The objective of the project is to uncover insights related to:

Customer spending patterns
Product preferences
Subscription behavior
Shipping trends
Customer segmentation
Dataset
Rows: 3,900
Columns: 18
Dataset Type: Retail Customer Shopping Data
Features Included
Customer demographics (Age, Gender, Location)
Purchase details (Category, Item Purchased, Purchase Amount)
Shopping behavior (Discount Applied, Shipping Type, Subscription Status)
Product feedback (Review Rating)
Tools & Technologies
Python
Pandas
NumPy
SQL / MySQL
Power BI
Jupyter Notebook
Gamma
Project Steps
1. Data Cleaning & Preparation (Python)
Loaded dataset using Pandas
Handled missing values in review ratings
Standardized column names
Created new features:
age_group
purchase_frequency_days
Removed redundant columns
2. Exploratory Data Analysis (EDA)

Performed analysis on:

Revenue trends
Product categories
Customer demographics
Ratings and subscriptions
Discount usage
3. SQL Analysis

Used SQL queries to answer business questions such as:

Revenue by gender
Top-rated products
Customer segmentation
Repeat buyers analysis
Shipping type comparison
Revenue by age group
4. Power BI Dashboard

Built an interactive dashboard with:

KPI Cards
Revenue visualizations
Subscription analysis
Category performance
Age group analysis
Interactive slicers
5. Reporting & Presentation
Created project report documentation
Designed presentation slides in Gamma
Added business recommendations and insights
Dashboard Features
KPIs
Total Customers
Average Purchase Amount
Average Review Rating
Visuals
Revenue by Category
Revenue by Age Group
Subscription Distribution
Sales by Category
Customer Segmentation
Filters
Gender
Category
Shipping Type
Subscription Status
Key Results
Male customers generated higher total revenue
Express shipping users spent slightly more on average
Loyal customers formed the largest customer segment
Certain products showed high discount dependency
Young adults contributed the highest revenue
Business Recommendations
Promote subscription benefits
Implement loyalty reward programs
Optimize discount strategy
Focus marketing on high-revenue segments
Highlight top-rated products in campaigns
How to Run the Project
Python
Open Jupyter Notebook
Install required libraries:
pip install pandas numpy sqlalchemy pymysql
Run the notebook cells step-by-step
SQL
Create database in MySQL/PostgreSQL
Import cleaned dataset
Run SQL queries for analysis
Power BI
Open Power BI Desktop
Load the cleaned CSV dataset
Create visuals and dashboard
Publish/export dashboard if needed
Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
├── report/
├── presentation/
└── README.md

