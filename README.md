# 👨🏻‍💻 Customer Behavior Data Analytics Project  
**Python · SQL · Power BI**

This project demonstrates a **complete, industry-style end-to-end data analytics workflow** focused on understanding customer shopping behavior and converting raw transactional data into **actionable business insights**.  
The analysis mirrors real-world responsibilities of Data Analysts working with cross-functional business teams.

---

## 📌 Business Context
A retail organization is experiencing shifts in customer purchasing patterns across **demographics, product categories, and shopping behaviors**.  
The leadership team wants to leverage customer data to improve:

- Sales performance  
- Customer engagement & loyalty  
- Marketing and product strategies  

**Core Business Question:**  
> *How can consumer shopping data be used to identify trends, improve customer engagement, and optimize marketing and product decisions?* :contentReference[oaicite:1]{index=1}

---

## 📸 Dashboard Preview

### 🔹 Overall Customer Behavior Dashboard
![Dashboard Overview](https://github.com/dhruvsingh33/customer-trends-data-analysis/blob/main/img/img1.png)

---

### 🔹 Subscription Status Analysis
<img src="https://github.com/dhruvsingh33/customer-trends-data-analysis/blob/main/img/img2.png" width="450">

**Insight:**  
Only a minority of customers are subscribed, indicating a strong opportunity to increase adoption through targeted incentives.

---

### 🔹 Revenue & Sales by Category
![Category Analysis](https://github.com/dhruvsingh33/customer-trends-data-analysis/blob/main/img/img3.png)

**Insight:**  
A small number of product categories account for a disproportionate share of total revenue and sales volume.

---

### 🔹 Customer Segmentation by Age Group
![Age Group Analysis](https://github.com/dhruvsingh33/customer-trends-data-analysis/blob/main/img/img4.png)

**Insight:**  
Young adult and middle-aged customers generate the highest revenue contribution.

---

## 🎯 Project Objectives
- Clean and prepare raw customer data for analysis  
- Identify key customer segments and purchasing drivers  
- Analyze the impact of discounts, subscriptions, shipping types, and demographics  
- Build an interactive dashboard to support data-driven decision-making  

---

## 🛠️ Tech Stack
- **Python** – Data cleaning, transformation, and exploratory data analysis (EDA)  
- **SQL (PostgreSQL)** – Structured business analysis and customer segmentation  
- **Power BI Desktop** – Data modeling, KPI tracking, and interactive dashboards  
- **CSV Dataset** – Retail customer shopping behavior data  

---

## 📊 Dataset Overview
- **Records:** ~3,900 customer transactions  
- **Columns:** 18 features  
- **Key Attributes:**
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Category, Item Purchased, Purchase Amount, Season)
  - Shopping behavior (Discount Applied, Shipping Type, Review Rating, Purchase Frequency)

Missing values were identified in the **review rating** field and handled during preprocessing :contentReference[oaicite:2]{index=2}.

---

## 🔍 Analytics Workflow

### 1️⃣ Data Preparation & EDA (Python)
- Loaded raw dataset using pandas  
- Inspected schema and summary statistics  
- Handled missing review ratings using **category-level median imputation**  
- Standardized column naming (snake_case)  
- Engineered new features:
  - `age_group` (binned customer ages)
  - Purchase frequency indicators  
- Validated data consistency and removed redundant fields  
- Loaded cleaned data into PostgreSQL for SQL analysis :contentReference[oaicite:3]{index=3}

---

### 2️⃣ Data Analysis (SQL)
Business-driven SQL queries were written to answer key questions, including:

- Revenue comparison by gender  
- High-spending customers who used discounts  
- Top-rated products by average review rating  
- Shipping type comparison (Standard vs. Express)  
- Subscribers vs. non-subscribers (customers, spend, revenue)  
- Discount-dependent products  
- Customer segmentation into **New, Returning, and Loyal** users  
- Revenue contribution by age group  
- Relationship between repeat buyers and subscription behavior :contentReference[oaicite:4]{index=4}

---

### 3️⃣ Visualization & Dashboarding (Power BI)
An interactive Power BI dashboard was built to present insights clearly to stakeholders.  
The dashboard includes:

- KPI cards (Customers, Avg Purchase, Avg Rating)
- Subscription status distribution
- Revenue & sales by product category
- Revenue & sales by age group
- Dynamic filters for gender, category, subscription status, and shipping type

---

## 🧠 Key Business Insights
- Subscribed customers represent a smaller segment but show strong revenue impact  
- Discounts influence purchases but do not always reduce average spend  
- Certain products are highly discount-dependent  
- Loyal customers form the largest segment, highlighting the importance of retention  
- Revenue contribution varies significantly by age group and shipping preference  

---

## 📈 Business Recommendations
- **Increase Subscription Adoption** – Promote exclusive benefits for subscribers  
- **Strengthen Loyalty Programs** – Incentivize repeat buyers to retain high-value customers  
- **Optimize Discount Strategy** – Balance promotional impact with profit margins  
- **Product Positioning** – Highlight top-rated and best-selling products  
- **Targeted Marketing** – Focus campaigns on high-revenue age groups and express-shipping users :contentReference[oaicite:5]{index=5}

---

## 📁 Repository Structure
customer-behavior-analysis/
│
├── customer_behavior_dashboard.pbix
├── customer_shopping_behavior.csv
├── customer_behavior_sql_queries.sql
├── Customer_Shopping_Behavior_Analysis.ipynb
├── screenshots/
│ ├── dashboard_overview.png
│ ├── subscription_status.png
│ ├── category_analysis.png
│ └── age_group_analysis.png
└── README.md


---

## ▶️ How to Use
1. Clone or download the repository  
2. Review Python-based EDA in `Customer_Shopping_Behavior_Analysis.ipynb`  
3. Explore business queries in `customer_behavior_sql_queries.sql`  
4. Open `customer_behavior_dashboard.pbix` using **Power BI Desktop**  
5. Interact with slicers and visuals to explore insights  

> **Note:**  
> The dashboard is built using **Power BI Desktop**.  
> Public publishing requires an organizational Microsoft account.

---

## 👤 Author
**Dhruv**  
Data Analyst  
Skills: Python · SQL · Power BI · Data Analysis


## 📁 Repository Structure
