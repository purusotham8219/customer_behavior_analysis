# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using transactional retail data. The workflow covers data cleaning and exploratory data analysis (EDA) in Python, SQL-based business analysis, and dashboard creation in Power BI. A professional presentation and report were also created using Gamma and Power BI visuals.

The objective of the project is to uncover insights related to:

* Customer spending patterns
* Product preferences
* Subscription behavior
* Shipping trends
* Customer segmentation

# Dataset

* **Rows:** 3,900
* **Columns:** 18
* **Dataset Type:** Retail Customer Shopping Data

### Features Included

* Customer demographics (Age, Gender, Location)
* Purchase details (Category, Item Purchased, Purchase Amount)
* Shopping behavior (Discount Applied, Shipping Type, Subscription Status)
* Product feedback (Review Rating)


# Tools & Technologies

* Python
* Pandas
* NumPy
* SQL / MySQL
* Power BI
* Jupyter Notebook
* Gamma

# Project Steps

## 1. Data Cleaning & Preparation (Python)

* Loaded dataset using Pandas
* Handled missing values in review ratings
* Standardized column names
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant columns

## 2. Exploratory Data Analysis (EDA)

Performed analysis on:

* Revenue trends
* Product categories
* Customer demographics
* Ratings and subscriptions
* Discount usage

## 3. SQL Analysis

Used SQL queries to answer business questions such as:

* Revenue by gender
* Top-rated products
* Customer segmentation
* Repeat buyers analysis
* Shipping type comparison
* Revenue by age group

## 4. Power BI Dashboard

Built an interactive dashboard with:

* KPI Cards
* Revenue visualizations
* Subscription analysis
* Category performance
* Age group analysis
* Interactive slicers

## 5. Reporting & Presentation

* Created project report documentation
* Designed presentation slides in Gamma
* Added business recommendations and insights

# Dashboard Features

### KPIs

* Total Customers
* Average Purchase Amount
* Average Review Rating

### Visuals

* Revenue by Category
* Revenue by Age Group
* Subscription Distribution
* Sales by Category
* Customer Segmentation

### Filters

* Gender
* Category
* Shipping Type
* Subscription Status

# Key Results

* Male customers generated higher total revenue
* Express shipping users spent slightly more on average
* Loyal customers formed the largest customer segment
* Certain products showed high discount dependency
* Young adults contributed the highest revenue

# Business Recommendations

* Promote subscription benefits
* Implement loyalty reward programs
* Optimize discount strategy
* Focus marketing on high-revenue segments
* Highlight top-rated products in campaigns


# How to Run the Project

## Python

1. Open Jupyter Notebook
2. Install required libraries:

```bash
pip install pandas numpy sqlalchemy pymysql

3. Run the notebook cells step-by-step


## SQL

1. Create database in MySQL/PostgreSQL
2. Import cleaned dataset
3. Run SQL queries for analysis

## Power BI

1. Open Power BI Desktop
2. Load the cleaned CSV dataset
3. Create visuals and dashboard
4. Publish/export dashboard if needed

# Project Structure

```bash
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
├── report/
├── presentation/
└── README.md

## Conclusion

This project successfully analyzed customer shopping behavior using Python, SQL, and Power BI to uncover meaningful business insights from 3,900 retail transactions. Through data cleaning, exploratory analysis, SQL-based querying, and interactive dashboard development, the project identified trends in customer spending, subscription behavior, product preferences, shipping patterns, and customer segments.

The analysis revealed that loyal customers contributed the majority of purchases, non-subscribers generated higher total revenue, and certain product categories consistently performed better in terms of sales and ratings. Discount usage and shipping preferences also showed measurable impacts on customer spending behavior.

By combining data analytics techniques with business-focused visualization, this project demonstrates how retail organizations can use data-driven decision-making to improve customer engagement, optimize marketing strategies, and increase overall business performance.

 
