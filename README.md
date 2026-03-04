# Databel Customer Churn Analysis (Excel Dashboard)

This repository contains an Excel-based churn analysis case study using the Databel telecom dataset.
It includes a ready-to-use dashboard and PivotTable analysis to understand churn drivers, with a focus on competitor-driven churn.

## Open This File First
**Download and open:**
- `Databel_Customer_Churn_Analysis.xlsx`

> If Excel shows a security warning (“Protected View”), click **Enable Editing**.
> Then go to the **Overview** sheet first.

---

## 🧭 How to Navigate the Workbook (Quick Tour)

### 1) Overview (Dashboard)
**Sheet: `Overview`**
- Top KPIs: **Total Customers**, **Churned Customers**, **Churn Rate %**
- Visuals: churn drivers and competitor churn breakdown
- This is the stakeholder-facing view.

### 2) Churn Analysis (Deep Dives)
**Sheet: `Churn Analysis`**
Contains PivotTables that answer:
- Churn by **Churn Category** and **Churn Reason** (Competitor focus)
- Churn by **Unlimited Plan** and **Grouped Consumption**
- Churn by **Intl Plan** and **State** (includes Top 25 states filter + heatmap)
- Churn by **Account Length** and how it differs by **Contract Type**
- Churn by **Age brackets** (10-year groups) with customer count + churn rate

### 3) Databel - Aggregate (Data + Features)
**Sheet: `Databel - Aggregate`**
- Main dataset table: **Aggregate**
- Added fields used in analysis:
  - `Churned` (Yes=1, No=0)
  - `Demographics` (Under 30 / Senior / Other)
  - `Grouped Consumption` (<5 GB / 5–10 GB / 10+ GB)

---

## 🔁 Refresh Instructions (If something looks wrong)
If PivotTables don’t update:
1. Go to **Data → Refresh All**
2. Or click a PivotTable → **Right-click → Refresh**

If you add new data rows:
- Make sure they are added inside the **Aggregate** table so pivots update correctly.

---

## 📌 Key Insights (Summary)
- **Competitor** is the highest contributing churn category.
- **Unlimited plan** customers show higher churn; consumption banding helps validate whether heavy usage drives this.
- **Intl plan churn** varies strongly by **state** (Top 25 states by churn rate are highlighted).
- Churn tends to **decrease as account length increases**, but the pattern differs by **contract type**.

---

## Tools Used
- Microsoft Excel Desktop (Tables, PivotTables, Calculated Fields, Conditional Formatting, PivotCharts)

## Author
Balaji — MSc Data Science, University of Hertfordshire
