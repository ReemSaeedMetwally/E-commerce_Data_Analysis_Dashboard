# 📦 E-commerce Data Analysis Dashboard

This project provides an end-to-end data analysis and interactive visualization of an e-commerce dataset using **Power BI**. The dashboard provides stakeholders with a 360-degree view of business performance, encompassing sales, customer behavior, product trends, and RFM segmentation.

---

## 🔍 Project Objectives

- Analyze revenue growth trends over time.
- Identify top-performing products, categories, and customers.
- Monitor customer conversion, retention, and purchasing frequency.
- Detect inventory and supply chain inefficiencies.
- Segment customers using Recency, Frequency, and Monetary (RFM) metrics.

---

## 🗃️ Dataset Description

The dataset comprises the following structured tables:

| Table         | Description |
|---------------|-------------|
| **Customers** | Includes customer names, contact details, cities, and countries |
| **Categories** | Contains product category names and descriptions |
| **Products** | Contains product-level details, including prices and inventory |
| **Orders** | Includes sales order metadata, including order date, shipping location, and freight |
| **OrderDetails** | Transaction-level data including quantities, unit prices, and discounts |

---

## 🛠️ Skills and Tools

- Skills: ETL with Power Query, Data wrangling, Data Cleaning, Feature Engineering, Dashboard Design, Business Insight Extraction, KPI Reporting, Story-telling.
- Tools:
  * **Microsoft Excel**: Data wrangling and transformation
  * **Power BI**: Data visualization and interactive dashboards
  * **DAX**: Custom measures, KPIs, and dynamic filtering logic

---

## 📊 Dashboard Overview

The E-commerce Dashboard is divided into four interactive sections:

### 1. 📈 **Sales Analysis**
- **KPIs**: Revenue, Orders, AOV (Average Order Value), YOY Growth.
- **Trends**: Monthly revenue comparison across 1996, 1997, and 1998.
- **Geographic Analysis**: Top countries and cities by revenue.
- **Weekly Sales Patterns**: Daily sales trends for operational insights.

### 2. 👥 **Customer Analysis**
- **KPIs**: Conversion Rate, Repeat Purchase Rate, CLTV (Customer Lifetime Value).
- **Funnel**: Lead → Paid → Repeat.
- **Top Customers**: Highest revenue contributors.
- **Demographics**: Country-wise and month-wise customer distribution.

### 3. 🛒 **Product Analysis**
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

## 💡 Insights & Observations

### Sales
- 📈 Total Revenue: **$1.27M** over three years.
- 📉 Revenue Trends:
    * The highest revenue was observed in April 1997.
    * Massive growth from 1996 to 1997: **+196.56%**.
    * Decline in 1998: **-28.60%**, indicating possible lower customer acquisition, stockouts, macro trends, churn, or market saturation.
- 🌍 Top Revenue Countries:
    * **USA**: $245.68K
    * **Germany**: $226.92K
- 🏙️ Top Cities: **Cunewalde** is the top city by revenue, despite being a lesser-known location, then **Graz** and **Boise**.
  
### Customers  
- 🧍‍♀️ High Conversion rate with **97.8%** from leads to paying customers.
- 🔁 High customer loyalty with **98.88% repeat rate**.
- 👥 Top Customers by Revenue:
    * QUICK-Stop: **$110K**
    * Ernst Handel: **$105K**
- 🌍 Top Countries by Customer Count: USA, Germany, and France.

### Products
- 📦 Top Categories by Revenue:
    * Beverages **$267.87K**
    * Dairy Products **$234.51K**.
- 🛍️ Best-Selling Products: Camembert Pierrot **1.6K units**, Raclette Courdavault.
- 🗂️ Several high-performing products are **out of stock**, risking revenue loss.

### RFM Segmentation
📁  Customers are segmented as: **Champions** with **21.98%**, **Loyal Customers** with **20.88%**, **At risk** with **30.77%**, and **Needs attention** with **26.37%**.
The biggest opportunity lies in the **At Risk** and **Needs Attention** segments. Together, they represent over **57%** of our customers, unlocking value here can drive major growth.

✅  Recommendations: 
  * Win-back campaigns: email offers, discounts, or feedback surveys.
  * Investigate reasons behind churn (e.g., pricing, stockouts).
  * Target with welcome offers, onboarding flows, or product suggestions.
  * Create nurturing campaigns to build loyalty.

---

## 🚀 Features

- 📅 Dynamic filtering by Year, Month, Country, City, and Product Category.
- 📈 Interactive line and bar charts for time-series and comparative analysis.
- 📍 Geo-insights for identifying market hotspots.
- ⚙️ Inventory intelligence integrated with product sales.
- 📊 RFM segmentation for customer targeting and retention strategy.

---

## 📌 Recommendations

1. **Revive Revenue Growth**  

   Address the 1998 decline by retargeting high-value customers with incentives or win-back campaigns.

3. **Inventory Management**  
   - Implement automated stock alerts for low stock.
   - Prioritize restocking high-demand items, like Camembert Pierrot and Raclette Courdavault, and high-revenue products.

4. **Customer Retention Strategies**  
   - Launch email marketing based on RFM segmentation.
   - Personalize offers for "At Risk" and "Need Attention" segments to focus on converting them into "Loyal Customers" or "Champions"

5. **Expand Strong Markets**  

   Leverage strong markets (USA, Germany) while exploring growth opportunities in emerging cities like Graz and Boise.

---

## 📌 Dashboard & Report

📊 [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDc5Mjk2ZjItN2M4Yi00ZTc0LTkxOTYtM2Q5ZDc0Y2JmMzg5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9) 

📎 [Full Report (PDF)]()  

---

## 🖼️ Dashboard Preview

### Sales Analysis
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/Sales%20Analysis.PNG)

### Customer Analysis
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/Customer%20Analysis.PNG)

### Product Analysis
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/Product%20Analysis.PNG)

### RFM Segmentation
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/RFM%20Segmentation.PNG)
