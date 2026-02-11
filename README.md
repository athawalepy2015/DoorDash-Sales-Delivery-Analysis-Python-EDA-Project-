DoorDash Sales and Analytics Project

Welcome to the DoorDash Sales and Analytics Project repository! 🚀
This project demonstrates a comprehensive data analytics solution, from exploring raw order data to generating actionable business insights. Designed as a portfolio project, it highlights practical data analysis techniques used in food delivery platforms.

🏗️ Data Architecture

The data architecture for this project follows a simple analytics pipeline inspired by real-world BI workflows:

Raw Data → Cleaned Data → KPI Layer → Visual Analytics

Raw Layer:
Stores the original order-level dataset containing state, city, restaurant, dish, price, and ratings.

Processed Layer:
Includes data cleansing, validation, and transformation steps to prepare the dataset for analysis.

Analytics Layer:
Contains aggregated metrics and KPIs used for reporting and visualizations.

📖 Project Overview

This project involves:

Data Exploration
Importing and inspecting raw order-level data.

Data Cleaning
Handling data types, missing values, and inconsistencies.

KPI Development
Calculating core business metrics such as total sales, average rating, and order value.

Analytics & Visualization
Building trend charts and regional performance analysis to generate insights.

🚀 Project Requirements
Building the Analytics Solution (Data Analysis)
Objective

Analyze DoorDash-style order data using Python to generate insights into sales performance, customer satisfaction, and regional trends.

Specifications

Data Source

Single transactional dataset in Excel format

Contains 100,000 order-level records

Data Quality

Validate column data types

Ensure numeric fields are properly formatted

Check for missing or inconsistent values

Integration

Convert order dates into time-based dimensions

Aggregate data by month, week, state, and city

Scope

Focus on exploratory data analysis (EDA)

No historical data warehousing required

Documentation

Define clear KPIs

Provide structured analysis steps

Include charts and business insights

📊 Key Performance Indicators (KPIs)

Total Sales – Overall revenue generated from orders

Average Rating – Customer satisfaction level

Average Order Value (AOV) – Revenue per order

Ratings Count – Total number of customer reviews

Total Orders – Number of orders received

📈 Visual Analytics

The project includes the following charts:

Monthly Sales Trend

Daily Sales Trend

Total Sales by Food Category

Total Sales by State

Quarterly Performance Summary

Top 5 Cities by Sales

Weekly Trend Analysis

🧰 Tools & Technologies

Python

Pandas – Data processing

NumPy – Numerical operations

Matplotlib – Visualizations

Plotly – Interactive charts

Jupyter Notebook
