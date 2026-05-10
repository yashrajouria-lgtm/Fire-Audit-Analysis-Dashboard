# 🔥 Fire Audit Analysis Dashboard

### *Turning supplier audit chaos into actionable insights*

[![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-316192?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Power BI](https://img.shields.io/badge/Power_BI-Desktop-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)

**An end-to-end data analytics project — Excel ➜ Python ➜ SQL ➜ Power BI**

</div>

---

## 💡 The Problem

> Companies plan fire safety audits. Companies forget to do them.  
> Suppliers get audited late. Risks go undetected. Disasters happen.

**This dashboard answers the question every safety officer should be asking:**  
> *"Which suppliers are slipping through the cracks?"*

---

## 🎯 What This Project Solves

| Pain Point | Solution |
|------------|----------|
| 🕐 No visibility into audit delays | Real-time delay tracking |
| ❓ Unknown supplier risk levels | Risk category breakdown |
| 📅 Pending audits piling up | Monthly execution gap analysis |
| 📉 No performance benchmarking | YoY completion rate comparison |

---

## 🖥️ Dashboard Preview

<div align="center">

![Dashboard](dashboard_preview.png)

*Interactive Power BI dashboard with 3 slicers, 4 KPIs, 3 charts, and a supplier table*

</div>

---

## 🔥 Key Findings

<div align="center">

| 🎯 Metric | 📊 Value | 💬 Insight |
|-----------|----------|-----------|
| Total Audits | **45** | Across 2 financial years |
| Completion Rate | **77.8%** | Room for improvement |
| High Risk Suppliers | **6** | Need immediate attention |
| Max Delay | **152 days** | Critical execution gap |
| Avg Score | **~89%** | Most suppliers in caution zone |

</div>

---

## 🛠️ Built With
┌─────────────────────────────────────────────┐
│  Excel → Python → PostgreSQL → Power BI    │
│                                             │
│  Raw Data    Cleaning      Storage    Viz  │
└─────────────────────────────────────────────┘

- **🐼 Pandas + NumPy** — Data wrangling
- **📊 Matplotlib + Seaborn** — Exploratory analysis  
- **🗄️ PostgreSQL** — Database with 5 analytical views
- **📈 Power BI** — Interactive dashboard
- **🔗 SQLAlchemy** — Python-SQL bridge

---

## ⚡ Project Architecture
📂 Fire-Audit-Analysis-Dashboard
│
├── 📓 fire_audit_jupyter.ipynb      Data cleaning + EDA
├── 📊 Fire_Audit_Dashboard.pbix     Interactive dashboard
├── 📋 Fire_Audit_Plan_Excel.xlsx    Raw audit data
├── 🗃️ fire_audit_clean.csv          Processed dataset
│
├── 📁 sql/
│   └── fire_audit_views.sql         5 PostgreSQL views
│
└── 📁 charts/
└── *.png                        7 EDA visualizations

---

## 🚀 Quick Start

**1. Clone**
```bash
git clone https://github.com/yashrajouria-lgtm/Fire-Audit-Analysis-Dashboard.git
```

**2. Install**
```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary openpyxl
```

**3. Run**
```bash
jupyter notebook fire_audit_jupyter.ipynb
```

**4. Load SQL views**
```bash
psql -U postgres -d fire_audit_db -f sql/fire_audit_views.sql
```

**5. Open** `Fire_Audit_Dashboard.pbix` in Power BI Desktop

---

## 📊 Dashboard Features
✓ 3 Interactive Slicers      ✓ Risk Category Donut
✓ 4 Dynamic KPI Cards        ✓ Cumulative Plan Tracker
✓ Monthly Plan vs Actual     ✓ Full Supplier Detail Table

---

## 🎨 The Result

A pixel-perfect, executive-ready dashboard that turns spreadsheet noise into board-room clarity.

<div align="center">

**Before:** 📉 Static Excel sheets, manual analysis, no insights  
**After:** 📈 Live filters, real-time KPIs, instant decisions

</div>

---

<div align="center">

### Built with ☕ and grit by

**[Yash Rajouria](https://github.com/yashrajouria-lgtm)**

⭐ *If this project helped you, drop a star!*

</div>

Save it and push:
powershellgit add README.md
git commit -m "Add README"
git pushOpus 4.7
