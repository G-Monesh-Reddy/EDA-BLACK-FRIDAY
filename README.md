🛍️ Black Friday Sales – Exploratory Data Analysis (EDA)
📌 Project Overview

This project explores the Black Friday Sales Dataset from Kaggle to understand customer purchase behavior across demographics, occupations, and product categories.
Using Exploratory Data Analysis (EDA), we identify key spending patterns, revenue drivers, and segment-level insights.

The findings support:

Business insights → identifying top cities, occupations, and product categories driving sales.

Customer segmentation → profiling high-value cohorts based on age, tenure, and city.

Modeling guidance → understanding correlations and preparing features for ML tasks.

📊 Dataset Details

Source: Black Friday Sales Dataset – Kaggle

Records: ~550,000+ purchase transactions

Features:

User Demographics → User_ID, Gender, Age, Marital_Status, Occupation, City_Category, Stay_In_Current_City_Years

Product Information → Product_ID, Product_Category_1/2/3

Target Variable → Purchase (amount spent per transaction)

🔍 Methodology

Data Cleaning & Encoding → handled missing values, categorical conversion.

Univariate Analysis → examined purchase distribution, age, city, and occupation breakdowns.

Bivariate Analysis → cross-tabulated purchase values with demographics.

Correlation Heatmap → studied linear relationships between encoded features.

Top-N Analysis → highlighted high-revenue products and categories.

📈 Key Insights (From Visuals)
🌆 City-Wise Purchases

City B dominates with ~41.5% of total sales revenue.

Cities C (~32.7%) and A (~25.8%) follow.
➡️ City B is the primary market driver during Black Friday sales.

🏠 Customer Tenure

1-year residents generated ~35.2% of revenue.

2-year residents have the highest avg order value (~₹9,320), slightly higher than others.
➡️ Short-stay customers drive volume, mid-stay customers drive value.

👥 Age Groups

Older cohorts spend more: Age code 5 avg = ₹9,535 vs. code 0 avg = ₹8,933.

Spending grows ~6.7% between youngest and older cohorts.
➡️ Mature customers show higher purchasing power.

💍 Marital Status

Minimal difference: Married (₹9,261) vs. Unmarried (₹9,266).
➡️ Marital status has negligible effect on spending.

💼 Occupation

Top 5 occupations (codes 4, 0, 7, 1, 17) = ~52.5% of revenue.
➡️ Half the sales are concentrated in a few professional groups.

📦 Product Categories

Category 1: IDs 10, 9, 15 are most common.

Category 2: IDs 15, 16, 13 dominate.

Category 3: IDs 16, 17, 13 lead.
➡️ Purchases cluster around a few product categories.

🛍️ Top Products

Top SKU (P00025442) generated ~₹28M.

Top 5 SKUs ≈ ₹128.5M (~2.5% of total sales).
➡️ A few products show outsized popularity, but sales are distributed overall.

📉 Correlation Insights

No strong linear predictors of purchase (all |r| < 0.07).
➡️ Customer spending is segment-driven, not purely linear.

🖥️ Visual Outputs

Bar charts → Purchases by city, age, occupation, tenure.

Histograms → Purchase distribution.

Heatmap → Feature correlations.

Top-N plots → Products and categories.
