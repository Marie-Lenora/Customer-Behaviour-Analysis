# Customer-Behaviour-Analysis
Data Analysis Project showcasing data analytics using python, SQL and PowerBI


# 📊 Customer Behaviour Analysis

## 📌 Project Overview
This project analyzes customer purchasing behaviour to uncover key drivers of revenue and engagement. The goal is to generate actionable insights around customer segments, product preferences, and purchasing patterns to support data-driven business decisions.

The project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI.

---

## 🎯 Business Problem
The business aims to better understand:
- Who their most valuable customers are  
- What products and categories drive the most revenue  
- How discounts, subscriptions, and shipping influence purchasing behavior  

These insights help improve marketing strategies, customer retention, and overall revenue.

---

## 📊 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  

### Key Features:
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Product Category, Purchase Amount, Season, Size, Colour  
- **Shopping Behaviour:** Discounts, Purchase Frequency, Review Ratings, Shipping Type  

### Data Quality:
- 37 missing values in the `review_rating` column (handled during preprocessing)

---

## 🛠️ Tools & Technologies
- **Python (Pandas)** – Data cleaning & preprocessing  
- **SQL (PostgreSQL)** – Business analysis  
- **Power BI** – Data visualization & dashboard  

---

## 🔍 Data Cleaning & Preparation
- Handled missing values using **median imputation by category**  
- Standardized column names to **snake_case**  
- Removed redundant columns (`promo_code_used`)  
- Created new features:
  - `age_group` for segmentation  
  - `number_of_days_between_purchases` for behavioral analysis  

---

## 📈 Analysis Approach

### Python (EDA & Feature Engineering)
- Explored dataset structure and summary statistics  
- Identified trends and inconsistencies  
- Performed feature engineering to improve analysis  

### SQL (Business Analysis)
Key questions answered:
- Revenue comparison by gender  
- Impact of discounts on high-spending customers  
- Top-rated products  
- Customer segmentation (New, Returning, Loyal)  
- Subscription vs purchase behavior  
- Revenue by age group  
- Shipping type impact on spending  

---

## 📊 Dashboard
A Power BI dashboard was created to visualize key insights, including:
- Revenue trends  
- Customer segments  
- Product performance  
- Purchase behavior  

---

## 💡 Key Insights
- ~70% of customers are male  
- Clothing is the top-selling category  
- Young adults and middle-aged customers generate the most revenue  
- Spring is the highest-performing season  
- Over 75% of customers are repeat buyers  
- Majority of customers are non-subscribers  
- Repeat customers are not significantly more likely to subscribe  

---

## 📈 Business Recommendations
- Introduce stronger incentives to increase subscriptions  
- Implement loyalty programs to retain customers  
- Focus marketing on high-value segments  
- Optimize inventory based on size demand (medium most popular)  
- Promote top-rated and best-selling products  
- Increase seasonal promotions during spring  
