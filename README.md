# 🛍️ E-commerce Sales Analysis

This project analyzes an e-commerce dataset to uncover sales trends, customer behavior, and key revenue drivers.  
The data was processed and explored in **Python (pandas, matplotlib, seaborn)** and visualized with **Tableau** for an interactive presentation.

---

## 📁 Dataset Overview

- **Source:** [Ecommerce dataset on Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
- **Rows:** ~540,000 transactions  
- **Period:** 2010–2011  
- **Main columns:**
  - `InvoiceNo` — Transaction ID  
  - `StockCode` — Product code  
  - `Description` — Product name  
  - `Quantity` — Units sold  
  - `InvoiceDate` — Date of sale  
  - `UnitPrice` — Price per unit  
  - `CustomerID` — Buyer identifier  
  - `Country` — Customer location  

---

## 🧹 Data Preparation (Python Notebook)

Performed using **pandas**:

1. Removed cancelled transactions and missing values.  
2. Created calculated fields:
   - **Revenue = Quantity × UnitPrice**  
   - **Average Order Value (AOV)**  
   - **Revenue share by country**  
3. Aggregated data by product, customer, and country.  

📓 The Jupyter Notebook includes data cleaning, feature engineering, and exploratory analysis.

---

## 📊 Key Insights

- **The United Kingdom contributes ~84% of total revenue**, showing a highly concentrated market.  
- **Top 10 products** drive most of the sales, but high-volume items aren’t always the most profitable.  
- **Customer base is diversified** — no single buyer dominates total revenue.  
- Suggests opportunities for **pricing optimization** and **geographic expansion**.

---

## 🖼️ Interactive Dashboard

You can explore the full interactive Tableau dashboard here:  
👉 [View on Tableau Public](https://public.tableau.com/app/profile/lucio.colombo/viz/EcommerceUCIUKanalysis/Dashboard1)

---

## 🧠 Tools & Skills Demonstrated

| Category | Tools / Libraries |
|-----------|------------------|
| Data Cleaning & Analysis | Python, pandas, numpy |
| Visualization | seaborn, matplotlib, Tableau |
| Data Storytelling | Dashboard design, KPI tracking |
| Version Control | Git & GitHub |

---

## 🚀 How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-analysis.git
