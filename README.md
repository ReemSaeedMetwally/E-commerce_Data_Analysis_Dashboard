# 📦 E-commerce Data Analysis Dashboard

This project presents a comprehensive Power BI dashboard analyzing an e-commerce dataset, providing insights into sales trends, customer behavior, product performance, and RFM segmentation. The dashboard is designed for business stakeholders to monitor performance and make data-driven decisions.

---

## 📊 Dashboard Overview

The E-commerce Dashboard is divided into four interactive sections:

### 1. 🛒 **Sales Analysis**
- **KPIs**: Revenue, Orders, AOV (Average Order Value), YOY Growth.
- **Trends**: Monthly revenue comparison across 1996, 1997, and 1998.
- **Geographic Analysis**: Top countries and cities by revenue.
- **Weekly Sales Patterns**: Daily sales trends for operational insights.

### 2. 👥 **Customer Analysis**
- **KPIs**: Conversion Rate, Repeat Purchase Rate, CLTV (Customer Lifetime Value).
- **Funnel**: Lead → Paid → Repeat.
- **Top Customers**: Highest revenue contributors.
- **Demographics**: Country-wise and month-wise customer distribution.

### 3. 📦 **Product Analysis**
- **Category Performance**: Revenue, quantity sold, and discount amounts.
- **Top Products**: By revenue and by units sold.
- **Inventory Insights**: Products out of stock or requiring reordering.
- **Operational Metrics**: Avg items per order, shipping cost as % of revenue.

### 4. 🧠 **RFM Segmentation**
- **Scoring**: Recency, Frequency, and Monetary value scoring for customers.
- **Segments**: Champion, Loyal, At Risk, Needs Attention, etc.
- **Tiering**: Platinum, Gold, Silver, Bronze.
- **Customer-Level Details**: Score table for micro-targeting.

---

## 🗃️ Dataset

- **Source**: [Kaggle / Fictional E-Commerce Dataset] (Assumed or customize based on your data)
- **Time Frame**: 1996 – 1998
- **Key Fields**: Order ID, Customer ID, Product, Category, Quantity, Revenue, Discount, Shipping Cost, Order Date, etc.

---

## 💡 Insights & Observations

- 📉 Revenue dropped by **28.60%** in 1998—potential factors include lower customer acquisition, stockouts, or macro trends.
- 🌍 **USA** and **Germany** generated the highest revenue.
- 🏙️ **Cunewalde** is the top city by revenue, despite being a lesser-known location.
- 🛍️ **QUICK-Stop** and **Côte de Blaye** (product) are top customer and product contributors respectively.
- 🔁 High customer loyalty with **98.88% repeat rate**.
- 📉 Several high-performing products are **out of stock**, risking revenue loss.

---

## 🚀 Features

- 📅 Dynamic filtering by Year, Month, Country, City, and Product Category.
- 📈 Interactive line and bar charts for time-series and comparative analysis.
- 📍 Geo-insights for identifying market hotspots.
- ⚙️ Inventory intelligence integrated with product sales.
- 📊 RFM segmentation for customer targeting and retention strategy.

---

## 🛠️ Tools Used

- **Power BI**: Dashboard creation and visualization
- **DAX**: Measures and KPIs (e.g., CLTV, AOV, Repeat Rate)
- **Power Query**: Data transformation and modeling
- **Excel / CSV**: Initial dataset handling

---

## 📁 Project Structure

```bash
📦 E-commerce-Dashboard
├── 📊 Power BI Dashboard (.pbix)
├── 📁 Screenshots/
│   ├── 1.PNG (Sales View)
│   ├── 2.PNG (Customer View)
│   ├── 3.PNG (Product View)
│   └── 4.PNG (RFM View)
├── 📄 README.md
└── 📁 Data/ (Optional raw data CSVs)
