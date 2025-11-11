## 🛍️  Retailed-Sales-Anlaysis Dashboard

📘 Project Overview

The Retail Sales Analysis Dashboard provides key insights into sales performance, profitability, and customer trends using transactional data.
It helps businesses understand which products, categories, and customer segments drive revenue and profit over time.
It helps management analyze sales trends, profitability and customer behavior for better business decisions.It allows users to explore performance by month, gender, and product category, helping retailers understand what drives their revenue and profit.


---
## 🎯 Project Objectives

- Visualize **total sales** and **order trends** in one dashboard.  
- Analyze performance by **product category, gender, and age group**.  
- Identify **top-performing months** and **customer segments**.  
- Create an **interactive and dynamic dashboard** with filters and highlights.  
- Generate **automated insights** using Smart Narrative visual.
---
  
## 📂 Dataset Information

| Column Name          | Description                                                    |
| -------------------- | -------------------------------------------------------------- |
| **Transaction ID**   | Unique identifier for each transaction                         |
| **Date**             | Date of the transaction                                        |
| **Month**            | Month extracted from the transaction date                      |
| **Year**             | Year of the transaction                                        |
| **Day**              | Day of the month                                               |
| **Day Name**         | Name of the weekday (e.g., Monday, Tuesday)                    |
| **Customer ID**      | Unique identifier for each customer                            |
| **Gender**           | Gender of the customer (Male/Female)                           |
| **Product Category** | Category of the purchased product                              |
| **Quantity**         | Number of units sold in the transaction                        |
| **Price per Unit**   | Selling price per item                                         |
| **Total Sales**      | Total revenue from the transaction (Quantity × Price per Unit) |
| **Profit**           | Profit earned per transaction                                  |
| **Profit Margin**    | Profit percentage on total sales                               |
| **Avg Discount**     | Average discount applied on the product                        |


---

🎯 Project Objectives

- Identify top-performing product categories and their sales contribution.
- Analyze sales and profit trends across different months and years.
- Study the impact of discounts on total sales and profit margins.
- Evaluate customer behavior by gender and purchasing patterns.
- Visualize monthly and seasonal performance trends.

--- 

| **KPI Name**                      | **Description / Insight**                        | **DAX Formula (Power BI)**                                                      |
| --------------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------------- |
| 🏆 **Total Sales**                | Measures total revenue from all transactions     | `Total Sales = SUM(Sales[Total Sales])`                                         |
| 💰 **Total Profit**               | Calculates total profit across all sales         | `Total Profit = SUM(Sales[Profit])`                                             |
| 📈 **Profit Margin (%)**          | Shows profitability percentage relative to sales | `Profit Margin (%) = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Total Sales])) * 100` |
| 👥 **Total Customers**            | Counts unique customers                          | `Total Customers = DISTINCTCOUNT(Sales[Customer ID])`                           |
| 📦 **Total Quantity Sold**        | Total units sold across all products             | `Total Quantity = SUM(Sales[Quantity])`                                         |
| 🛍️ **Average Order Value (AOV)** | Average revenue per transaction                  | `Avera                                                                          |

---

🧭 Recommended KPI Cards in Power BI

You can display these metrics as KPI Cards or Summary Tiles at the top of your dashboard:
- Total Sales 💰
- Total Profit 📈
- Profit Margin (%) 💹
- Total Customers 👥
- Total Quantity Sold 📦
- Average Discount (%) 💸
- Monthly Sales Growth (%) 📊

---

## 📈 Visuals Used  

- 📅 Line Chart – Monthly Sales Trend
- 🏔️ Area Chart – Profit Over Time
- 🔄 Line & Clustered Column Chart – Sales vs Avg Discount
- 👥 Stacked Column Chart – Sales by Month & Gender
- 🍩 Pie / Donut Chart – Category Contribution
- 📋 Table  – Monthly sales and profit summary
- ⚙️ Gauge Chart – Sum of Quantity

---

  ## 🎛️ Filters (Slicers) Used
  
| **Slicer**   | **Field**        | **Function**                                       |
| ------------ | ---------------- | -------------------------------------------------- |
| **Year**     | Year             | Filter visuals to display data for a specific year |
| **Gender**   | Gender           | View and compare sales performance by gender       |
| **Day Name** | Day Name         | Analyze daily trends (e.g., weekday vs weekend)    |
| *(Optional)* | Month            | Focus on sales and profit for a selected month     |
| *(Optional)* | Product Category | View performance for specific product categories   |
| *(Optional)* | Customer ID      | Analyze purchase patterns of individual customers  |

  
---

## 🛠️ Tools Used  

- Microsoft Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- Excel / CSV Dataset  

---

## 📷 Dashboard Preview  
<img width="1311" height="734" alt="Screenshot 2025-11-10 221942" src="https://github.com/user-attachments/assets/6700e6fb-9aff-473d-b327-44a039421aca" />



---

<img width="1149" height="646" alt="Screenshot 2025-11-09 152820" src="https://github.com/user-attachments/assets/600d336a-77be-427c-a6bc-4b062494eeac" />


---

## 📎 Author  

**👤 Name:** Harshada Pawar
**📧 Email:** [harshadapawar4912@gmail.com](mailto:prafullwahatule@gmail.com)  
**💻 GitHub:** [harshada4912](https://github.com/harshada4912)  
---
