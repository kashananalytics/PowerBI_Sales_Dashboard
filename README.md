<img width="1600" height="912" alt="WhatsApp Image 2026-05-13 at 11 33 54 PM" src="https://github.com/user-attachments/assets/171a82d6-f587-43ae-baef-25823344bd26" />
# 📊 Analytical Sales Dashboard — Power BI

> Transforming raw sales data into a clear, interactive dashboard that shows exactly where revenue is coming from, which brands are profitable, and how each supervisor is performing.

---

## 📸 Dashboard Preview

> *(Add your dashboard screenshot here)*

---

## 📌 Project Summary

This project takes a complete sales dataset covering 13+ product categories and 11 brands and turns it into a fully interactive **Power BI dashboard**. The goal was simple — make it easy to see the full picture of sales performance without digging through rows of spreadsheet data.

**At a glance:** 99M total sales · 76M total cost · 23M total profit · 13K quantity · 5K transactions

---

## 🔢 KPI Cards

| KPI | Value |
|---|---|
| 💰 Total Sales | 99M |
| 📦 Total Cost | 76M |
| 📈 Total Profit | 23M |
| 🛒 Quantity Sold | 13K |
| 🔄 Total Transactions | 5K |

---

## 📊 Visuals Built

**1. Bar Chart — Quantity by Category**
Ranks all 13 product categories by units sold. Monitor leads with 1,843 units, followed by Mouse (1,496) and CPU (1,450). Printer sits at the bottom with 357 units.

**2. Area Chart — Profit by Brand**
Shows profit trend across 11 brands. Intel tops the chart at 4.3M, followed by Samsung (3.7M) and Dell (3.3M). Asus sits at the bottom with 0.7M.

**3. Pie Chart — Product Share by Brand**
Breaks down brand contribution to total product mix. Samsung leads at 24%, followed by Dell (18%) and Intel (12%).

**4. Bing Map — Cities**
Geographic view of sales locations — plots city-level data points across the region.

**5. Supervisor Slicer**
One-click filtering by supervisor — Aadil Khan, Abrar Akbar, Fatima Khan, Mubashir Khan, Rehan Shah, and Umar Hayat. All visuals update instantly.

---

## 🧮 Key DAX Measures

```dax
-- Total Sales
Total Sales = SUM('Sales'[Sale Amount])

-- Total Profit
Total Profit = SUM('Sales'[Sale Amount]) - SUM('Sales'[Cost])

-- Profit Margin %
Profit Margin = DIVIDE([Total Profit], [Total Sales])

-- Total Transactions
Total Transactions = COUNTROWS('Sales')

-- Quantity Sold
Total Quantity = SUM('Sales'[Quantity])
```

---

## 🛠️ Tools Used

- **Microsoft Excel** — raw data source
- **Power Query** — data cleaning & transformation
- **Power BI Desktop** — dashboard design & layout
- **DAX** — custom KPI measures & calculations
- **Bing Maps** — geographic city mapping

---

## 💡 Key Insights

- 🏆 **Intel generates the highest profit** at 4.3M — nearly 20% of total brand profit
- 🖥️ **Monitor is the top-selling category** with 1,843 units sold
- 📉 **Profit margin is 23%** — healthy but with room to reduce cost on low-margin brands
- 🗺️ **Geographic data** shows city-level sales concentration across the region
- 👤 **Supervisor filter** makes it easy to track individual team performance

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use the supervisor slicer on the left to filter by team member
4. Click any bar, brand, or pie slice to cross-filter all visuals instantly

---

*Built as a portfolio project. Feel free to fork, adapt, or use the DAX measures for your own sales or business analytics dashboards.*

## Author
Kashan Ahmed  
BS Statistics Graduate | Power BI & Data Analytics.
