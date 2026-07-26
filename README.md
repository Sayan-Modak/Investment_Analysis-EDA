<div align="center">

# 🇮🇳 Investment Trends in India (2014–2025)

### Exploratory Data Analysis using World Bank World Development Indicators

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

</div>

---

## 📌 Overview

This project explores India's investment trends between **2014 and 2025** using data from the **World Bank World Development Indicators (WDI)**.

The analysis focuses on **Gross Capital Formation (GCF)** as the primary indicator of investment activity and examines its relationship with **Foreign Direct Investment (FDI) Net Inflows** through a structured Exploratory Data Analysis (EDA).

Unlike many beginner projects that rely on curated Kaggle datasets, this project works with a real-world macroeconomic dataset containing numerous indicators and missing values.

---

## 🎯 Objectives

- Analyze India's investment trends (2014–2025)
- Study Gross Capital Formation (% of GDP)
- Analyze Foreign Direct Investment Net Inflows (% of GDP)
- Explore the relationship between GCF and FDI
- Interpret investment trends within the context of major economic events

---

<details>
<summary><b>📊 Dataset Information</b></summary>

### Source

- **World Bank – [World Development Indicators (WDI)](https://data.worldbank.org/country/india)**

### Study Area

- India

### Time Period

- 2014–2025

### Primary Indicators

- Gross Capital Formation (% of GDP)
- Foreign Direct Investment, Net Inflows (% of GDP)

</details>

---

<details open>
<summary><b>⚙️ Project Workflow</b></summary>

```text
World Bank Dataset
        │
        ▼
Data Inspection
        │
        ▼
Data Cleaning
        │
        ▼
Missing Value Analysis
        │
        ▼
Indicator Selection
        │
        ▼
Univariate Analysis
        │
        ▼
Bivariate Analysis
        │
        ▼
Correlation Analysis
        │
        ▼
Key Findings
```

</details>

---

## 📈 Analysis Performed

### Univariate Analysis

- Gross Capital Formation (% of GDP)
- Foreign Direct Investment Net Inflows (% of GDP)

### Bivariate Analysis

- Scatter Plot
- Regression Analysis
- Pearson Correlation
- Relationship between GCF and FDI

---

## 📊 Key Findings

- Investment activity declined between **2014–2016** before gradually recovering.
- Gross Capital Formation experienced another decline during the **COVID-19 pandemic**.
- Investment recovered steadily after **2021** and reached its highest level by **2025**.
- FDI Net Inflows followed a different trend and showed greater volatility.
- A **Pearson correlation coefficient of -0.76** indicates a strong negative linear relationship between the selected indicators during the study period.
- The findings suggest that **FDI alone does not explain changes in Gross Capital Formation**, highlighting the role of broader macroeconomic factors.

---

## 🛠️ Technologies Used

| Category      | Tools         |
| ------------- | ------------- |
| Programming   | Python        |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib    |
| Notebook      | Google Colab  |

---

## 📁 Repository Structure

```text
Economic_EDA_Project
│
├── Dataset/
│   └── WorldBank_IND_Dataset.xls
│
├── Notebooks/
│   └── Economic_EDA_.ipynb
│
├── Reports/
│   └── Economic_Analysis_EDA_Report.docx
│   └── Economic_Analysis_EDA_Report.pdf
│
├── Visualizations/
│   └── GCF/
│   └── FDI/
│   └── Comparative_Analysis_Graphs/
│
├── README.md
```

---

<details>
<summary><b>📌 Research Questions</b></summary>

- How did Gross Capital Formation change between 2014 and 2025?
- What were the major turning points in investment activity?
- Did these turning points align with major economic events?
- How resilient was investment after periods of slowdown?
- What relationship exists between Gross Capital Formation and FDI Net Inflows?

</details>

---

<details>
<summary><b>⚠️ Limitations</b></summary>

- Analysis limited to India.
- Only two investment indicators were analyzed.
- Dataset contains missing observations.
- Findings describe relationships rather than causation.

</details>

---

<details>
<summary><b>🚀 Future Work</b></summary>

- Include GDP Growth, Inflation and Domestic Savings.
- Compare India's investment trends with other emerging economies.
- Extend the analysis using updated World Bank releases.
- Apply multivariate statistical models.

</details>

---

## 📄 Report

The complete report is available in the **Reports/** directory.

---

## 📚 Data Source

World Bank

**World Development Indicators (WDI)**

https://data.worldbank.org/

---

This project is intended for educational and portfolio purposes.

---

<div align="center">

### Built using real-world World Bank macroeconomic data.

</div>
