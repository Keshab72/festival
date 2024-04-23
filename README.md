# Exploratory Data Analysis of Festival Data

## Introduction
In this project, we conducted an exploratory data analysis (EDA) of the Festival Data, which contains information about customers, their purchases, and demographic details. The dataset was analyzed to gain insights into customer behavior, preferences, and trends.

## Dataset Overview
The dataset contains the following columns:
- User_ID: Unique identifier for each user
- Cust_name: Name of the customer
- Product_ID: Unique identifier for each product
- Gender: Gender of the customer (M: Male, F: Female)
- Age Group: Age group of the customer
- Age: Age of the customer
- Marital_Status: Marital status of the customer (0: Single, 1: Married)
- State: State of the customer
- Zone: Zone of the customer
- Occupation: Occupation of the customer
- Product_Category: Category of the purchased product
- Orders: Number of orders placed by the customer
- Amount: Amount spent by the customer

## Data Cleaning
- Checked for missing values and dropped rows with null values.
- Converted the 'Amount' column from float to integer data type to remove decimal values.

## Exploratory Data Analysis
1. **Gender Analysis**:
   - Count of people for each gender was visualized using a countplot.
   - Amount spent by each gender was analyzed, showing that females spent more than males.

2. **Age Group Analysis**:
   - Count of people in each age group based on gender was visualized using a countplot.
   - Most sales were analyzed based on age group, indicating the highest sales from customers aged 26-35.

3. **State-wise Analysis**:
   - Total sales by state were visualized, highlighting the states with the highest sales.

4. **Marital Status Analysis**:
   - Married status of customers based on gender and sales was visualized.

5. **Occupation Analysis**:
   - Count of people based on occupation was visualized.
   - Sales of products based on occupation were analyzed, showing the occupations with the highest sales.

6. **Product Category Analysis**:
   - Count of orders for each product category was visualized.
   - Top 10 product categories sold were analyzed based on sales.

7. **Product ID Analysis**:
   - Count of orders for each product ID was visualized to identify the top-selling products.

## Conclusion
Based on the analysis, it can be concluded that married women aged 26-35 years from states like Uttar Pradesh, Maharashtra, and Karnataka, working in industries such as IT, healthcare, and aviation, are likely to purchase products related to food, clothing, electronics, and gadgets during festivals.

## Repository Details
- The dataset used for analysis is named "Festival Data.csv".
- The code for data analysis is provided in both PDF and CSV formats.

This project provides valuable insights into customer behavior and preferences, which can be utilized for targeted marketing strategies and product recommendations during festivals.
