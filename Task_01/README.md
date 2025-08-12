# Project Title: EDA on Retail Sales Data
# 📊 Task 01 - Amazon Dataset Exploratory Data Analysis

## 📌 Overview
This project performs an **end-to-end Exploratory Data Analysis (EDA)** on Amazon sales data.  
It includes **data cleaning**, **statistical exploration**, **advanced visualizations**, and an **automated PDF report generation** for streamlined insights.

---

## 📂 Key Deliverables
- **Cleaned Dataset**: `cleaned_amazon_data.csv`
- **Summary Tables**:
  - `numeric_summary.csv` → Descriptive statistics of numeric columns
  - `top_products.csv` → Highest selling products
  - `category_summary.csv` → Category-level sales summary
  - `top_customers.csv` → Top customers by spend
  - `correlation_matrix.csv` → Correlation between numerical features
- **Visuals**:
  - Top products by sales
  - Category-wise sales distribution
  - Customer purchase behavior
  - Correlation heatmap
  - Price distribution comparison
  - Sales trends over time
  - Boxplots for price ranges
- **Automated Report**: `EDA_Report.pdf` (contains all visuals + insights)

---

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn fpdf
python amazon_eda.py
