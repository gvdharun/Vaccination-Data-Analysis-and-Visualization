# 🛡️ Vaccination Data Analysis and Visualization

## Overview

This project analyzes and visualizes global vaccination and disease data to empower public health strategy, policy, and resource allocation. It includes a complete data cleaning, SQL database setup, and interactive dashboards using Power BI.

---

## Features

- Python data cleaning and transformation scripts (`vaccination_report.ipynb`)
- Structured SQLite database (`vaccination_report.db`)
- Interactive Power BI dashboard (`vaccination_report.pbix`)
- Scenario analysis for vaccination coverage and disease incidence
- Visual reports: Heatmaps, time trends, KPIs, disparities

---

## Folder Structure
```
├── Data/
│ ├── coverage-data.csv
│ ├── incidence-rate-data.csv
│ ├── reported-cases-data.csv
│ ├── vaccine-introduction-data.csv
│ └── vaccine-schedule-data.csv
├── vaccination_report.db
├── vaccination_report.ipynb
├── vaccination_report.pbix
```
---

## How To Use

1. **Data Preparation:**  
   Use the provided Jupyter notebook to clean and normalize source CSV files; export to `vaccination_report.db`.

2. **Power BI Dashboard:**  
   - Open Power BI Desktop.
   - Connect to `vaccination_report.db` (SQLite).
   - Open or import the report file `vaccination_report.pbix` for visualizations and insights.

3. **Scenario-Based Analysis:**  
   Explore dashboards for insights by region, year, antigen, and other critical dimensions.

---

## Key Visualizations

- 🌍 **Geographical heatmaps** for coverage and incidence
- 📈 **Trend lines** for time-series analysis
- 🧩 **Scatter plots** for coverage vs. disease rates
- ✅ **KPI indicators** for progress tracking

---

## Requirements

- Python 3.x (pandas, sqlite3, etc.)
- Power BI Desktop (latest version)
- SQLite

---

## Project Deliverables

- Cleaned and normalized vaccination/disease database
- Ready-to-use Power BI visual reports
- Complete source code for further analysis

---

# ✅ Conclusion

This vaccination data analytics project successfully streamlines and visualizes global immunization efforts. By integrating rigorous data cleaning, structured SQL database management, and interactive Power BI dashboards, it empowers data-driven decision-making for **public health policy, disease prevention, and equitable resource allocation**. The tools and insights developed here enable governments, health agencies, researchers, and NGOs to monitor vaccine coverage, assess campaign effectiveness, and identify critical gaps, contributing to healthier populations and strategic global health progress.

---
