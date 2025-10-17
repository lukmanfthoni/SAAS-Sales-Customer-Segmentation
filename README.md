# 🧠 Capstone Project 2 — Customer Lifetime Value & LRFM Segmentation Analysis  

## 📋 Project Overview  
This project analyzes customer behavior and profitability for a SaaS company operating on **Amazon Web Services (AWS)** infrastructure. The main goal is to identify the most valuable customers, understand behavioral patterns using **CLV (Customer Lifetime Value)** and **LRFM segmentation**, and provide actionable business insights for improving retention and profitability.  

---

## 🎯 Objectives  
1. Measure **Customer Lifetime Value (CLV)** based on sales data.  
2. Analyze customer behavior using **Length, Recency, Frequency, and Monetary (LRFM)** metrics.  
3. Segment customers CLV Class into **High**, **Medium**, and **Low Value** groups.  
4. Explore the relationship between **CLV** and **LRFM segments**.  
5. Provide strategic recommendations to improve **marketing efficiency** and **customer retention**.  

---

## 🧰 Tools & Technologies  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy)  
- **Tableau** (for dashboard visualization)  
- **Jupyter Notebook (.ipynb)**  
- **Dataset:** SaaS Sales Transactions (2020–2023)  

---

## 📦 Dataset Information  
- **Total Rows:** 9,994  
- **Total Columns:** 19  
- **Key Columns:**  
  - `Customer`, `Product`, `Sales`, `Profit`, `Quantity`, `Segment`, `Industry`, `Region`, `Order Date`    

---

## 🔍 Exploratory Data Analysis (EDA)
Main analyses include:
- **Sales & Profit Distribution**  
- **Outlier Detection (Sales, Profit, Discount, Quantity)**  
- **Customer Profitability Ranking**  
- **Most Profitable Products**  

💡 *Top insight:*  
- **Most profitable product:** 🧪 *Alchemy*  
- **Most profitable customer:** 🏢 *Valero Energy*  
- **Most popular product:** 💼 *ContactMatcher*

---

## 💎 CLV (Customer Lifetime Value) Analysis  
Formula used:  
\[
CLV = \frac{(\text{Average Sales per Transaction} \times \text{Frequency} \times \text{Customer Duration})}{10^4}
\]

- **High Value:** CLV > 4170  
- **Medium Value:** 2090–3082  
- **Low Value:** < 2090  

**Results:**  
- 49 High Value Customers  
- 25 Medium Value Customers  
- 25 Low Value Customers  

High-value customers contribute **most of the total profit**.  

---

## 📊 LRFM Segmentation  
Each dimension scored from 1–4 based on quantiles or domain rules:  

| Metric | Meaning | High Score Criteria |
|:--|:--|:--|
| **Length** | Customer lifetime | ≥ 1419 days |
| **Recency** | Days since last purchase | ≤ 6 days |
| **Frequency** | Number of orders | ≥ 60 |
| **Monetary** | Total spending | ≥ 31,000 |


## 👨‍💻 Author  
**Lukman Fathoni**  
Linkedin : https://www.linkedin.com/in/lukmanfthoni
📧 Email: [lukman.fathoni.lf@gmail.com]  


