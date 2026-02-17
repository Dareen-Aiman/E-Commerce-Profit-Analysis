## 📊 E-Commerce Profit Analysis (500K+ Transactions)

##🎯 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on a massive e-commerce dataset. The goal is to transform raw transaction logs into actionable business stories, identifying profitability drivers and consumer behavior patterns.

##🛠️ Tech Stack
Language: 
Python 3.x.
Libraries: Pandas (Data Wrangling), Seaborn & Matplotlib (Visualization), NumPy.
Tools: Jupyter Notebook, Git/GitHub.

##📊 Dataset Information
The primary dataset used in this analysis contains over 500,000 rows of transaction data. Due to GitHub's file size limitations, the raw CSV file is not included in this repository.
Raw Data Source: You can find the original dataset on Kaggle - E-Commerce Data https://www.kaggle.com/datasets/carrie1/ecommerce-data 
Data Description: Real-world transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based online retail store.

##⚙️ Data Processing & Engineering
To ensure high data quality, the following steps were performed in the [E_Commerce_Profitability_Analysis.ipynb notebook:](https://colab.research.google.com/github/Dareen-Aiman/E-Commerce-Profit-Analysis/blob/main/E_Commerce_Profitability_Analysis.ipynb)
Cleaning: Removed rows with missing CustomerID and handled negative Quantity values (representing returns) to ensure data integrity.
Transformation: Converted InvoiceDate to a proper datetime format for time-series analysis.
Feature Engineering: Created Sales and Profit columns to move beyond basic counts into deep financial analysis.

##📈 Key Insights
Top Performers: Identified the "Top 5 Best Selling Products" (e.g., Paper Craft, Little Birdie) to optimize inventory levels.
Trend Analysis: Spotted seasonal patterns that inform marketing and stock replenishment strategies.

