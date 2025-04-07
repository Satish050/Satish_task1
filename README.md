# Satish_task1
Cleaned Customer Personality Analysis
# Customer Personality Analysis - Data Cleaning

## Overview
This project involves cleaning the Customer Personality Analysis dataset from Kaggle.

## Dataset Used
- Source: https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

## Cleaning Steps Performed
- Removed duplicate records
- Renamed columns to lowercase and snake_case format
- Handled missing values by dropping rows with nulls
- Converted date column (Dt_Customer) to proper datetime format
- Standardized categorical text fields like Marital_Status, Education
- Verified and fixed data types of numeric columns
- Created a new column children by summing Kidhome and Teenhome

## Output
- Cleaned dataset: cleaned_customer_personality.csv

## Tools Used
- Python
- Pandas

## IDE Used
- Juptyer Note Book
