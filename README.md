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
| **Products** | Contains product-level-details, including prices and inventory |
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
- **KPIs**: Revenue, Gross Profit, Orders, AOV (Average Order Value), Average Monthly Revenue, MoM Growth.
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

## 💡 Dashboard Highlights & Observations

### Sales
- 📈 Total Revenue: **$1.27M** over three years.
- 📅 Avg Monthly Revenue:	**$105.48K**
- 📉 Revenue Trends:
    * The highest revenue was observed in April 1998.
    * Average Monthly Revenue Growth 1996–1997 shows an increase of **48.28%**
    * Average Monthly Revenue Growth 1997–1998 shows an even bigger increase of **71.37%**
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
- 🛍️ Best-Selling Products: Camembert Pierrot **1.6K units**, Raclette Courdavault **1.5K units**.
- 🗂️ Several high-performing products are **out of stock**, such as **Alice Mutton** and **Chef Anton’s Gumbo Mix**, risking revenue loss.

### RFM Segmentation
- 📁  Customers are segmented as: 
   * **Champions** with **21.98%**
   * **Loyal Customers** with **20.88%**
   * **At risk** with **30.77%**
   * **Needs attention** with **26.37%**

 The biggest opportunity lies in the **At Risk** and **Needs Attention** segments. Together, they represent over **57%** of our customers, and unlocking value here can drive major growth.

- 📁  Customers are segmented as: 
   *  **Platinum**: spent more than **$10K** with **71.76%**
   *  **Gold**: spent more than **$5K** with **18.68%**
   *  **Silver**: spent more than **$1K** with **31.87%**
   *  **Bronze**: spent less than or equal **$1K**, or made **no purchases** yet with **7.69%**

---

## 🧠 Insights

1. High conversion and repeat purchase rates indicate an efficient conversion funnel & strong customer loyalty.
2. Revenue is heavily concentrated in the top customers and specific regions, making retention and regional focus critical.
3. The average MoM Growth of 1996–1997 shows an increase of **48.28%**, while the average MoM Growth of 1997–1998 shows an even bigger increase of **71.37%**, which confirms that the significant increase in the YoY growth of 1996-1997 of **196.56%** is due to partial 1996 data and the sharp decline in the YoY growth of 1997-1998 of **-28.60%** is due to partial 1998 data.

---

## 📌 Recommendations

1. **Inventory Management**  
   - Implement automated stock alerts for low stock.
   - Prioritize restocking high-demand items, such as Camembert Pierrot and Raclette Courdavault, as well as high-revenue products.

2. **Customer Retention Strategies**  
   - Launch email marketing based on RFM segmentation.
   - Personalize offers for "At Risk" and "Need Attention" segments to focus on converting them into "Loyal Customers" or "Champions"
     
3. **Nurture Top Customers**
  
   Launch loyalty or VIP programs to retain high-value accounts and reduce churn risk.

4. **Expand Strong Markets**  

   Leverage strong markets (USA, Germany) while exploring growth opportunities in emerging cities like Graz and Boise.

---

## 📍 Dashboard & Report

📊 [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiM2U2NDI2NDMtZDJiYS00MzE1LWFkNGUtZDBiMWJjYWQwNzFhIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9) 

📎 [Full Report (PDF)](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/E-commerce%20Data%20Analysis%20Report.pdf)  

---

## 🖼️ Dashboard Preview

### Sales Analysis
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/Sales.PNG)

### Customer Analysis
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/Customer.PNG)

### Product Analysis
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/Product.PNG)

### RFM Segmentation
![](https://github.com/ReemSaeedMetwally/E-commerce_Data_Analysis_Dashboard/blob/main/images/RFM%20Segmentation.PNG)
