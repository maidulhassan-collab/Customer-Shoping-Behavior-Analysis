## 📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional retail data to uncover meaningful business insights related to customer spending patterns, product preferences, purchasing behavior, subscription trends, and customer segmentation.

The project follows a complete data analytics workflow:

*Data Cleaning → Exploratory Data Analysis → SQL Business Analysis → Dashboard Development → Business Recommendations*

The objective is to transform raw customer transaction data into actionable insights that can support data-driven decision-making for retail businesses.

---

# 🎯 Business Objectives

The main objectives of this project are:

- Analyze customer purchasing patterns and spending behavior.
- Identify valuable customer segments.
- Understand product performance and customer preferences.
- Evaluate the impact of discounts and subscriptions.
- Discover revenue trends across customer groups.
- Build an interactive dashboard for business decision-making.

---

# 📂 Dataset Information

The dataset contains customer transaction records from different product categories.

### Dataset Summary

| Feature | Details |
|---|---|
| Total Records | 3,900 |
| Total Columns | 18 |
| Domain | Retail / E-commerce Analytics |
| Data Type | Customer Transaction Data |

### Main Features

### 👤 Customer Information
- Customer ID
- Age
- Gender
- Location
- Subscription Status

### 🛒 Purchase Information
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

### 📊 Shopping Behavior
- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

---

# 🛠️ Tools & Technologies

## Python
Used for:
- Data loading
- Data exploration
- Data cleaning
- Missing value handling
- Feature engineering

Libraries:
- Pandas
- NumPy

---

## PostgreSQL

Used for:
- Business transaction analysis
- Customer segmentation
- Revenue analysis
- Product performance analysis

---

## Power BI

Used for:
- Interactive dashboard creation
- Data visualization
- Business reporting

---

# 🔄 Project Workflow
# 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed:

### Missing Value Handling
- Identified missing values in the Review Rating column.
- Filled missing ratings using category-level median values.

### Data Standardization
- Converted column names into snake_case format.
- Improved dataset readability and consistency.

### Feature Engineering

Created additional analytical features:

- age_group
  - Young Adult
  - Adult
  - Middle-aged
  - Senior

- purchase_frequency_days

### Data Consistency Checks

- Compared discount_applied and promo_code_used variables.
- Removed redundant information before database analysis.

---

# 📊 SQL Business Analysis

PostgreSQL was used to answer important business questions.

## 1. Revenue Analysis by Gender

Compared total revenue contribution between male and female customers.

*Insight:*
The analysis helps identify customer groups contributing more revenue and supports targeted marketing strategies.

---

## 2. High-Spending Discount Users

Identified customers who:

- Used discounts
- Still spent above the average purchase amount

*Business Value:*
Helps understand whether discounts are attracting valuable customers.

---

## 3. Top Rated Products

Analyzed products with the highest average customer ratings.

Top-rated products included:

- Gloves
- Sandals
- Boots
- Hat
- Skirt

---

## 4. Shipping Type Analysis

Compared average purchase amounts between:

- Standard Shipping
- Express Shipping

---

## 5. Subscription Analysis

Compared:

- Subscribers
- Non-subscribers

Based on:

- Average spending
- Total revenue contribution

---

## 6. Customer Segmentation

Customers were classified into:

### 🟢 Loyal Customers
Frequent buyers with strong purchase history.

### 🟡 Returning Customers
Customers with previous purchase activity.

### 🔵 New Customers
Customers with limited purchase history.

---

## 7. Repeat Buyer Analysis

Analyzed whether customers with higher purchase frequency are more likely to subscribe.

---

## 8. Revenue by Age Group

Analyzed revenue contribution across different customer age groups.

---

## 9. Product Category Analysis

Identified top-selling products within each category:

Categories included:

- Accessories
- Clothing
- Footwear
- Outerwear

---

# 📈 Power BI Dashboard

An interactive dashboard was developed to visualize key business metrics.

## Dashboard Features

### KPI Metrics

- Total Customers
- Average Review Rating
- Average Purchase Amount

### Visual Analysis

- Revenue by Category
- Sales by Category
- Subscription Distribution
- Revenue by Age Group
- Customer Filtering

---

# 💡 Key Business Insights

✔️ Customer purchasing behavior differs across demographic groups.

✔️ Loyal customers represent the largest customer segment.

✔️ Product ratings can help identify products suitable for promotional campaigns.

✔️ Discount strategies should be optimized to increase sales without reducing profitability.

✔️ Subscription programs provide opportunities for customer retention.

---

# 🚀 Business Recommendations

## 1. Increase Subscription Adoption

Introduce:

- Exclusive subscriber discounts
- Membership benefits
- Personalized offers

---

## 2. Strengthen Customer Loyalty

Implement:

- Reward programs
- Repeat purchase incentives
- Personalized recommendations

---

## 3. Optimize Discount Strategy

Balance:

- Customer attraction
- Revenue growth
- Profit margins

---

## 4. Promote High-Performing Products

Use customer ratings and sales data to highlight:

- Best-selling products
- Highly-rated products

---

## 5. Targeted Marketing Campaigns

Focus marketing efforts on:

- High-revenue customer groups
- Frequent buyers
- Valuable customer segments

---

# 📁 Repository Structure
# 📌 Project Outcome

This project demonstrates an end-to-end data analytics workflow by combining Python, SQL, and Power BI to convert raw retail transaction data into meaningful business insights.

The analysis helps organizations understand customer behavior, improve marketing decisions, optimize product strategies, and increase customer retention.

---
