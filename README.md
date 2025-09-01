# 📊 Blinkit Sales Dashboard (Power BI)

## 📌 Project Overview
This project analyzes sales performance and product trends for **Blinkit (India’s Last Minute App)**.  
The dashboard provides insights into:
- **Total Sales**: $1.20M
- **Average Sales per Item**: $141
- **Number of Items**: 9K
- **Average Rating**: 4

---

## 🛠 Tools & Technologies
- **Power BI** (Data Visualization & Dashboarding)
- **DAX** (Measures & Calculations)
- **Excel** (Data Source)

---

## 📑 Key Insights
- **Top Performing Items**: Fruits & Snacks drive the highest revenue.
- **Outlet Size & Location**: Tier 3 outlets generate maximum sales (~$472K).
- **Outlet Type**: Supermarket Type1 contributes the highest sales ($787K).
- **Customer Ratings**: Average rating across all outlets is **4.0**.

---

## 📂 Data Model
The data model consists of:
- **BlinkIT Grocery Data**: Item details, fat content, weight, visibility, outlet info.
- **Metrics Table**: Custom DAX measures for sales and rating KPIs.

![Data Model](./Dashboard-Screenshots/data-model.png)

---

## 📊 Dashboard Preview
Here is the final dashboard view:

![Dashboard](./Dashboard-Screenshots/dashboard-overview.png)

---

## 📜 DAX Measures Used
Some of the DAX formulas:
```DAX
Total Sales = SUM(BlinkIT_Grocery_Data[Sales])
Average Sales = AVERAGE(BlinkIT_Grocery_Data[Sales])
No. of Items = COUNT(BlinkIT_Grocery_Data[Item Identifier])
Average Rating = AVERAGE(BlinkIT_Grocery_Data[Rating])

