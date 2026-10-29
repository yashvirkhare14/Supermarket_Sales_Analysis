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
Seven questions were explored using simple Python code and graphs:
1. What is the distribution of total sales?
— Histogram
<img width="500" height="373" alt="Screenshot 2026-10-29 132614" src="https://github.com/user-attachments/assets/12d2b7a2-8fb8-4eb3-92b2-124c4304a39d" />

#### Analysis
- The average transaction total is about 322.97.
- The median transaction total is about 253.85.
- The highest transaction total is 1042.65, which is much higher than the average.
#### Conclusion:
Most transaction totals are in the lower and middle ranges, while fewer transactions have high totals.

2. How is unit price related to total sales?
— Scatter plot
<img width="500" height="380" alt="Screenshot 2026-10-29 132638" src="https://github.com/user-attachments/assets/4ff7afaf-e5f6-4965-874e-1cc64eec6e53" />

#### Analysis
- Unit price and Total have a positive relationship.
- Transactions with a higher unit price often have a higher total amount.
#### Conclusion:
Unit price is one factor related to the total sales amount.

3. How does quantity affect total sales?
— Scatter plot
<img width="470" height="382" alt="Screenshot 2026-10-29 132657" src="https://github.com/user-attachments/assets/8a76e9e3-2b31-48e1-85b4-5288616fd4b7" />

#### Analysis
- Quantity and Total have a positive relationship.
- Transactions with more items often have a higher total amount.
#### Conclusion: 
The number of items purchased is strongly related to the total sales amount.

4. Which product line has the highest average total sales?
— Bar plot
<img width="460" height="305" alt="Screenshot 2026-10-29 132723" src="https://github.com/user-attachments/assets/a7267d18-a263-4dee-8523-0634e8e127d6" />

#### Analysis
- Home and lifestyle has the highest average transaction total, about 336.64.
- Fashion accessories has the lowest average transaction total, about 305.09.
#### Conclusion: 
Average transaction totals differ across product lines.

5. How does total sales vary across cities?
— Box plot
<img width="423" height="362" alt="Screenshot 2026-10-29 132739" src="https://github.com/user-attachments/assets/62b37c3c-5e82-433c-adb9-2cf553bea0da" />

#### Analysis
- Naypyitaw has the highest average transaction total, about 337.10.
- Yangon has the lowest average transaction total, about 312.35.
- The box plot compares the spread of transaction totals in each city.
#### Conclusion:
Transaction totals vary between the three cities.

6. Does customer type relate to total sales?
— Bar plot
<img width="417" height="388" alt="Screenshot 2026-10-29 132755" src="https://github.com/user-attachments/assets/b18d9095-6b2c-409e-b8dc-4b0989212b8a" />

#### Analysis
- Members have an average transaction total of about 327.79.
- Normal customers have an average transaction total of about 318.12.
#### Conclusion:
Average transaction totals are slightly higher for members than for normal customers in this dataset.

7. What is the correlation between total sales and other numerical features?
— Heatmap
<img width="405" height="363" alt="Screenshot 2026-10-29 132812" src="https://github.com/user-attachments/assets/c9936660-dd3e-4efc-a9e6-4685d6f666b4" />

#### Analysis
- Quantity has a positive correlation of about 0.71 with Total.
- Unit price has a positive correlation of about 0.63 with Total.
- Rating has a very weak relationship with Total (correlation: -0.04).
#### Conclusion:
Quantity and unit price are more closely related to total sales than customer rating.

Each question includes a graph, a short analysis, and a conclusion.

### 4️⃣ Data Visualization Dashboard
- The graphs are used together to compare transaction totals across different features.
- The dashboard section summarizes the main findings from the analysis.

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
