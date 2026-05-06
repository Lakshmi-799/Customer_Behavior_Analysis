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

**🔍 Key Insights:**
1. 💰 Revenue by Gender
2. 🎯 High-Spending Discount Users
3. ⭐ Top 5 Products by Rating
4. 🚚 Shipping Type vs Spending
5. 👥 Subscribers vs Non-Subscribers Analysis
6. 🏷️ Discount-Dependent Products
7. 🔁 Customer Segmentation:
    - New
    - Returning
    - Loyal
8. 🛍️ Top Products per Category
9. 🔄 Repeat Buyers & Subscription Trends
10. 📊 Revenue by Age Group
## 📈 Power BI Dashboard

Built an interactive dashboard to visualize insights:

**📌 Key Features:**

**KPI Cards:**
- Total Customers
- Average Purchase
- Average Rating

**Filters:**
  
- Subscription Status
- Gender
- Category
- Shipping Type
- 
**📊 Visualizations:**
  
- Revenue by Age Group
- Sales by Category
- Subscription Distribution
- Shipping vs Spending
  <img width="1907" height="920" alt="image" src="https://github.com/Lakshmi-799/Customer_Behavior_Analysis/blob/main/Screenshot%20(51).png" />

## 💡 Key Business Insights
- **🚚 Express shipping users spend more** → Opportunity for upselling
- 📉 Only **27% customers are subscribed** → High growth potential
- 💸 Discount-heavy products impact margins significantly
- 👥 Majority customers are **Loyal (≈80%)**
- 🎯 **Young Adults generate highest revenue**
  🚀 Business Recommendations
## 🎯 Boost Subscriptions
Offer exclusive benefits to convert non-subscribers

- **🏆 Customer Loyalty Programs**
- Reward repeat customers to increase retention
- **💰 Optimize Discount Strategy**
- Balance between sales growth and profitability
- **📢 Targeted Marketing**
- Focus on high-value age groups and frequent buyers
- **🛍️ Product Positioning**
- Promote top-rated and high-performing products

 Power point Presentation
   <img width="1907" height="920" alt="image" src="https://github.com/Lakshmi-799/Customer_Behavior_Analysis/blob/main/Customer-Shopping-Behavior-Analysis%20ppt.pdf" />
