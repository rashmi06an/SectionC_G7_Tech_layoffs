# 📊 Tech Layoffs Analytics Dashboard (2020–2025)

## 🔷 Project Overview
This project analyzes workforce instability in the global technology sector between **2020 and 2025**. The objective is to identify structural layoff patterns across industries, funding stages, geographies, company sizes, and time periods, and convert raw layoff records into **decision-oriented business insights** using data analytics and visualization.

The analysis reveals that tech layoffs during this period were **systemic correction cycles** driven by over-expansion, funding slowdowns, and macroeconomic pressures rather than isolated events.

---

## 🔷 Dataset Information

| Attribute | Details |
|----------|---------|
| **Dataset Name** | Tech Layoffs 2020–2025 |
| **Source** | Kaggle |
| **Total Records** | 5,501 rows |
| **Total Columns** | 10 |
| **File Format** | CSV |
| **Granularity** | Company-level layoff events |

The dataset supports **multi-dimensional workforce risk analysis** across time, geography, and organizational maturity.

---

## 🔷 Data Dictionary

| Column | Description | Data Type |
|--------|-------------|-----------|
| Company | Name of the company | Text |
| Industry | Industry category | Text |
| Country / Region | Company location | Text |
| Stage | Funding stage | Text |
| Total Laid Off | Employees laid off | Numeric |
| Percentage Laid Off | Workforce reduction % | Percentage |
| Date | Layoff announcement date | Date |
| Year | Extracted year from Date | Numeric |
| Total Employees | Workforce size before layoff | Numeric |
| Funds Raised | Total capital raised | Numeric/Text |

---

## 🔷 Data Cleaning & Preparation

All preprocessing was performed in **Google Sheets** following structured data engineering practices.

### ✔ Cleaning Actions Performed

| Step | Action |
|------|--------|
| 1 | Standardized column names and formats |
| 2 | Removed duplicate records |
| 3 | Fixed mixed date formats and extracted Year |
| 4 | Converted percentage fields to numeric |
| 5 | Normalized country names (e.g., USA → United States) |
| 6 | Handled missing categorical values with "Unknown" |
| 7 | Verified numeric columns for analytical accuracy |

### ✔ Derived Features Created

- **Layoff Intensity Category** (Low, Moderate, High, Severe)  
- **Company Size Category** (based on employee count)  
- **Year** extracted from Date  

These transformations ensured the dataset became **dashboard-ready and analysis-safe**.

---

## 🔷 KPI Framework

The project tracks workforce instability using the following key performance indicators:

| KPI Category | Metric | Purpose |
|-------------|--------|---------|
| Workforce Impact | Total Layoffs by Industry | Magnitude concentration |
| Workforce Intensity | Average Layoff % | Proportional workforce reduction |
| Capital Risk | Layoffs by Funding Stage | Funding exposure analysis |
| Geographic Risk | Layoffs by Country/Region | Location concentration |
| Temporal Trend | Year-wise Layoff Trend | Instability cycle detection |
| Structural Risk | Severe Companies % | Systemic stress indicator |
| Firm Vulnerability | Risk Multiplier (Small vs Large) | Size-based risk comparison |

---

## 🔷 Key Insights & Statistics

### 📉 Major Findings

- 🔹 **6.3M+ jobs** lost in tech (2020–2025)  
- 🔹 Average layoff intensity: **~4.68% per company**  
- 🔹 **FinTech** recorded highest proportional layoffs (~4.98%)  
- 🔹 **Late-stage firms** drove maximum absolute layoffs  
- 🔹 **United States** dominated workforce reductions  
- 🔹 Layoffs **peaked in 2021**, followed by correction in 2022–23  
- 🔹 **Small firms were 1.23× more vulnerable** than large firms  
- 🔹 ~**20% companies** experienced high/severe layoffs  

### 🧠 Strategic Interpretation
These patterns confirm layoffs were **structural, cyclical corrections** tied to capital cycles rather than random shocks.

---

## 🔷 Dashboard Summary

An executive dashboard was developed using **Google Sheets** and **Looker Studio**.

### 📊 Dashboard Components

- KPI summary cards  
- Industry-wise layoff distribution  
- Funding stage exposure analysis  
- Geographic concentration view  
- Year-wise trend visualization  
- Layoff severity segmentation  

### 🎛 Interactivity Features

- Dynamic filters for:
  - Industry  
  - Funding Stage  
  - Country/Region  
  - Year  

The dashboard enables **self-service exploration of workforce risk patterns** for strategic decision-making.

---

## 🔷 Dataset Analysis Screenshots

Repository includes visual evidence of the analytical workflow:

📁 Calculations_Pivots/ → Pivot tables & KPI calculations
📁 Dashboard/ → Dashboard visuals & Looker link
📁 Cleaned/ → Final processed dataset
📁 RawDataset/ → Original raw data


---

## 🔷 Limitations

- Revenue and profitability data unavailable  
- Macroeconomic indicators not included  
- Observational dataset limits causal inference  

⚠️ Findings should be interpreted as **pattern-based insights**, not definitive causality.

---

## 🔷 Conclusion

The analysis demonstrates that technology-sector layoffs from 2020–2025 followed **predictable structural correction cycles** linked to funding volatility and rapid growth expansion.

By transforming raw workforce data into **intensity metrics, KPIs, and executive dashboards**, the project enables **proactive workforce risk monitoring** rather than reactive downsizing decisions.

---

## 🔷 Tools & Technologies

- **Google Sheets** — Data cleaning, transformation, pivot analysis  
- **Looker Studio** — Interactive dashboard visualization  
- **GitHub** — Version control and project documentation  

---

## 👥 Team — Section C, Group 7

| Name | Role |
|------|------|
| Anshuman Mehta | Project Lead |
| Nitanshu Goyal | Team Member |
| Rashmi Anand | Team Member |
| Sankalp | Team Member |
| Akhil | Team Member |
| Puneet Thakar | Team Member |

---

## ⭐ Repository Purpose

This repository demonstrates an **end-to-end data analytics workflow**, covering:

- Raw data engineering  
- Data cleaning & standardization  
- KPI design  
- Exploratory analysis  
- Dashboard development  
- Business insight generation  

---
