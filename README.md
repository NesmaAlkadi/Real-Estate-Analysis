# Real-Estate-Analysis

House-Prices-Analysis-PowerBI

🎯 Objective
Analyze and visualize residential house prices using Python and Power BI to uncover:

Price drivers and key influencing factors

Impact of property features on market value

Neighborhood-based price differences

Business-ready insights for decision-making

📊 Overview
This project demonstrates an end-to-end data analytics workflow, starting from data cleaning and exploratory analysis in Python to building interactive and insightful Power BI dashboards.

Based on the Ames Housing dataset (Kaggle)

Focused on understanding housing market behavior through business-oriented visuals

⚙️ Process

1. 🧹 Data Cleaning

Removed duplicate records

Dropped columns with more than 20% missing values

Handled missing values using:

Median for numerical features

Mode for categorical features

Converted data types (numerical vs categorical)

Standardized and cleaned categorical values

Identified and handled outliers using the IQR method

Renamed columns for clarity and business readability

2. 🧩 Data Analysis & Modeling

Performed exploratory data analysis (EDA) to understand distributions and patterns

Analyzed outliers while preserving valuable market information

Prepared clean, analysis-ready data for Power BI

3. 📈 Visualization

Built interactive Power BI dashboards

Created DAX measures and KPIs

Designed dashboards focused on business storytelling

🧠 Tools & Features

Python (Pandas, NumPy) – Data cleaning & EDA

Power BI – Data modeling, DAX & dashboards

Power BI DAX – KPIs & calculated measures

Interactive Filters – Dynamic data exploration

🔍 Key Insights

💵 Market Overview

Newer homes tend to sell at higher prices

Remodeled homes command a pricing premium

Build quality has a strong positive relationship with sale price

🏘 Price Drivers

Premium neighborhoods such as NoRidge and NridgHt achieve the highest prices

Living area increases price, but very large homes show diminishing returns

Single-family homes outperform duplexes and condos

Higher quality homes consistently command higher prices

🏠 Interior Layout & Space

Prices increase with more bedrooms up to a point, then flatten

Full bathrooms add more value than half bathrooms

Above-ground living area is a key driver of home value

🏁 Conclusion
This project highlights how Python and Power BI can be combined to deliver a complete analytics solution:

From raw data cleaning and EDA

To business-ready Power BI dashboards

With insights that support smarter real-estate decisions
