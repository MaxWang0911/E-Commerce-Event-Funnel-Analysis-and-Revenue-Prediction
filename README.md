# E-Commerce Event Funnel Analysis and Revenue Prediction

## 📌 Project Overview
This project analyzes large-scale e-commerce behavioral datasets to uncover patterns in user activity (`view`, `cart`, `purchase`) and their impact on revenue.  
It includes **conversion funnel analysis**, **correlation studies**, **multicollinearity diagnostics**, and **regression modeling** to identify key drivers of sales performance.

## 📂 Dataset
This project uses multiple publicly available e-commerce datasets from Kaggle, covering different product categories and event histories:

1. [Ecommerce Behavior Data from Multi Category Store](https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store)  
2. [Ecommerce Purchase History from Electronics Store](https://www.kaggle.com/mkechinov/ecommerce-purchase-history-from-electronics-store)  
3. [Ecommerce Events History in Cosmetics Shop](https://www.kaggle.com/mkechinov/ecommerce-events-history-in-cosmetics-shop)  
4. [Ecommerce Purchase History from Jewelry Store](https://www.kaggle.com/mkechinov/ecommerce-purchase-history-from-jewelry-store)  
5. [Ecommerce Events History in Electronics Store](https://www.kaggle.com/mkechinov/ecommerce-events-history-in-electronics-store)  

The datasets contain detailed records of user interactions, including:
- Product views
- Add-to-cart actions
- Purchases
- Cart removals
- Associated timestamps and revenue data

## 📊 Key Analyses
1. **Event Distribution** – Overall counts for each event type, highlighting large drop-off from views to purchases.
2. **Hourly Activity Patterns** – Identification of peak activity hours and potential marketing opportunities.
3. **Conversion Rates** – View→Cart, Cart→Purchase, and View→Purchase.
4. **Correlation Analysis** – Pearson & Spearman correlation coefficients between events and revenue.
5. **Regression Modeling** – Linear regression with R², coefficients, and intercept for predicting revenue.
6. **Multicollinearity Checks** – Variance Inflation Factor (VIF) and condition number diagnostics.
7. **Scatter Plot Analysis** – log1p-transformed relationships between event counts and revenue.

## 📈 Insights
- Purchases have the **strongest direct relationship** with revenue (Pearson: 0.963).
- High **multicollinearity** detected between `view`, `cart`, and `purchase` (VIF > 5 in raw counts).
- Conversion from views to purchases is **~2.6%**, indicating potential for funnel optimization.
- Peak user activity occurs in **late morning** (~9–11 AM) and **late afternoon** (~4–5 PM).

## 🛠 Tools & Libraries
- **Python** (pandas, numpy, matplotlib, seaborn, statsmodels, scipy)
- **Jupyter Notebook** for interactive analysis and visualization
- **Parquet** files for efficient data storage

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.co

