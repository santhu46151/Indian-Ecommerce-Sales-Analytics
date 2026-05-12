# 🛒 Indian E-Commerce Sales Analytics Dashboard

> End-to-end sales analytics project using Microsoft Excel and Power BI on a simulated Indian e-commerce dataset of 1,000+ orders across 12 months, 10 states, and 5 product categories.

---

## 📌 Project Overview

This project analyses Indian e-commerce sales data to uncover revenue trends, category performance, regional patterns, and customer payment behaviour. The goal is to demonstrate real-world data analytics skills — from raw data cleaning to interactive dashboard creation.

| Detail | Info |
|---|---|
| **Dataset** | Simulated Indian E-Commerce Orders (2024) |
| **Records** | 1,000+ orders |
| **Time Period** | January 2024 – December 2024 |
| **Tools Used** | Microsoft Excel · Power BI |
| **Skills** | Data Cleaning · Pivot Tables · Data Visualisation · DAX · Business Intelligence |

---

## 📊 Key Findings

- 📈 **Festive season (Oct–Dec) drives 35%+ of annual revenue** — Q4 is the peak quarter by a significant margin, consistent with Indian shopping trends (Diwali, Dussehra, year-end sales)
- 💻 **Electronics is the top revenue category** despite having fewer orders — high average order value (₹8,000–₹17,000) drives this
- 📱 **UPI is the #1 payment method** — accounts for the largest share of transactions, reflecting India's digital payment growth
- 🗺️ **Telangana and Maharashtra lead state-wise revenue** — metro states consistently outperform Tier-2 regions
- 🔄 **Return rate is under 5%** — a healthy benchmark indicating strong product-customer fit
- 📣 **Social Media channel shows highest average order value** — targeted ads attract higher-spending customers

---

## 📁 File Structure

```
📦 Indian-Ecommerce-Sales-Analytics
 ┣ 📊 Ecommerce_Sales_Analytics_Santhosh_Kumar_Kalla.xlsx
 ┃ ┣ 📋 Sheet 1 — Raw Data          (1,000+ order records)
 ┃ ┣ 📈 Sheet 2 — Dashboard Summary (KPIs, tables, insights)
 ┃ ┣ 📉 Sheet 3 — Charts & Pivots   (pivot tables + embedded charts)
 ┃ ┗ 📖 Sheet 4 — Power BI Guide    (step-by-step Power BI instructions)
 ┗ 📄 README.md
```

---

## 🗂️ Dataset Description

The dataset simulates realistic Indian e-commerce transactions with the following fields:

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Month | Month of order (Jan–Dec) |
| State | Indian state (10 states including Telangana, Maharashtra, Karnataka etc.) |
| Category | Product category (Electronics, Clothing, Home & Kitchen, Books, Sports) |
| Product | Specific product name |
| Unit Price (₹) | Price per unit in Indian Rupees |
| Quantity | Number of units ordered |
| Discount (%) | Discount applied (0–20%) |
| Revenue (₹) | Final revenue after discount |
| Payment Method | UPI, Credit Card, Debit Card, Net Banking, COD |
| Channel | Sales channel (App, Website, Social Media) |
| Order Status | Delivered, Returned, or Cancelled |

---

## 📐 Excel Dashboard Features

### Sheet 2 — Dashboard Summary
- **5 KPI Cards** — Total Orders, Total Revenue, Avg Order Value, Top Category, Return Rate
- **Monthly Revenue Table** — with MoM (Month-on-Month) growth formula
- **Category Performance Table** — revenue, orders, avg price, % of total
- **Top States by Revenue** — ranked table with % contribution
- **Payment Method Breakdown** — orders and revenue split by payment type
- **Key Insights Section** — 6 business insights derived from the data

### Sheet 3 — Charts & Pivots
- **Line Chart** — Monthly Revenue Trend (Jan–Dec 2024)
- **Bar Chart** — Revenue by Product Category
- **Pivot Tables** — ready to connect to Power BI

### Sheet 4 — Power BI Guide
- 11 step-by-step instructions to build the full Power BI dashboard
- Includes DAX measures, slicer setup, map visual, and KPI cards

---

## ⚙️ How to Use

### Excel
1. Download `Ecommerce_Sales_Analytics_Santhosh_Kumar_Kalla.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Navigate between sheets using the tabs at the bottom
4. All formulas are pre-calculated — no setup needed

### Power BI
1. Open Power BI Desktop
2. Go to **Get Data → Excel** → select the downloaded file
3. Load the **Raw Data** sheet
4. Follow the 11 steps in **Sheet 4 (Power BI Guide)** to build the full dashboard
5. Key DAX measures to create:
```
Total Revenue = SUM('Raw Data'[Revenue (₹)])
Total Orders = COUNTROWS('Raw Data')
Avg Order Value = DIVIDE([Total Revenue],[Total Orders])
Return Rate = DIVIDE(CALCULATE([Total Orders],'Raw Data'[Order Status]="Returned"),[Total Orders])
```

---

## 🧠 Skills Demonstrated

| Skill | Where Applied |
|---|---|
| Data Cleaning | Raw Data sheet — consistent formatting, data types |
| Pivot Tables | Charts & Pivots sheet |
| Excel Formulas | MoM growth, averages, % of total, KPI calculations |
| Data Visualisation | Embedded line and bar charts |
| Business Intelligence | KPI cards, insight generation |
| DAX (Power BI) | Measure creation guide in Sheet 4 |
| Storytelling with Data | Key Insights section — translating numbers to decisions |

---

## 👨‍💻 About the Analyst

**Santhosh Kumar Kalla**
BTech Data Science student at Malla Reddy College of Engineering & Technology, Hyderabad.

- 🔗 [LinkedIn](https://www.linkedin.com/in/santhoshkumarkalla)
- 📧 Open to Data Analyst / Data Science roles in Hyderabad & Remote

---

## 📜 License

This project uses a simulated dataset created for educational and portfolio purposes. Free to use and adapt with attribution.

---

*Built with Microsoft Excel · Designed for Power BI · Made in Hyderabad 🇮🇳*
