**ZEPTO SQL DATA ANALYSIS PROJECT**

This is a hands-on SQL portfolio project based on an e-commerce inventory dataset scraped from Zepto, one of India’s popular quick-commerce platforms.

The project is designed to show how a data analyst actually works — starting from raw data, understanding it, cleaning it, and finally answering business questions using SQL.

This project start raw data, then understanding it, then cleaning it, and finally answering business questions using SQL.


**GOAL OF THIS PROJECT**

- Create and understand a messy e-commerce inventory table

- Exploring the data through EDA to understand product categories, stock status, and pricing issues

- Cleaning the data by handling null values, removing incorrect records, and converting prices from paise to rupees

- Writing business-focused SQL queries to analyze pricing, inventory levels, stock availability, revenue, and related insights


**ABOUT DATASET**

Columns in the Dataset

sku_id – unique ID for each product entry

name – product name

category – product category (Fruits, Snacks, Beverages, etc.)

mrp – original price (converted from paise to ₹)

discountPercent – discount applied

discountedSellingPrice – final price after discount (₹)

availableQuantity – stock available

weightInGms – product weight in grams

outOfStock – shows whether the product is out of stock

quantity – number of units per package

**PROJECT STEPS**
1. Database & Table Creation

A PostgreSQL table is created with proper data types to store product data.

2. Data Import

The dataset was imported into PostgreSQL using the Import/Export option available in pgAdmin.
During import, encoding issues were fixed by saving the file in UTF-8 format.

3. Data Exploration (EDA)

Basic checks were done to understand the data:

total number of records

sample rows

null values in columns

list of product categories

in-stock vs out-of-stock products

products appearing multiple times

4. Data Cleaning

Common data issues were fixed:

removed rows where price values were zero

converted prices from paise to rupees

5. Business Analysis

I written SQL queries to answer questions like:-

- Which products give the highest discounts

- Expensive products that are currently out of stock

- Estimated revenue by category

- High-price products with very low discounts

- Categories with the highest average discounts

- Price per gram to find value-for-money products

- Grouping products by weight (Low, Medium, Bulk)

- Total inventory weight per category










