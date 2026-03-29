# ☕ Coffee Shop Sales Analysis Dashboard — Excel

> **End-to-end Excel analytics project** — from raw transactional data to an interactive business dashboard — uncovering peak hours, top products, and store performance insights for a multi-location coffee shop chain.

---

## 🧩 Business Problem

A coffee shop chain with multiple locations needed clarity on three core questions:

- **When** are customers ordering — and are we staffed correctly for peak hours?
- **What** products drive the most revenue — and which underperform?
- **Where** are the strongest and weakest store locations — and why?

This dashboard transforms raw POS transaction data into actionable answers for store managers and business owners.

---

## 📊 Dashboard KPIs at a Glance

| Metric | Value |
|---|---|
| 💰 Total Sales | $156,727.76 |
| 👣 Total Footfall | 33,527 customers |
| 🧾 Avg Bill Per Person | Calculated dynamically |
| 📦 Avg Orders Per Person | Calculated dynamically |

---

## 📁 Project Files

| File | Description |
|---|---|
| `Coffee Shop Sales raw data.xlsx` | Original raw POS transaction records |
| `cafe sales details.xlsx` | Cleaned dataset + final interactive dashboard |
| `dashboard_screenshot.png` | Preview of the completed dashboard |

---

## 🧹 Data Cleaning Process

The raw dataset required significant preprocessing before analysis could begin:

### Missing & Inconsistent Data
- Identified and removed blank values across critical fields — product name, quantity, and revenue
- Standardized inconsistent category labels and product names

### Date & Time Transformation
- Converted raw timestamps into Excel datetime format
- **Extracted Hour** from order timestamp → enabled hourly sales pattern analysis
- **Extracted Day Name** → enabled weekday performance comparison
- **Extracted Month Name** → enabled monthly trend analysis

### Data Structuring
- Ensured numeric columns (quantity, unit price, revenue) were correctly typed for calculations
- Validated and grouped products into logical categories: Coffee, Tea, Bakery, etc.
- Organized final output into a structured table to support Pivot Tables and Charts

---

## 📈 Dashboard Features

### 📊 Visual Insights

| Chart | Business Question Answered |
|---|---|
| Sales by Hour | When is peak demand? Are we overstaffed during slow hours? |
| Category Sales Distribution | Which product categories drive the most revenue? |
| Drink Size Distribution | What sizes do customers prefer — Small, Regular, or Large? |
| Store Location Performance | Which locations lead in footfall vs revenue? |
| Top 5 Products by Revenue | Which individual products should we promote or expand? |
| Orders by Weekday | Which days are busiest — and which need a promotion boost? |

### 🎛️ Interactive Filters (Slicers)
Users can dynamically filter the entire dashboard by:
- **Month** — track seasonal or monthly trends
- **Day of Week** — isolate weekday vs weekend performance

---

## 💡 Key Business Insights

**1. Morning hours drive the most orders**
Peak ordering occurs in the morning, confirming classic coffee shop behavior. Staffing and inventory should be front-loaded to morning shifts to reduce wait times and avoid stockouts.

**2. Coffee dominates revenue — but bakery is the hidden upsell opportunity**
Coffee products lead total sales, with bakery items following. Bundling bakery items with coffee orders (e.g. "add a muffin for X") could increase average bill per person significantly.

**3. Regular and Large sizes outsell Small**
Customers prefer larger sizes — pricing strategy should reflect this. Consider promotional nudges toward Large (e.g. "upgrade for just $0.50").

**4. Revenue per footfall varies across locations**
Some stores generate higher revenue despite similar customer traffic — indicating stronger product mix or upselling behavior. These locations can serve as best-practice benchmarks for underperforming stores.

**5. Weekday patterns reveal promotion opportunities**
Slower weekdays identified in the analysis are prime targets for limited-time offers or loyalty point multipliers to drive traffic.

---

## 🛠️ Tools & Excel Features Used

| Feature | Purpose |
|---|---|
| Data Cleaning | Standardization, null removal, type correction |
| Derived Columns | Hour, Day Name, Month Name extraction |
| Pivot Tables | Dynamic aggregation for all charts |
| Pivot Charts | Visual representation of sales data |
| Slicers | Interactive Month and Day filters |
| Dashboard Design | KPI cards, layout, and formatting |

---

## 🚀 How to Use

1. Download `cafe sales details.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Navigate to the **Dashboard** sheet
4. Use the **Month** and **Day** slicers on the left to filter all visuals dynamically
5. Hover over charts for detailed data tooltips

---




## 👤 Author

**Sanjeeb Sapkota** | Data & Business Analytics | Excel | Power BI | Tableau | Python | SAP B1

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sanjeeb%20Sapkota-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanjeeb-sapkota-07b625226)
[![GitHub](https://img.shields.io/badge/GitHub-sanjeebsapkota-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sanjeebsapkota)

---

*⭐ Star this repo if you found it useful!*
