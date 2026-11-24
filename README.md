# HR Analytics & Employee Attrition Analysis

## Project Overview
An end-to-end data analytics, SQL diagnostics, statistical hypothesis testing, and interactive dashboard project investigating workforce turnover drivers using the **IBM HR Analytics Employee Attrition & Performance** dataset.

### Important Dataset Disclaimer & Limitations
* **Synthetic Data Origin:** This dataset (1,470 employee records, 35 features) is a fictional/synthetic dataset created by IBM data scientists for educational and analytical modeling.
* **No Calendar Dates:** The dataset contains no hire-date or exit-date timestamps; therefore, no monthly or yearly time-series attrition trends are present.
* **Unspecified Currency:** Income fields (`MonthlyIncome`, `DailyRate`, `HourlyRate`, `MonthlyRate`) do not specify a currency unit and are reported as plain numeric values.

---

## Key Findings Summary
* **Baseline Attrition:** **16.12%** (237 departures out of 1,470 employees; 83.88% retention).
* **Overtime Association:** Overtime workers leave at **30.53%** vs. **10.44%** for non-overtime staff ($\chi^2 = 87.56, p < 0.0001$).
* **High-Risk Roles:** **Sales Representatives** (**39.76%** attrition) and **Laboratory Technicians** (**23.94%** attrition) exhibit the highest turnover concentration.
* **Compensation & Job Level:** Employees in lower job levels (Level 1) and lower monthly income brackets show significantly higher voluntary resignation rates.

---

## Repository Structure
```text
├── 01_Dataset/               # Original IBM HR Analytics dataset & metadata
├── 02_Data_Cleaning/         # Python preprocessing, missing value checks & data validation
├── 03_EDA/                   # Exploratory Data Analysis notebooks & correlation matrices
├── 04_SQL_Analysis/          # SQL queries, schemas, and relational views
├── 05_Statistical_Analysis/  # Chi-square tests, ANOVA, and hypothesis testing scripts
├── 06_Machine_Learning/      # Predictive attrition models and feature importance ranking
├── 07_Dashboard/             # Interactive dashboard assets (Power BI / Streamlit)
├── 08_Final_Report/          # Comprehensive PDF Internship Report
└── README.md                 # Project documentation
