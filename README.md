# Amazon E-Commerce Data Analysis

An exploratory data analysis project on a 1-million-row Amazon e-commerce dataset using Python.

## About the Project

The goal of this project is to explore e-commerce data, identify patterns in customer orders and returns, and understand how different factors such as product category, rating, shipping time, and payment method relate to the data.

## Tools & Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

### 01_data_cleaning.ipynb
Data cleaning and preprocessing, including checking data types, missing values, duplicates, and preparing the dataset for analysis.

### 02_EDA.ipynb
Exploratory Data Analysis using Pandas to investigate different patterns and relationships in the dataset.

### 03_visualization.ipynb
Data visualization using Matplotlib and Seaborn to present important findings from the analysis.

## Analysis Performed

Some of the questions explored in this project include:

- How are products distributed across categories?
- What is the distribution of payment methods?
- What is the return rate for each product category?
- Does product rating relate to return rate?
- Does shipping time relate to return rate?
- How are products distributed across subcategories?

## Key Findings

- Product categories are almost evenly distributed in the dataset.
- Payment method usage is also almost evenly distributed.
- Return rates are relatively similar across product categories.
- Products with below-average ratings have a noticeably higher return rate.
- Return rates remain relatively stable for 1–5 day shipping but increase noticeably for 6-day shipping.

## Conclusion

The analysis identified several patterns in the e-commerce dataset, particularly around product ratings, shipping time, and product returns. The results provide useful areas for further investigation and can serve as a foundation for a future machine learning model to predict product returns.

## Skills Practiced

- Data cleaning
- Exploratory data analysis
- Data aggregation with Pandas
- Data visualization
- Statistical interpretation
- Writing analytical insights
