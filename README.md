# DA_Task4
# Retail Sales Analysis: Data Storytelling & Statistical Validation

## Project Overview

This project focuses on transforming raw retail sales data into meaningful business insights through Data Storytelling and Statistical Validation. The analysis identifies key revenue drivers, customer purchasing behavior, regional performance, and category-wise sales trends to support data-driven decision-making.

---

## Business Objective

The primary objective of this project is to:

- Analyze retail sales performance.
- Identify top-performing product categories and regions.
- Understand customer purchasing patterns.
- Validate business insights using statistical testing.
- Provide actionable recommendations for business growth.

---

## Dataset Information

Dataset Used: **orders(1).csv**

Dataset Features:

- Order ID
- Customer ID
- Order Date
- Product Category
- Region
- Revenue
- Quantity

Dataset Summary:

- Total Orders: 5000
- Total Customers: 500
- Multiple Product Categories
- Multiple Sales Regions

---

## Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- GitHub

---

## Project Workflow

### 1. Data Preparation

- Loaded the dataset into Google Colab.
- Converted date columns into datetime format.
- Performed data quality checks.

### 2. KPI Analysis

Calculated key business metrics:

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value

### 3. Revenue Trend Analysis

Analyzed monthly revenue performance to identify sales trends and seasonal patterns.

### 4. Category Analysis

Compared revenue generated across product categories to determine top-performing categories.

### 5. Regional Analysis

Evaluated regional sales contribution to identify high-performing markets.

### 6. Customer Analysis

Identified top customers contributing the highest revenue.

### 7. Statistical Validation

Performed an Independent Two-Sample T-Test to compare average revenue between product categories.

---

## Hypothesis Testing

### Null Hypothesis (H₀)

There is no significant difference in average revenue between Fashion and Electronics categories.

### Alternative Hypothesis (H₁)

There is a significant difference in average revenue between Fashion and Electronics categories.

### Statistical Method

- Independent Two-Sample T-Test
- Confidence Level: 95%
- Significance Level (α): 0.05

### Decision Rule

- If p-value < 0.05 → Reject H₀
- If p-value ≥ 0.05 → Fail to Reject H₀

---

## Key Insights

- Identified the highest revenue-generating product category.
- Determined the strongest performing sales region.
- Analyzed customer purchasing behavior.
- Evaluated monthly revenue trends.
- Validated category performance using statistical testing.

---

## Business Recommendations

1. Increase investment in top-performing product categories.
2. Focus marketing efforts on high-revenue regions.
3. Develop customer retention programs for high-value customers.
4. Use data-driven strategies to improve revenue growth.
5. Continuously monitor sales trends and customer behavior.

---

## Visualizations

The project includes:

- KPI Dashboard
- Monthly Revenue Trend
- Revenue by Category
- Revenue by Region
- Top Customers Analysis
- Statistical Test Results

---
