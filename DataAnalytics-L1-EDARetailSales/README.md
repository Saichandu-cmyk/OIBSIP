
# Exploratory Data Analysis on Retail Sales Data

## Oasis Infobyte Internship – Data Analytics

**Name:** Kalimera Sai Chandu  
**Track:** Data Analytics  
**Task:** Task 1 – Exploratory Data Analysis on Retail Sales Data

## Project Objective

The objective of this project is to perform exploratory data analysis on retail sales data and identify useful patterns in sales performance and customer characteristics.

## Dataset

The dataset contains 1,000 retail transactions across 9 columns, including:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Analysis Performed

- Dataset structure and data quality analysis
- Descriptive statistics
- Monthly sales trends
- Quarterly sales trends
- Customer age-group analysis
- Gender analysis
- Revenue by product category
- Quantity sold by product category
- Correlation analysis
- Correlation heatmap
- Age-group sales analysis
- Average transaction value by category
- Top 10 highest-value transactions

## Key Findings

1. The dataset contains 1,000 transactions with no duplicate rows.
2. The 46–55 age group recorded the highest number of transactions, with 229 transactions.
3. Female transactions were slightly higher than male transactions, with 510 compared with 490.
4. Electronics generated the highest total revenue at 156,905.
5. Clothing had the highest quantity sold, with 894 units.
6. Beauty had the highest average transaction value.
7. May 2023 recorded the highest monthly sales at 53,150.
8. Q4 2023 recorded the highest sales among the complete quarters at 126,190.
9. Price per Unit had a strong positive correlation with Total Amount, with a correlation coefficient of 0.85.
10. The 46–55 age group recorded the highest transaction activity and total sales.

## Business Recommendations

1. Focus marketing campaigns on the 46–55 customer segment.
2. Give additional promotional attention to Electronics because it generated the highest total revenue.
3. Use monthly and quarterly sales trends to improve inventory planning and promotional timing.
4. Consider bundles, cross-selling, and promotional offers for Clothing to increase average transaction value.
5. Collect product-level information such as Product Name to enable more detailed product performance analysis.

## Data Limitation

The dataset does not contain an individual Product Name column. Therefore, a true Top 10 best-selling product analysis cannot be performed at the individual product level without introducing unsupported information.

Instead, product performance was analyzed using Product Category, and the notebook includes the Top 10 highest-value transactions as an additional analysis.

## Project File

The complete analysis is available in:

`EDA_Retail_Sales.ipynb`
