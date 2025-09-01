# 🛍️ Black Friday Sales – Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-green)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-purple)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-lightgrey)

---

## 📌 Project Overview
The **Black Friday Sales Dataset** (Kaggle) contains 550K+ customer transactions.  
This project applies **Exploratory Data Analysis (EDA)** to uncover:  

- Which **cities, occupations, and age groups** drive the most revenue  
- Whether **marital status or city tenure** impacts spending  
- Which **products and categories** dominate sales  
- How strong are **correlations** between demographics and purchase amount  

---

## 📊 Dataset Information
- **Source**: [Black Friday Sales – Kaggle](https://www.kaggle.com/datasets/mehdidag/black-friday)  
- **Records**: ~550,000  
- **Features**:  
  - 🧑 Demographics → `Gender`, `Age`, `Marital_Status`, `Occupation`, `City_Category`, `Stay_In_Current_City_Years`  
  - 📦 Products → `Product_ID`, `Product_Category_1/2/3`  
  - 💰 Target → `Purchase` (amount spent per transaction)  

---

## 🔍 Methodology
1. Data Cleaning & Encoding → handled missing values, standardized categories  
2. Univariate Analysis → purchase distributions, categorical breakdowns  
3. Bivariate Analysis → demographic impacts on spending  
4. Top-N Analysis → most valuable customers, products, and categories  
5. Correlation Study → feature–target relationships via heatmap  

---

## 📈 Key Findings

### 🌆 City Contribution
- **City B → 41.5% of total revenue** (dominant market)  
- Cities C (32.7%) and A (25.8%) follow  

### 🏠 Tenure in Current City
- **1-year residents** → ~35.2% of revenue volume  
- **2-year residents** → highest avg purchase (~₹9,320)  

### 👥 Age Influence
- **Older groups spend more**: Age code 5 avg = ₹9,535 vs. code 0 avg = ₹8,933  
- ~6.7% increase between youngest and older cohorts  

### 💍 Marital Status
- Negligible impact: Married vs. Unmarried differ by only ₹4.7  

### 💼 Occupation
- Top 5 occupation codes (4, 0, 7, 1, 17) = **~52.5% of revenue**  

### 📦 Product Categories
- **Category 1** → 10, 9, 15 dominate  
- **Category 2** → 15, 16, 13 dominate  
- **Category 3** → 16, 17, 13 dominate  

### 🛍️ Products
- **Top SKU P00025442 → ₹28M sales**  
- Top 5 SKUs ≈ **₹128.5M (~2.5% of sales)**  

### 📉 Correlation
- **No strong linear predictors** (all |r| < 0.07)  
- Spending patterns are **segment-driven**, not linear  

---

## 📊 Visual Gallery
The notebook generates:  
- Purchases by **City, Age, Occupation, Tenure**  
- **Histograms** of purchase distribution  
- **Correlation heatmap**  
- **Top-N products & categories plots**  

---

## 🚀 Resume-Ready Impact
- Analyzed **550K+ Black Friday sales records** to extract **business-critical insights**  
- Found **City B generates 41.5% of revenue** and **older cohorts spend ~6.7% more**  
- Identified **top 5 occupations driving ~52.5% of sales**  
- Verified **no strong linear predictors (|r| < 0.07)**, guiding toward non-linear ML models  
- Delivered **visual-first, actionable insights** for retail strategy  

---

## 📂 Repository Structure
