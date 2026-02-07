# 🛍️ Customer Shopping Behavior Analysis

This project analyzes **customer shopping behavior** using transactional data to uncover insights into spending patterns, customer segmentation, product preferences, discount usage, and subscription behavior.  
The objective is to support **data-driven business and marketing decisions** through end-to-end analytics.

The project follows a **complete analytics lifecycle** using **Python, SQL (PostgreSQL), and Power BI**.

---


## 🎯 Business Objectives

- Understand customer spending patterns  
- Segment customers based on purchase behavior  
- Analyze discount and subscription impact  
- Identify top-performing and discount-dependent products  
- Enable data-driven marketing and pricing strategies  

---

## 📊 Dataset Overview

- **Total Records:** 3,900 purchases  
- **Total Features:** 18 columns  

### Key Attributes:
- Customer Demographics: Age, Gender, Location, Subscription Status  
- Purchase Details: Item, Category, Amount, Season
- Shopping Behavior: Discounts, Purchase Frequency, Review Ratings, Shipping Type  

### Data Quality:
- Missing values in `review_rating`
- Imputed using **median rating by product category**

---

## 🧹 Data Preparation & EDA (Notebook)

Performed in **Python (Pandas)**:

- Data loading and structure inspection  
- Missing value treatment  
- Column standardization (snake_case)  
- Feature engineering:
  - Age group creation  
  - Purchase frequency metrics  
- Data validation and consistency checks  

The cleaned dataset is stored in the **data/** folder and loaded into PostgreSQL.

---

## 🗄️ SQL Analysis (sql/)

Business-focused SQL queries were executed in **PostgreSQL** to answer:

- Revenue by gender  
- High-spending discount users  
- Top-rated products  
- Shipping type comparison  
- Subscriber vs non-subscriber performance  
- Discount-dependent products  
- Customer segmentation (New, Returning, Loyal)  
- Revenue by age group  

---

## 📈 Power BI Dashboard (powerbi/)

An interactive Power BI dashboard was built to visualize:

- Sales and revenue trends  
- Customer segments  
- Product performance  
- Subscription and discount impact  
- Shipping behavior insights  

The dashboard enables **dynamic exploration** for business users.

---

## 📑 Business Report (report/)

A professional **business analytics report** containing:

- Executive summary  
- Key performance metrics  
- Analytical findings  
- Visual insights  
- Strategic recommendations  

Designed for **stakeholders, managers, and interview discussions**.

---

## 💡 Key Business Insights

- Subscribers generate higher average revenue  
- Loyal customers drive a large share of sales  
- Discounts strongly influence specific products  
- Express shipping users spend more on average  
- Certain age groups dominate revenue contribution  

---

## 🧠 Business Recommendations

- Strengthen subscription offerings  
- Launch customer loyalty programs  
- Optimize discount strategies  
- Promote top-rated products  
- Target high-value age groups with personalized marketing  

---

## 🛠 Tools & Technologies

- **Python** (Pandas)  
- **PostgreSQL** (SQL analysis)  
- **Power BI** (Dashboarding)  
- **Excel / CSV** (Data source)  

---


