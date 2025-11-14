# 📊 Electronics Sales & Profit Analysis Dashboard – Power BI

### 👩‍💻 Author: [Rucha Jadhav]
**Tool Used:** Microsoft Power BI  
**Dataset:** Electronics Sales Data (Excel)  
**Duration:** November 2025  
**Objective:** Analyze sales, profitability, customer, and regional performance using interactive data visualizations.

---

## 🚀 Project Overview
This Power BI dashboard provides a comprehensive analysis of sales and profit performance across different product categories, customers, and regions.  
It was developed as part of a Data Analyst assignment to demonstrate data cleaning, modeling, DAX calculation, and dashboard design skills.

---

## 🧮 DAX Measures Used
- `Total Sales = SUMX(Sales, Sales[Quantity] * Sales[Unit_Price])`  
- `Total Cost = SUMX(Sales, Sales[Quantity] * Sales[Unit_Cost])`  
- `Total Profit = [Total Sales] - [Total Cost]`  
- `Profit Margin = DIVIDE([Total Profit], [Total Sales])`  

---

## 🧠 Key Insights
- Overall Profit Margin: **9.59%**   
-	Top-Selling Product: Printer (~20M in sales)
-	Highest Profit Category: Accessories (~10.2M profit)
-	Lowest Profit Category: Networking (~1.3M profit)
-	Profit Margin Range: 7.74% (Mouse) to 11.37% (Monitor)


---

## 🗂️ Files Included
| File | Description |
|------|--------------|
| `Electronics-Sales-Analysis-Dashboardt.pbix` | Power BI source file |
| `Electronics-Sales-Analysis-Dashboard-Pdf.pdf` | Exported dashboard (PDF) |


---

## 🧰 Skills Demonstrated
- Power Query (data cleaning & transformation)
- DAX (calculated measures & KPIs)
- Data Modeling (relationships, calendar table)
- Interactive Dashboard Design
- Insight Presentation

---


