# 📊 TASK8: Superstore Sales Dashboard – Power BI Project

## 🎯 Task Objective
This project presents a **interactive sales dashboard** built using **Power BI**, based on the Superstore dataset. It visualizes performance across **time (Month-Year)**, **product category**, and **region**, along with added cards and visual charts for better insights.

---
## 🛠 Tools Used

- Microsoft Power BI (Desktop)
- Excel (optional for initial checks)
- DAX (for calculated columns and measures)
---

## 📁 Dataset


🔄 Data Preparation Steps

1. **Imported Dataset** into Power BI.
2. Created a `MonthYear` column:
   ```DAX
   MonthYear = FORMAT([order_date], "MMM YYYY")
   
- **Source File:** `CLEANED_DATASET.xlsx`
- **Main Columns Used:**
  - `order_date`
  - `region`
  - `category`
  - `state`
  - `sales`
  - `profit`
  - `monthyear`
---
## 📊 Visuals Used

| Visual        | Purpose                            |
|---------------|-------------------------------------|
| 📈 Line Chart | Show sales trend by Month-Year      |
| 📊 Bar Chart  | Compare regional sales performance  |
| 🍩 Donut Chart| Show sales by product category      |
| 🧩 Slicer     | Filter data by region               |
| 🃏 Cards      | Display key metrics (top state, sales) |

---

## ⚙️ Dashboard Highlights (Summary)

- 📍 Regional and State-level Sales Breakdown
- 🧠 Category-wise Sales Performance
- 📈 Time Series Trend by Month-Year
- 🎯 KPIs and Cards for Quick Insights
- 🎨 Clean and Interactive Visual Design

---

## 🎨 Design Principles Followed

- Simple and clean layout with minimal clutter
- Consistent color use to highlight performance areas
- Chronological sorting of time series using custom columns
- Cards and tooltips for quick metrics access
- Interactive slicers for dynamic filtering
- Titles and labels for clarity and ease of understanding

---

## 💼 Business Insights

- High performance in the **West region** signals strong market presence.
- **Technology** category could be prioritized for further investment.
- Regional comparison reveals underperformance in the **South**, needing attention.
- **Time-based trends** (sales spikes in March and Nov) can guide seasonal campaigns.
- **California** is a key revenue driver and should be supported accordingly.

---

## 📦 Deliverables

- ✅ Power BI Dashboard file (`.pbix`)
- ✅ screenshot of final dashboard
- ✅ `README.md` documenting the project
- ✅ List of 3–5 business insights in a clear format

---

## 🎓 Learning Outcome

- Learned how to import and clean data in Power BI.
- Created custom columns for date formatting and sorting.
- Built interactive visuals: line, bar, donut, map, and slicer.
- Wrote DAX measures to extract business metrics (e.g., top state).
- Designed a dashboard to present data visually and derive insights.

---
## 👤 Report By
Yash Patel 
23-05-2025

