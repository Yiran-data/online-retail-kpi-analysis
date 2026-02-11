# 📊 Online Retail KPI Analysis

A complete end-to-end business analytics project using Python, Power BI, and R to analyze retail performance trends and key performance indicators (KPIs).

---

## 🚀 Project Overview

This project analyzes an online retail dataset to:

- Clean and preprocess raw transaction data
- Define and validate business KPIs
- Perform time-series aggregation
- Visualize monthly performance trends
- Build an interactive Power BI dashboard
- Cross-validate results using R

The goal is to simulate a real-world analytics workflow from raw data to executive-ready insights.

---

## 📁 Repository Structure
```
online-retail-kpi-analysis/
│
├── data/
│ ├── raw/                (not included in repository due to size limit)              
│ └── processed/
│ └── daily_kpi.csv
│
├── notebooks/
│ ├── 01_data_preparation.ipynb
│ ├── 02_kpi_definition_and_validation.ipynb
│ └── 03_time_series_analysis.ipynb
│
├── r/
│ └── 04_r_kpi_analysis.Rmd
│
├── powerbi/
│ └── Business_KPI_Monthly_Trends.pbix
│
└── figures/
├── kpi_monthly_net_revenue_trend.png
└── kpi_monthly_orders_trend.png

Note: The raw dataset is not included in this repository due to GitHub size limitations.
The dataset used in this project was obtained from Kaggle:
Online Retail Dataset
https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset
```


---

## 🧠 KPI Definitions

The following KPIs are computed and validated:

- **Orders**
- **Active Customers**
- **Gross Revenue**
- **Return Revenue**
- **Net Revenue**
- **Items Sold**

Monthly aggregation is used to highlight seasonality and trend patterns.

---

## 📈 Key Visualizations

### Monthly Net Revenue

![Monthly Net Revenue](figures/kpi_monthly_net_revenue_trend.png)

### Monthly Orders

![Monthly Orders](figures/kpi_monthly_orders_trend.png)

---

## 🛠 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib)
- **Power BI**
- **R (tidyverse, ggplot2)**
- Jupyter Notebook

---

## 📌 Workflow Summary

1. Data cleaning and preprocessing  
2. KPI computation and validation  
3. Time-series aggregation  
4. Dashboard construction in Power BI  
5. Cross-checking monthly trends in R  

---

## 🎯 Business Insight Example

- Revenue shows clear seasonal spikes in Q4.
- Orders and revenue trends are strongly correlated.
- Customer activity increases significantly during peak sales months.

---

## 👤 Author

Yiran Han  
Business Analytics / Data Science
