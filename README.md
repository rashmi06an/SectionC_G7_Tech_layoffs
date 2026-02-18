# Tech Layoffs Analytics Dashboard (2020–2025)

## Project Overview
This project analyzes workforce instability in the global technology sector between 2020 and 2025.  
The objective is to identify structural layoff patterns across industries, funding stages, geographies, company sizes, and time periods, and convert raw layoff records into decision-oriented insights using data analytics and visualization.

The study demonstrates that layoffs during this period were not random shocks but structured correction cycles driven by over-expansion, funding slowdowns, and macroeconomic pressure. 

---

## Dataset Information
- **Dataset:** Tech Layoffs 2020–2025  
- **Source:** Kaggle  
- **Records:** 5,501 rows  
- **Columns:** 10  
- **Format:** CSV  

### Key Fields
- Company  
- Industry  
- Country / Region  
- Funding Stage  
- Total Laid Off  
- Percentage Laid Off  
- Date  
- Total Employees  
- Funds Raised  
- Department  

The dataset enables multi-dimensional workforce risk analysis across time, geography, and organizational maturity. 
---

## Data Dictionary
| Column | Description | Type |
|--------|-------------|------|
| Company | Name of the company | Text |
| Industry | Industry category | Text |
| Country / Region | Company location | Text |
| Stage | Funding stage | Text |
| Total Laid Off | Employees laid off | Numeric |
| Percentage Laid Off | % workforce reduced | Percentage |
| Date | Layoff announcement date | Date |
| Year | Extracted year from Date | Numeric |
| Total Employees | Workforce size before layoff | Numeric |
| Funds Raised | Total capital raised | Text/Numeric |

(Data dictionary summarized from Appendix A.)

---

## Data Cleaning Notes
All preprocessing was performed in **Google Sheets**.

### Cleaning Steps
- Standardized column names and formats  
- Removed duplicate records  
- Converted percentage values to numeric format  
- Extracted **Year** from Date  
- Standardized country naming (e.g., USA → United States)  
- Created derived fields:
  - Layoff Intensity Category (Low, Moderate, High, Severe)  
  - Company Size Category based on employee count  

Missing or blank categorical values were replaced with **“Unknown.”** 

These transformations ensured the dataset was suitable for KPI calculation, pivot analysis, and dashboard visualization.

---

## KPI Framework & Statistics
Key analytical KPIs include:

- **Total Layoffs by Industry** – measures magnitude concentration  
- **Average Layoff Intensity %** – evaluates proportional workforce reduction  
- **Layoffs by Funding Stage** – identifies capital-exposure risk  
- **Layoffs by Country/Region** – shows geographic concentration  
- **Year-wise Layoff Trend** – detects instability cycles  
- **Severe Companies %** – estimates systemic workforce stress  
- **Risk Multiplier (Small vs Large Firms)** – measures structural vulnerability  

These KPIs enable executive-level interpretation of workforce instability. :contentReference[oaicite:4]{index=4}

---

## Key Insights
Major findings from the analysis include:

- Over **6.3 million jobs** were lost in tech between 2020–2025.  
- Average layoff intensity per company was **~4.68%**.  
- **FinTech** showed the highest proportional layoff intensity (~4.98%).  
- **Late-stage and mature firms** drove the largest absolute layoffs.  
- The **United States** accounted for the majority of workforce reductions.  
- Layoffs **peaked in 2021** due to over-hiring during capital surplus, followed by correction in 2022–23.  
- **Small firms were 1.23× more vulnerable** than large firms.  
- Around **20% of companies experienced high or severe layoffs**, indicating systemic stress.  

These results confirm that layoffs were **structural and cyclical**, not isolated incidents. 

---

## Dashboard Summary
An executive dashboard was developed in **Google Sheets** to visualize workforce instability patterns.

### Dashboard Components
- KPI summary cards (magnitude & risk)  
- Industry-wise layoff distribution  
- Funding stage exposure  
- Geographic concentration  
- Year-wise trend analysis  
- Severity segmentation  

### Interactivity
- Filters for **Industry, Stage, Region, and Year**  
- Enables dynamic exploration of workforce risk patterns  

The dashboard provides a comprehensive view of technology sector layoffs and supports data-driven workforce strategy decisions. 

---

## Dataset Analysis Screenshots
Screenshots of:

- Pivot table calculations  
- KPI derivations  
- Final dashboard visuals  

are included in the repository under:




---

## Limitations
- No revenue or profitability data available  
- No macroeconomic indicators included  
- Observational dataset limits causal inference  

Findings therefore represent **pattern-based insights rather than definitive causality**. 

---

## Conclusion
The project demonstrates that technology-sector layoffs from 2020–2025 followed **predictable structural correction cycles** tied to funding volatility and growth over-expansion.

By transforming raw layoff data into **intensity metrics, KPIs, and executive dashboards**, the analysis enables **predictive, stability-oriented workforce planning** rather than reactive downsizing. 

---

## Tools Used
- **Google Sheets** – Data cleaning, transformation, KPIs, pivot tables  
- **Looker Studio** – Final dashboard visualization  
- **GitHub** – Documentation and version control  

---

## Team
Section C – Group 7  
- Anshuman Mehta (Project Lead)  
- Nitanshu Goyal  
- Rashmi Anand  
- Sankalp  
- Akhil  
- Puneet Thakar  

(Contribution details available in the project report.) 
