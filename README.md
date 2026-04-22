# 📞 Call Center Performance Analysis — Excel Dashboard

## 📌 Project Overview

This project analyzes **call center operational data** using Microsoft Excel to uncover insights around agent performance, call resolution efficiency, and customer satisfaction. The goal is to simulate a real-world business analyst workflow — from raw data to an interactive executive dashboard.

> **Tools Used:** Microsoft Excel (Pivot Tables · Charts · Power Query · Conditional Formatting · KPIs)

---

## 🎯 Business Problem

Call centers generate massive volumes of daily data, yet most managers rely on gut feeling to make staffing and training decisions. This project answers key business questions:

- Which agents are consistently top performers — and who needs coaching?
- What time periods see the highest call volume, and are we staffed accordingly?
- Where is customer satisfaction breaking down, and why?
- What percentage of calls are being resolved on first contact?

---

## 📂 Dataset

| Column | Description |
|---|---|
| `Call ID` | Unique identifier for each call |
| `Agent Name` | Name of the handling agent |
| `Date & Time` | Timestamp of the call |
| `Call Duration (min)` | Length of the call in minutes |
| `Call Status` | Resolved / Unresolved |
| `CSAT Score` | Customer Satisfaction Score (1–5) |

> **Dataset size:** ~1,000 rows of simulated call center records

---

## 🛠️ Excel Skills Demonstrated

- **Pivot Tables** — Aggregated agent-wise and date-wise summaries
- **Pivot Charts** — Visual trends for call volume, resolution rate, CSAT
- **Data Cleaning** — Removed duplicates, handled blanks, standardized date formats
- **Conditional Formatting** — Highlighted low CSAT scores and underperforming agents
- **KPI Cards** — Total Calls, Avg Call Duration, Resolution Rate, Avg CSAT
- **Dashboard Design** — Single-page interactive dashboard with slicers

---

## 📊 Dashboard Features

The final dashboard includes:

- ✅ **KPI Summary Bar** — Total Calls · Avg Duration · Resolution Rate · Avg CSAT
- 📅 **Daily & Weekly Call Volume Trends** — Identifies peak traffic days
- 👤 **Agent Performance Comparison** — Side-by-side bar chart of resolution rates
- ⭐ **CSAT Distribution** — Breakdown of satisfaction scores across all calls
- 🔽 **Slicers** — Filter by Agent Name, Month, and Call Status

---

## 💡 Key Insights

1. **Peak call volume falls on Mondays and Fridays** — staffing levels on these days should be reviewed to reduce wait times.
2. **Top 3 agents maintain a resolution rate above 85%** — their handling techniques should be documented as best practices.
3. **Avg CSAT drops below 3.0 for calls exceeding 8 minutes** — longer calls correlate with lower satisfaction, suggesting a need for better scripts.
4. **~22% of calls remain unresolved** — a targeted training program could bring this below 10%.

---

## 📁 Repository Structure

```
Call-Center-Excel-Analysis/
│
├── Call_Center Analysis.xlsx      # Main Excel file with raw data, pivots & dashboard
├── Call Center Dashboard.png      # Dashboard screenshot preview
└── README.md                      # Project documentation
```

---

## 🚀 Future Improvements

- [ ] Migrate data to **SQL** for scalable querying and multi-table joins
- [ ] Rebuild dashboard in **Power BI** for real-time interactivity
- [ ] Add **predictive model** for call volume forecasting (Python)
- [ ] Include **agent satisfaction / attrition** data for a 360° view

---

## 📌 Conclusion

This project demonstrates how Excel can be used effectively for data analysis and visualization. It highlights key business insights that can help improve call center operations.



