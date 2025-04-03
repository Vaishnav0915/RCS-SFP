# RCS-SFP
# 🛍️ Retail Customer Segmentation & Sales Forecasting

A comprehensive end-to-end data analysis project focused on uncovering customer behavior patterns and forecasting future sales using machine learning and time series techniques. This project demonstrates a blend of business intelligence, data science, and customer analytics to support decision-making in a retail environment.

---

## 📌 Problem Statement

Retail companies deal with large volumes of transactional data. However, understanding **who your most valuable customers are**, and being able to **predict future sales trends**, is essential to drive growth, personalize marketing, and optimize operations.

This project addresses two key business questions:

1. **How can we segment customers based on their purchase behavior?**
2. **How can we forecast future sales to help with inventory planning and financial projections?**

---

## 🎯 Project Objectives

- Perform **RFM (Recency, Frequency, Monetary)** analysis to understand customer behavior
- Use **K-Means Clustering** to segment customers into meaningful groups
- Identify **top-selling products and trends** using exploratory data analysis
- Build a **sales forecasting model** using Facebook Prophet
- Visualize insights through graphs and charts for business understanding

---

## 📊 Dataset

**Source:** [Online Retail II Dataset – Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)

**Details:**
- Transactions from a UK-based online retailer (2009–2011)
- Includes fields such as `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `Price`, `CustomerID`, and `Country`

---

## 🧠 Tools & Technologies

| Area | Tools Used |
|------|------------|
| Data Manipulation | Python, Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Clustering | Scikit-learn (KMeans) |
| Forecasting | Facebook Prophet |
| Dashboard (Optional) | Power BI / Streamlit |
| Environment | Jupyter Notebook / Google Colab |

---

## 🔎 Project Workflow

### 1. Data Cleaning
- Removed null values (e.g., missing `CustomerID`)
- Filtered out canceled and negative transactions
- Created a `TotalPrice` column (Quantity × UnitPrice)

### 2. Exploratory Data Analysis (EDA)
- Identified top 10 products by revenue and quantity
- Analyzed sales trends over time (monthly revenue trends)
- Visualized patterns using bar plots and line graphs

### 3. RFM Customer Segmentation
- Calculated:
  - **Recency** = Days since last purchase
  - **Frequency** = Number of purchases
  - **Monetary** = Total spend
- Standardized the values and applied **KMeans Clustering**
- Grouped customers into 4 segments (e.g., loyal, at-risk)

### 4. Visual Insights
- Scatter plot: Recency vs Frequency (colored by customer cluster)
- Bar plot: Average spend per cluster
- Line plot: Monthly revenue over time

### 5. Sales Forecasting
- Resampled data to monthly granularity
- Modeled sales with Facebook Prophet
- Forecasted next 6 months of sales
- Visualized trends, seasonality, and future projections

---

## 📈 Key Insights

- High-value customers were identified using clustering, enabling potential **personalized marketing** campaigns.
- November and December showed **seasonal spikes** in revenue, likely due to holiday promotions.
- Top-selling products generated a disproportionate share of revenue, suggesting **80/20 rule** dynamics.
- Sales forecasting highlighted consistent growth with **seasonal dips and peaks**.

---

## 🧩 Business Applications

- Targeted email campaigns for **loyal and at-risk** customers
- **Inventory management** based on predicted sales volume
- **Product bundling** based on high-performing SKUs
- Budgeting and **strategic planning** aligned with seasonal trends

---


## 🚀 Next Steps

- Build a **Power BI or Streamlit dashboard** to make this project interactive
- Apply **advanced clustering (DBSCAN or Hierarchical)** for deeper segmentation
- Introduce **promotion or marketing campaign data** to evaluate effectiveness
- Deploy forecasting app on **Streamlit Cloud** or **HuggingFace Spaces**

---

## 🧑‍💼 Author

**Vaishnav Vadrevu**  
Data & Business Analyst | Machine Learning Enthusiast  
📧 [vadrevuvaishnav9320@outlook.com]  
🔗 [[LinkedIn Profile](https://www.linkedin.com/in/vaishnav-vadrevu-li1qa1ba/)]  

---

## ⭐ If you liked this project...
Give it a ⭐ on GitHub and feel free to fork, clone, and adapt it for your use. Contributions welcome!



