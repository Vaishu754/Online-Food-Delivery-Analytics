# Online Food Delivery Analytics

## Project Overview

This project analyzes online food delivery data to understand sales performance, customer orders, food category performance, city-wise performance, and order status.

The project uses Python for data cleaning and exploratory data analysis and Power BI for interactive dashboard visualization.

## Problem Statement

The objective of this project is to analyze online food delivery data and identify important business trends and patterns.

The analysis focuses on:

- Sales performance
- City-wise sales
- Food category performance
- Monthly sales trends
- Order status
- Customer ratings
- Payment methods

The insights from the analysis can help businesses improve sales performance and make data-driven decisions.

## Dataset Description

The dataset is a synthetic online food delivery dataset containing 3,010 records before duplicate removal and 3,000 unique orders after cleaning.

The dataset contains the following columns:

- Order_ID
- Order_Date
- Customer_ID
- City
- Restaurant
- Food_Category
- Quantity
- Price
- Discount
- Delivery_Fee
- Payment_Method
- Order_Status
- Rating
- Total_Amount

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI
- Git
- GitHub

## Data Cleaning Process

The following data preparation steps were performed:

1. Inspected the dataset structure and data types.
2. Checked for missing values.
3. Identified missing values in Payment_Method and Rating.
4. Checked for duplicate records.
5. Removed 10 duplicate records.
6. Checked for incorrect Quantity values.
7. Checked for negative Price values.
8. Converted Order_Date into datetime format.
9. Created the Total_Sales column using Quantity × Price.

## Exploratory Data Analysis

The following EDA techniques were performed:

- Descriptive statistics
- Data inspection
- Missing-value analysis
- Duplicate detection
- Data validation
- City-wise sales analysis
- Food category sales analysis
- Restaurant-wise sales analysis
- Monthly sales analysis
- Correlation analysis
- Outlier detection

### Key EDA Findings

- Bengaluru recorded the highest total sales among the cities.
- Pizza was the highest-selling food category, followed closely by Biryani.
- May recorded the highest monthly sales.
- Most orders were successfully delivered.
- The average customer rating was 4.09 out of 5.

## Data Visualizations

The project includes visualizations for:

- Monthly Sales Trend
- Sales by City
- Sales by Food Category
- Order Status Distribution
- Payment Method Distribution
- Total Sales Outlier Analysis

These visualizations help communicate important trends and relationships in the dataset.

## Power BI Dashboard

An interactive Power BI dashboard was created with:

- Total Sales KPI
- Total Orders KPI
- Average Rating KPI
- Monthly Total Sales Trend
- Total Sales by City
- Total Sales by Food Category
- Order Status Distribution
- City slicer
- Food Category slicer

The dashboard provides an interactive view of the major business metrics and findings.

## Key Business Insights

1. Bengaluru generated the highest total sales among all cities.
2. Pizza generated the highest sales among the food categories.
3. Biryani was also one of the strongest-performing food categories.
4. May recorded the highest monthly sales.
5. Delivered orders represented approximately 87.91% of all orders.
6. The average customer rating was 4.09 out of 5.

## Business Recommendations

1. Focus promotional campaigns on high-performing categories such as Pizza and Biryani.
2. Strengthen marketing and restaurant partnerships in high-performing cities such as Bengaluru.
3. Introduce targeted offers during lower-sales months to improve sales consistency.

## Conclusion

This project demonstrates an end-to-end data analytics workflow, starting from dataset preparation and data cleaning to exploratory data analysis, visualization, and interactive Power BI reporting.

The analysis provides useful insights into sales, customer orders, food categories, cities, and order performance. These insights can support data-driven business decisions and help improve sales and customer experience.

## Project Structure

```text
Online-Food-Delivery-Analytics
│
├── dataset
│   └── online_food_delivery_synthetic_dataset.csv
│
├── notebooks
│   └── Food_delivery_system.ipynb
│
├── powerbi
│   └── Power BI Dashboard
│
├── presentation
│   └── Project Presentation
│
├── python
│   └── Python Analysis Files
│
├── report
│   └── Project Report
│
├── visualizations
│   └── Project Visualizations
│
├── .gitignore
└── README.md

Author

Vaishnavi