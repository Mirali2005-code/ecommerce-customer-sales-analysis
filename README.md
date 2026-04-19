# ecommerce-customer-sales-analysis
E-commerce sales analysis using Python and Power BI with customer insights and business KPIs
# 📊 E-commerce Sales & Customer Behavior Analysis

## 🧠 Business Problem

E-commerce companies generate massive transaction data, but **raw data alone doesn’t drive decisions**.

This project answers key business questions:

* What is driving revenue growth?
* Which customers are most valuable?
* Are customers returning or churning?
* Which products and regions should we invest in?

---

## 🎯 Objective

Build an end-to-end analytics solution to:

* Transform raw transactional data into actionable insights
* Track business performance using KPIs
* Analyze customer behavior and retention patterns
* Support data-driven decision making

---

## 📂 Dataset

* Source: Kaggle Online Retail Dataset
* Contains transactions, customers, products, and geography

---

## 🧹 Data Preparation (Python)

Performed using **Pandas**:

* Removed missing `CustomerID`
* Filtered negative/invalid transactions
* Converted `InvoiceDate` to datetime
* Created `TotalPrice = Quantity × UnitPrice`
* Generated time-based features for analysis

---

## 📊 Dashboard Overview (Power BI)

### 🔑 Key KPIs

* **Total Revenue:** 8.91M
* **Total Orders:** 19K
* **Total Customers:** 4,339
* **Average Order Value (AOV):** 480.76
* **Profit:** 3.56M
* **Profit Margin:** 40%
* **Repeat Customer Rate:** 98%
* **Month-over-Month Growth:** 6%

---

### 📈 Analytics Included

#### 1. Revenue Analysis

* Monthly revenue trends
* Growth tracking (MoM)

#### 2. Customer Analytics

* Customer segmentation (RFM-based)
* Repeat vs new customer behavior
* Customer value contribution

#### 3. Product Performance

* Top products by revenue
* High-value product identification

#### 4. Geographic Insights

* Revenue contribution by country
* Identification of key markets

---

## 🔍 Key Business Insights

* 📈 Revenue increased significantly after September (seasonal demand trend)
* 🌍 United Kingdom contributes the majority of total revenue
* 💎 High-value customers drive the largest share of revenue
* 🔁 Strong repeat customer behavior indicates high retention
* 🛍 A small set of products contributes disproportionately to revenue

---

## 💡 Business Recommendations

* Invest more in high-performing regions (e.g., UK market)
* Focus marketing efforts on high-value customer segments
* Promote top-performing products for higher ROI
* Leverage retention strategies (loyalty programs, remarketing)

---

## 🛠 Tech Stack

* **Python** (Pandas, Matplotlib)
* **Power BI**
* **DAX**

---

## 📸 Dashboard Preview

![Dashboard](images/dashboard.png)

---

## 🚀 Project Impact

This project demonstrates:

* End-to-end data analytics workflow
* Strong understanding of business KPIs
* Ability to convert data into actionable insights

---

## 📌 Future Improvements (Next Steps)

* Cohort analysis for retention tracking
* Customer lifetime value (CLV) modeling
* Advanced forecasting (time-series)
* A/B testing insights

---

## 🤝 Connect

If you found this useful or want to collaborate, feel free to connect!
