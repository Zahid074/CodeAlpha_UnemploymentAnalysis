# CodeAlpha_UnemploymentAnalysis

**Data Science Internship — CodeAlpha | Task 2: Unemployment Analysis with Python**

## 📌 Project Overview
This project analyzes unemployment rate data across Indian states (2019–2020) to uncover trends, compare rural vs. urban impact, and quantify the effect of the Covid-19 lockdown on employment.

## 📂 Repository Structure
```
CodeAlpha_UnemploymentAnalysis/
├── data/
│   ├── Unemployment in India.csv
│   └── Unemployment_Rate_upto_11_2020.csv
├── plots/
│   ├── national_trend.png
│   ├── rural_vs_urban.png
│   ├── top10_states.png
│   └── covid_impact.png
├── Unemployment_Analysis.ipynb    # Main notebook
└── README.md
```

## 🛠 Tools & Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn

## 🔍 Workflow
1. **Data Cleaning** — stripped whitespace from column names/values, removed 28 fully-null rows, parsed dates
2. **National Trend Analysis** — monthly average unemployment rate, 2019–2020
3. **Rural vs Urban Comparison**
4. **State-wise Analysis** — top 10 states by average unemployment rate
5. **Covid-19 Impact Quantification** — pre-lockdown vs. during-lockdown vs. post-lockdown averages

## 📊 Key Findings
- Unemployment rate roughly **doubled** during the Covid-19 lockdown period (March–June 2020) compared to the pre-Covid average.
- **Urban areas** were hit harder than rural areas during the lockdown, reflecting the service/industrial sector shutdown.
- Significant **state-level disparity** in average unemployment rates, pointing to uneven regional economic conditions.
- Gradual recovery is visible after June 2020, though rates hadn't fully returned to pre-Covid levels within this dataset's range.

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Unemployment_Analysis.ipynb
```

## 🎓 Internship
Completed as part of the **CodeAlpha Data Science Internship**.
