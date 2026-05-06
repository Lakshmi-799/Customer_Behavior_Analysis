# Customer_Behavior_Analysis
data analytics project showcasing customer behavior analysis using python, sql, power bi
## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases to uncover actionable insights into:

-Customer spending patterns
- Product preferences
- Subscription behavior
- Customer segmentation

The goal is to transform raw data into business-driven insights that can support strategic decision-making in retail/e-commerce environments.

## 📊 Dataset Summary
**📦 Total Records**: 3,900 transactions

 **📑 Features**: 18 columns
 
**⚠️ Missing Values:** 37 (Review Rating column)

## 🔑 Key Data Categories:
**Demographics** : Age, Gender, Location, Subscription Status

**Purchase Details**: Item, Category, Amount, Season, Size, Color

**Behavioral Data**: Discounts, Promo Codes, Frequency, Ratings, Shipping Type
## 🧹 Data Cleaning & Preparation (Python)

Performed using **Pandas & NumPy**

- ✔️ Data loading and inspection (df.info(), df.describe())
- ✔️ Handled missing values using median imputation (by category)
- ✔️ Standardized column names (snake_case)
- ✔️ Feature Engineering:
      - age_group
      - purchase_frequency_days
- ✔️ Removed redundant column (promo_code_used)
- ✔️ Ensured data consistency
## 🗄️ SQL Analysis (PostgreSQL)
Used SQL to answer key business questions:
🔍 Key Insights:
💰 Revenue by Gender
🎯 High-Spending Discount Users
⭐ Top 5 Products by Rating
🚚 Shipping Type vs Spending
👥 Subscribers vs Non-Subscribers Analysis
🏷️ Discount-Dependent Products
🔁 Customer Segmentation:
    - New
    - Returning
    - Loyal
🛍️ Top Products per Category
🔄 Repeat Buyers & Subscription Trends
📊 Revenue by Age Group

