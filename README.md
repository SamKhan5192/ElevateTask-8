# ElevateTask-8
Simple Sales Dashboard Design

# Superstore Sales Dashboard Project

## Dataset Overview

This project uses the **Superstore_Sales.csv** dataset, which contains historical sales data for a retail company. The dataset includes information such as order dates, sales figures, product categories, regions, and profit.

## Key Columns:
- **Order Date**: Date the order was placed
- **Region**: The geographical area where the order was delivered (e.g., East, West, Central, South)
- **Category**: Product category (e.g., Furniture, Office Supplies, Technology)
- **Sales**: Total sales amount for the order
- **Profit**: Net profit for the order

---

## Project Objective

To build a **Power BI dashboard** that visualizes trends and patterns in sales data and helps stakeholders make informed decisions based on:

- Monthly sales performance
- Regional performance
- Category-wise sales contribution

## Tools Used

- **Power BI**: For creating the interactive dashboard
- **Python + Pandas**: For data cleaning and preprocessing
- **CSV File**: Superstore_Sales.csv

---

## Data Cleaning Steps (in Python)

1. Loaded the dataset using `pandas`.
2. Converted `Order Date` to datetime format.
3. Created a new column `Month-Year` for monthly trend analysis.
4. Removed missing values and duplicates.
5. Saved the cleaned dataset.

## Dashboard Components (Power BI)

1. **Line Chart**: Sales over time (Month-Year)
2. **Bar Chart**: Sales by Region
3. **Donut Chart**: Sales by Category
4. **Slicer**: Filter data by Region & Category

## Key Insights

1. **The West region** had the highest sales consistently.
2. **Technology** was the top-selling product category across all regions.
3. **Sales dipped during mid-year months**, showing seasonal fluctuations.
