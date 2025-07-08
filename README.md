# 🦠 COVID-19 Statistical Analysis Project

## 📌 Overview  
This project performs a comprehensive statistical analysis on the COVID-19 dataset, focusing on trends, relationships, and statistical significance across countries and continents. Visualizations and hypothesis testing are applied to draw insights from daily and cumulative data.

---

## 🎯 Objectives:
- Perform **continent-wise and country-wise** analysis of COVID-19 cases  
- Understand **seasonal patterns** in the top affected countries  
- Analyze **correlation between multiple features** using Chi-Square contingency  
- Visualize the **distribution of daily new cases** in the top countries  
- Use **Two-way ANOVA** to evaluate if continent and population impact average cases  

---

## Tools & Libraries:
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy (Chi-Square Test, ANOVA)  
- Jupyter Notebook  

---

## Key Analyses & Visualizations:
- 7-day moving average for top countries  
- Country-wise death rate comparison  
- Distribution plots for daily new cases  
- Chi-Square contingency analysis  
- Two-way ANOVA analysis  

---

## Features in Dataset:

- **date** - Date of observation in YYYY-MM-DD format  
- **country** - Name of the country  
- **cumulative_total_cases** - Total confirmed cases till the given date  
- **daily_new_cases** - New confirmed cases on the given date  
- **active_cases** - Currently active cases (not yet recovered or dead)  
- **cumulative_total_deaths** - Total confirmed deaths till the given date  
- **daily_new_deaths** - New deaths reported on that date  
- **continent** - Continent of the country  
- **total_confirmed** - Total confirmed cases in the country  
- **total_deaths** - Total deaths in the country  
- **total_recovered** - Total recoveries in the country  
- **serious_or_critical** - Number of critical condition cases  
- **total_cases_per_1m_population** - Total cases per million population  
- **total_deaths_per_1m_population** - Total deaths per million population  
- **total_tests** - Total number of tests done in the country  

---

## How to Run:
1. Clone or download this repository  
2. Open the notebook (`COVID19_Statistical_Analysis.ipynb`) in Jupyter Notebook or Colab  
3. Run the cells one by one to see the analysis and visualizations  

---

## 📁 Dataset:
The dataset used in this project consists of two CSV files extracted from Worldometer data:
- `worldometer_coronavirus_daily_data.csv`  
- `worldometer_coronavirus_summary_data.csv`

---

## 🤝 Connect with Me:
- LinkedIn: [Tajwinder (Taj) Singh](https://www.linkedin.com/in/tajwinder-singh)  
- GitHub: [tajwinder-singh](https://github.com/tajwinder-singh)

If this project helped you, consider giving a ⭐ on the repository and sharing your feedback!
