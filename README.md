# E-COMMERCE SALES PERFORMANCE ANALYSIS

## Project Overview
This project provides comprehensive analysis of e-commerce sales data spanning approximately two years (2022-2024). 
The analysis includes exploratory data analysis, statistical insights, and business recommendations.

## Dataset Information
- **Total Records:** 3,500 transactions
- **Time Period:** Jan 2022 - Dec 2024
- **Columns:** 7 (Order Date, Product Name, Category, Region, Quantity, Sales, Profit)
- **Data Quality:** No missing values, clean data

## Analysis Performed

### 1. Exploratory Data Analysis (EDA)
- Data shape and structure validation
- Missing value detection
- Data type conversion and standardization
- Summary statistics

### 2. Sales Analysis
- Total sales revenue and trends
- Product performance ranking
- Regional sales comparison
- Category-wise sales breakdown
- Monthly sales trends

### 3. Profitability Analysis
- Profit margin calculations
- Category profitability comparison
- Region-wise profit analysis
- Profit distribution patterns

### 4. Business Insights
- Top 10 performing products
- Regional performance rankings
- Category contribution to revenue
- Seasonal trends identification
- Correlation analysis

## Key Findings

### Revenue Metrics
- Total Sales: ${df['Sales'].sum():,.2f}
- Total Profit: ${df['Profit'].sum():,.2f}
- Profit Margin: {(df['Profit'].sum()/df['Sales'].sum())*100:.2f}%
- Average Order Value: ${df['Sales'].mean():,.2f}

### Top Performers
- Best Product: {df.groupby('Product_Name')['Sales'].sum().idxmax()}
- Best Region: {df.groupby('Region')['Sales'].sum().idxmax()}
- Most Profitable Category: {df.groupby('Category')['Profit'].sum().idxmax()}

## Visualizations Generated
1. Top 10 Products by Sales
2. Sales by Region
3. Sales by Category
4. Monthly Sales Trend
5. Profit by Category
6. Quantity vs Sales Scatter Plot
7. Profit Distribution by Category (Box Plot)
8. Correlation Heatmap
9. Top 10 Products by Profit
10. Sales by Region & Category (Grouped)
11. Monthly Profit Trend
12. Category Distribution (Pie Chart)

## Technologies Used
- Python 3.x
- Pandas - Data manipulation and analysis
- NumPy - Numerical computations
- Matplotlib - Data visualization
- Seaborn - Statistical data visualization

## Recommendations
1. Focus marketing efforts on top-performing products
2. Expand operations in high-performing regions
3. Optimize inventory for high-profit margin categories
4. Monitor seasonal trends for better planning
5. Investigate underperforming regions for improvement opportunities

## Files Included
- `ecommerce_sales_analysis.ipynb` - Complete Jupyter notebook with analysis
- `analysis_results.csv` - Summary statistics export
- `README.md` - Project documentation

## Author
Nitish Raj | Senior Data Analyst | New Delhi, India
Data Analyst | Python | Pandas | Matplotlib | Seaborn
GitHub: https://github.com/nitish-raj98
Gmail: nnitishraj2016@gmail.com

## Date
July 2026

---
*This project demonstrates proficiency in data analysis, visualization, and business insights generation.*
"""
