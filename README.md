# 📊 Customer Shopping Behaviour Analysis

End-to-end data analytics project analyzing customer shopping behavior using **Python, PostgreSQL, and Tableau** to generate actionable business insights.

---

## 📁 Repository Structure


├── Customer_Shopping_Behaviour_Report.pdf
├── Customer_beaviour_EDA.ipynb
├── Customer_behaviour_dashboard.twbx
├── Customer_behaviour_sql_queries.sql
├── customer_shopping_behavior.csv
├── README.md
└── LICENSE


---

## 📌 Project Overview

This project performs a complete **end-to-end analysis of customer shopping behavior** using a dataset of ~3,900 records containing demographic, transactional, and behavioral data.

The workflow covers:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- SQL-based business analysis
- Interactive dashboard creation

---

## 🎯 Objectives

- Understand revenue distribution across gender, age group, and product category  
- Identify customer segments based on loyalty and subscription behavior  
- Analyze product performance using ratings, discounts, and purchase frequency  
- Compare the impact of shipping type on spending  
- Build an interactive Tableau dashboard for stakeholders  

---

## 🛠️ Tech Stack

- **Python (Pandas)** → Data cleaning, preprocessing, EDA  
- **PostgreSQL (SQL)** → Aggregations, CTEs, window functions, business queries  
- **Tableau** → Interactive dashboards and visual insights  

---

## 🔍 Project Workflow

### 1. Data Preprocessing (Python)

- Loaded dataset using Pandas  
- Handled missing values (Review Rating imputed using category median)  
- Standardized column names  
- Removed redundant columns  
- Feature engineering:
  - Age group segmentation  
  - Purchase frequency transformation  

---

### 2. SQL Analysis

Performed structured analysis using PostgreSQL:

- Revenue analysis by gender and age group  
- Customer segmentation:
  - New  
  - Returning  
  - Loyal  
- Subscription vs non-subscription behavior  
- Discount usage and high-value customer identification  
- Product performance using window functions (ROW_NUMBER)  

---

### 3. Tableau Dashboard

Built an interactive dashboard with:

**Filters:**
- Gender  
- Age Group  
- Category  
- Subscription Status  
- Shipping Type  

**KPIs:**
- Total Customers  
- Average Purchase Amount  
- Average Review Rating  

---

## 📊 Dashboard Preview

![Dashboard](images/dashboard.png)

---

## 📈 Key Insights

- 👥 Young Adults and Middle-aged customers contribute the highest revenue  
- 🛍️ Clothing is the top-performing category by both revenue and sales volume  
- 🔁 Loyal customers (11+ purchases) form the largest high-value segment  
- 💳 Only ~27% of customers are subscribed → strong opportunity for growth  
- 💸 Customers using discounts but spending above average are high-value targets  
- 🚚 Shipping type has minimal impact on spending behavior  

---

## 💼 Business Impact

This analysis provides actionable insights that can directly influence business strategy:

- 📌 **Targeted Marketing:** Focus campaigns on high-value segments (Young Adults & Middle-aged customers) to maximize ROI  
- 📌 **Subscription Growth:** Identify and convert repeat buyers into subscribers to increase customer lifetime value  
- 📌 **Revenue Optimization:** Prioritize high-performing categories (Clothing & Accessories) for promotions and inventory planning  
- 📌 **Discount Strategy:** Reduce unnecessary discounts by targeting customers who already spend above average  
- 📌 **Customer Retention:** Develop loyalty programs for frequent buyers to sustain long-term engagement  
- 📌 **Operational Efficiency:** Maintain current shipping pricing strategy since it does not significantly impact spending  

---

## 📄 Report

Detailed explanation of the analysis is available in:


Customer_Shopping_Behaviour_Report.pdf


---

## 🚀 How to Use

1. Clone the repository:

git clone [https://github.com/your-username/customer-shopping-analysis](https://github.com/ayinam-alekhya/customer_shopping_behaviour).git


2. Run Python analysis:

Customer_beaviour_EDA.ipynb


3. Execute SQL queries:

Customer_behaviour_sql_queries.sql


4. Open Tableau dashboard:

Customer_behaviour_dashboard.twbx


---

## 📌 Outcome

This project demonstrates a **production-style data analysis pipeline**, transforming raw data into meaningful insights and an interactive dashboard for decision-making.

---

## 🙌 Author

**Alekhya Ayinam**
