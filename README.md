# **# Food Delivery Data Analysis using Python**

This project performs end-to-end data integration and analysis on a food delivery dataset. Data from multiple sources (CSV, JSON, SQL) is combined, cleaned, and analyzed to extract business insights such as revenue trends, user behavior, cuisine performance, and membership impact.

-------------------------

**Datasets Used**
File	Type	Purpose
orders.csv	CSV	Order transaction data
users.json	JSON	User master information
restaurants.sql	SQL	Restaurant details (cuisine & ratings)

-------------------------
**ETL Process**

Loaded data from CSV, JSON, and SQL

Converted SQL to CSV using MySQL

Cleaned column names and fixed data types

Merged datasets using LEFT JOIN

Created a unified dataset: final_food_delivery_dataset.csv

---------------------------
**Data Merge Logic**
Join	Key	Type
Orders + Users	user_id	Left Join
Orders + Restaurants	restaurant_id	Left Join

------------------------
**Analysis Performed**
List insights you worked on:

Order trends over time

Revenue by city

Cuisine performance

Membership impact (Gold vs Regular)

User spending behavior

Revenue seasonality

---------------------
**Technologies Used**
Python

Pandas

MySQL Workbench

Jupyter Notebook / VS Code

--------------------
**Skills Demonstrated**
Data Cleaning

Data Integration

ETL Pipeline

Data Analysis

SQL & Pandas

------------------------------
**Outcome**
Built a business-ready dataset and performed analytics to simulate real-world data engineering and decision-making workflows.





