# 🛍️ Customer Shopping Behavior — End-to-End Data Analytics Project

## 📌 Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases across multiple product categories**. The goal is to uncover insights related to:

- Spending patterns  
- Customer segments  
- Product preferences  
- Subscription behavior  
- Revenue contribution across demographics  

The workflow covers the **complete analytics lifecycle** — from Python EDA and data cleaning, to SQL business analysis, Power BI dashboarding, and final business reporting.

---

## 🗂️ Dataset

**Rows:** 3,900  
**Columns:** 18  

Key feature groups include:

- Customer demographics — Age, Gender, Location, Subscription Status  
- Purchase behavior — Purchase Amount, Discounts, Previous Purchases, Frequency  
- Product details — Category, Item Purchased, Size, Color, Season  
- Engagement metrics — Review Rating, Shipping Type  

Missing values were handled for the **Review Rating column** using category-wise median imputation.

---

## 🛠️ Tools & Technologies

- **Python** — Pandas, Numpy, Matplotlib (EDA & data cleaning)
- **PostgreSQL** — Business queries & trend analysis
- **Power BI** — Interactive dashboard & KPI visualization
- **GAMMA** — Presentation generation
- **Report Writing** — Insights documentation & recommendations

---

## 🚶 Project Steps

### ✔️ 1. Data Loading & EDA (Python)

- Loaded dataset using pandas  
- Performed structure & summary checks (`df.info()`, `describe()`)  
- Handled missing values in Review Rating  
- Renamed columns to snake_case  
- Feature engineering:  
  - Age group segmentation  
  - Purchase frequency indicator  
- Dropped redundant fields and validated consistency  
- Loaded cleaned dataset into PostgreSQL for analysis

---

### ✔️ 2. Business Analysis using SQL (PostgreSQL)

Key insights generated include:

- Revenue by Gender  
- Discount users spending above average  
- Top-rated products  
- Shipping type comparison  
- Subscriber vs Non-Subscriber spending behavior  
- Discount-dependent products  
- Customer segmentation — New, Returning, Loyal  
- Top products per category  
- Repeat buyers vs subscription behavior  
- Revenue contribution by age group  

---

### ✔️ 3. Dashboard — Power BI

Interactive dashboard presenting:

- Customer count & average purchase amount  
- Subscription distribution  
- Revenue & sales by category  
- Revenue by age group  
- Demographic filters and slicers  

The dashboard highlights key business KPIs and allows drill-down analysis.

---

### ✔️ 4. Reporting & Presentation

Deliverables include:

- Business report summarizing findings  
- Insights for marketing & retention strategy  
- Final presentation created using **GAMMA** for storytelling  

---

## 📊 Results — Key Insights

- Loyal customers contribute the highest revenue  
- Discount users can still be high-value customers  
- Express shipping users show stronger purchase behavior  
- Young & Middle-aged groups generate maximum revenue  
- Top-rated products align with high-sales categories  
- Subscription model presents strong retention potential  

These insights support **targeted marketing, loyalty programs, and pricing strategy decisions**.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone <repo-url>
cd project-folder
```
### 2️⃣ Run Python EDA

Open notebook / script

Install dependencies

Load dataset and execute cells

### 3️⃣ Load data to PostgreSQL

Update DB credentials

Push cleaned dataset to database

### 4️⃣ Execute SQL queries

Run analysis queries in PostgreSQL

### 5️⃣ View Power BI Dashboard

Open .pbix file

Refresh dataset connection

### 6️⃣ Review Report & Presentation

Open report document

View GAMMA presentation deck

## 🤝 Project Relevance

This project demonstrates:

- End-to-end analytics workflow

- Strong business interpretation

- Hands-on Python, SQL & BI experience

- Clear presentation of insights

Suitable for roles in:

- Data Analytics

- Business Analytics

- BI & Reporting
