# 🛒 Supermarket_Sales_Analysis
A simple data analysis project using Python

## 📌 Project Overview
- This project studies supermarket sales data to understand which factors are related to the total amount paid in each transaction.
- It uses basic data cleaning, statistics, and graphs to find useful information about sales.
- The results can help compare sales by product line, city, and customer type.

## 🎯 Project Objectives
- Load and understand the supermarket sales data.
- Check missing values and duplicate rows.
- Explore the relationship between Total and other columns.
- Create graphs using Matplotlib and Seaborn.
- Find simple business insights from the results.

## 🛠️ Skills & Tools Used
- Python
- Pandas
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib
- Seaborn
- Business Insights

## 📂 Dataset Information
- Dataset Name: Supermarket Sales Dataset
- Records: 1,000
- Features: 17
- Target Variable: Total
#### Key Attributes
- Unit Price: Price of one product.
- Quantity: Number of products purchased.
- Product Line: Type of product purchased.
- City: City where the supermarket is located.
- Customer Type: Shows whether the customer is a Member or Normal customer.

## 🔍 Project Workflow
### 1️⃣ Data Loading and Understanding
- Loaded the dataset using Pandas.
- Checked the number of rows and columns.
- Reviewed column names, data types, and basic statistics

### 2️⃣ Data Cleaning Process
- Checked each column for missing values.
- Checked for duplicate rows.
- Changed the Date column to date format.
- The dataset has no missing values or duplicate rows, so no rows needed to be filled or removed.

### 3️⃣ Exploratory Data Analysis (EDA)
Used different graphs to explore the dataset and understand its main patterns:
1. Histogram
2. Scatter plot
3. Bar plot
4. Box plot
5. Heatmap

### 4️⃣ Data Visualization Dashboard
- The graphs are used together to compare transaction totals across different features.
- The dashboard section summarizes the main findings from the analysis.
- Dashbord
<img width="800" height="1200" alt="00_visualization_dashboard" src="https://github.com/user-attachments/assets/9e7b4003-7211-4215-827e-3d2e72054835" />


## 📊 Key Insights
1. The average transaction total is about 322.97.
2. Transactions with higher unit prices often have higher total amounts.
3. Transactions with more items usually have higher total amounts.
4. Home and lifestyle has the highest average transaction total, about 336.64.
5. Naypyitaw has the highest average transaction total among the three cities, about 337.10.
6. Member transactions have a slightly higher average total, about 327.79, than Normal customer transactions, about 318.12.
7. Quantity and unit price have a stronger relationship with Total than customer rating does.

## 💡 Business Insights
- Pay attention to product prices and the number of items purchased when studying transaction totals.
- Compare product lines and cities to understand differences in average transaction amounts.
- Member transactions have a slightly higher average total in this dataset, so customer type can be useful for comparison.

## ✅ Final Conclusion
This project used basic data cleaning, statistics, and seven graphs to study supermarket sales. The results show that unit price and quantity are closely related to the total amount paid. The graphs also help compare transaction totals across product lines, cities, and customer types.
