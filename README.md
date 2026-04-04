# 🍽️ Restaurant Sales Analysis

> Analyzing 500 orders across 8 months to uncover revenue patterns, peak hours, and item performance.

---

## 📌 Project Overview

A local restaurant wanted to understand **what drives revenue** — which items sell best, when customers order most, and which payment methods dominate. This analysis transforms raw order data into a clear, actionable Excel dashboard that answers those questions at a glance.

**Business Questions Answered:**
- When is the restaurant busiest, and what's the revenue impact?
- Which menu items and categories generate the most revenue?
- How do weekday vs. weekend sales compare?
- What payment methods do customers prefer?

---

## 📊 Dataset

| Detail | Value |
|---|---|
| Source | Simulated restaurant order data |
| Time Period | January 2025 – August 2025 |
| Total Orders | 500 transactions |
| Total Items Sold | 1,515 items |
| Columns | Order ID, Customer Name, Food Item, Category, Quantity, Price, Payment Method, Order Time |

**Menu Categories:** Dessert · Main · Starter

**Payment Methods:** Cash · Credit Card · Debit Card · Online Payment

---

## 🛠️ Tools Used

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Pivot_Tables-217346?style=flat&logoColor=white)

**Techniques:** Data Cleaning · Calculated Columns · Pivot Tables · KPI Cards · Dashboard Design · Slicers

---

## ⚙️ Process

### 1. Data Cleaning & Preparation
- Added calculated columns: `Cost` (60% of price), `Total Sales`, `Profit`, `Profit Margin`
- Extracted time features: `Month`, `Day`, `Day Type` (Weekday/Weekend), `Hour`, `Time Period`
- Categorized items by price tier: Budget / Mid-Range / Premium

### 2. Analysis (Pivot Tables)
- Revenue aggregated by Month, Category, Item, Time Period, Payment Method, and Day Type
- KPIs calculated: Total Revenue, Total Profit, Profit Margin, Avg Items/Order

### 3. Dashboard
- Built interactive Excel dashboard with slicers for Month, Category, and Payment Method
- Visualizations: Line chart (monthly trend), Donut (category split), Bar charts (items + time periods + payment), Pie (day type)

---

## 📈 Dashboard Preview

![Restaurant Sales Dashboard](screenshots/dashboard.png)

---

## 💡 Key Insights

| # | Finding |
|---|---|
| 1 | **Morning is peak revenue** — $9,427 (47% of daily revenue), nearly 2× the afternoon |
| 2 | **August was the worst month** — $1,057 in sales, a sharp drop from July's $3,314 |
| 3 | **Pizza is the top-selling item** at $2,628, while Ice Cream is the lowest at $1,703 |
| 4 | **Weekdays dominate** — $14,655 vs. $5,368 on weekends (2.7× higher) |
| 5 | **Credit Card & Cash together account for ~52% of revenue** |
| 6 | **80% profit margin** across all transactions — strong unit economics |
| 7 | **Avg order contains 3 items** — customers regularly combine multiple items per visit |

---

## 📁 Repository Structure

```
restaurant-sales-analysis/
├── README.md
├── restaurant_orders.xlsx       ← Raw + cleaned data with all sheets
├── screenshots/
│   └── Dashboard.png                ← Dashboard preview
```

---

## 🚀 How to Use

1. Download `restaurant_orders.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Navigate to the **Dashboard** sheet
4. Use the slicers (Month / Category / Payment) to filter the view

---

## 👤 Author

**Youssef Mohamed** — Aspiring Data Analyst  
📍 Egypt | 💼 [LinkedIn](https://www.linkedin.com/in/youssef-mohamed00/) | 📧 youssefmramadan0.0@gmail.com
