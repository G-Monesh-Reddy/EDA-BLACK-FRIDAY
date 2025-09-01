🛍️ Black Friday Sales – Exploratory Data Analysis (EDA)

📌 Project Overview

The Black Friday Sales Dataset is one of Kaggle’s most popular datasets for learning EDA and feature engineering.
This project dives into 550K+ customer transactions to answer key business questions such as:

Which cities, occupations, and age groups drive the most revenue?

Do marital status or city tenure influence customer spending?

Which products and categories are most popular?

How strong are the correlations between demographics and purchase amount?

The analysis blends business insights with data storytelling and prepares the ground for predictive modeling and customer segmentation.

📊 Dataset Information

Source: Black Friday Sales – Kaggle

Records: ~550,000

Features:

🧑 Demographics → Gender, Age, Marital_Status, Occupation, City_Category, Stay_In_Current_City_Years

📦 Products → Product_ID, Product_Category_1/2/3

💰 Target Variable → Purchase (spending amount per transaction)

🔍 Methodology

Data Cleaning & Encoding → managed missing values, standardized categories.

Univariate Analysis → purchase distributions, categorical breakdowns.

Bivariate Analysis → impact of demographics on spending.

Top-N Analysis → most valuable customers, products, and categories.

Correlation Study → heatmap of feature–target relationships.

📈 Key Findings
🌆 City Contribution

City B → 41.5% of total revenue (dominant market).

Cities C (32.7%) and A (25.8%) follow.

🏠 Tenure in Current City

1-year residents → ~35.2% of revenue volume.

2-year residents → highest avg purchase (~₹9,320).

👥 Age Influence

Older groups spend more: Age code 5 avg = ₹9,535 vs. code 0 avg = ₹8,933.

~6.7% increase between youngest and older cohorts.

💍 Marital Status

Negligible impact: Married vs. Unmarried differ by only ₹4.7 on avg purchase.

💼 Occupation

Top 5 occupation codes (4, 0, 7, 1, 17) = ~52.5% of revenue.

📦 Product Categories

Category 1 → 10, 9, 15 dominate.

Category 2 → 15, 16, 13 dominate.

Category 3 → 16, 17, 13 dominate.

🛍️ Products

Top SKU P00025442 → ₹28M sales.

Top 5 SKUs ≈ ₹128.5M (~2.5% of sales).

📉 Correlation

No strong linear predictors (all |r| < 0.07).

Spending patterns are segment-driven, not purely linear.

📊 Visual Gallery

Some of the key plots generated in the notebook:

Purchases by City, Age, Occupation, Tenure

Histograms of purchase distribution

Heatmap for correlation analysis

Top-N products & categories
