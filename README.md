E-Commerce Transactions Data Visualization (R)

Name: SHIMAL AYMAN
Roll No: 23BAD112

📌 Project Overview

This project performs exploratory data analysis (EDA) and visualization on an e-commerce transactions dataset using R. The analysis focuses on understanding transaction amount distributions and monthly sales trends across different product categories.

The visualizations help identify:

Spending patterns

Outliers in transaction amounts

Monthly sales intensity by product category

🛠 Tools & Libraries Used

R Programming Language

ggplot2 – for data visualization

dplyr – for data manipulation

lubridate – for date handling

📂 Dataset

File Name: 2.ecommerce_transactions.csv

Key Columns Used:

Transaction_Date – Date of purchase

Transaction_Amount – Amount spent per transaction

Product_Category – Category of the product purchased

⚠️ Ensure the CSV file is placed in the working directory before running the script.

🔄 Data Preprocessing Steps

Load required libraries.

Read the CSV file into R.

Convert Transaction_Date into Date format.

Handle missing values while summarizing sales data.

📈 Visualizations Generated
1️⃣ Histogram of Transaction Amounts

Displays the frequency distribution of transaction amounts.

Helps identify common spending ranges and skewness.

2️⃣ Boxplot of Transaction Amounts

Shows the median, quartiles, and outliers.

Useful for detecting extreme transaction values.

3️⃣ Heatmap of Monthly Sales Intensity

Aggregates total sales by Product Category and Month.

Color intensity represents total sales volume.

Helps compare seasonal trends across categories.

▶️ How to Run the Code

Open RStudio.

Set the working directory where the CSV file is stored.

Copy and paste the R script into the script editor.

Run the script line by line or click Run.

Visualizations will appear in the Plots panel.

✅ Expected Output

A histogram showing transaction amount distribution

A boxplot highlighting transaction spread and outliers

A heatmap visualizing monthly sales patterns

📌 Conclusion

This project demonstrates how R can be effectively used for:

Data cleaning

Exploratory analysis

Professional-quality visualizations

Such analysis is useful for business insights, sales forecasting, and decision-making in e-commerce systems.
