<p align="center">
  <img src="images/readme/hero.svg" alt="Cyclistic Rider Behaviour Analysis" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square" alt="pandas">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-7C3AED?style=flat-square" alt="DAX">
  <img src="https://img.shields.io/badge/Power%20Query-10B981?style=flat-square" alt="Power Query">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square" alt="Jupyter">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square" alt="GitHub">
</p>

<p align="center"><b>Python • pandas • Power BI • DAX • Power Query • Behavioural Analytics</b></p>

An end-to-end rider-behaviour analytics case study covering approximately **5.93 million bike-share trips** from **July 2025 to June 2026**. The analysis compares annual members and casual riders across volume, duration, day-of-week, hourly demand, seasonality, bike type and weekday/weekend behaviour.

> **Portfolio standard:** the repository is structured as an auditable analytics case study with business questions, data-quality controls, reproducible notebooks, dashboard evidence, limitations and automated repository checks.

---

## 🎯 Executive Snapshot

| KPI | Result |
| --- | ---: |
| Total rides | **5.93M** |
| Member rides | **3.81M** |
| Casual rides | **2.11M** |
| Member ride share | **64.36%** |
| Casual ride share | **35.64%** |
| Overall avg. ride duration | **14.38 min** |
| Member avg. ride duration | **12.06 min** |
| Casual avg. ride duration | **18.57 min** |

---

## 🧩 Business Problem

Cyclistic needs to understand how annual members and casual riders behave differently so marketing and membership strategy can be targeted more effectively.

The analysis addresses:

1. How do member and casual rider volumes differ?
2. Which group takes longer rides?
3. When do rider groups use the service most heavily?
4. How does demand change by month and season?
5. How do weekday/weekend and bike-type patterns differ?
6. Which behavioural patterns could support membership conversion?

---

## 🏗️ Analytical Architecture

```mermaid
flowchart LR
    A["12 monthly trip files"] --> B["Python + pandas preparation"]
    B --> C["Cleaning + validation"]
    C --> D["Feature engineering"]
    D --> E["Analytical aggregates"]
    E --> F["Power BI + DAX"]
    F --> G["Rider-behaviour dashboard"]
```

Full design: [`docs/TECHNICAL_ARCHITECTURE.md`](docs/TECHNICAL_ARCHITECTURE.md)

---

## 📊 Dashboard

![Cyclistic Power BI Dashboard](images/Cyclist_Powerbi_Dashboard.png)

---

## 🔎 Key Findings

- **Members account for 64.36% of rides**, indicating the larger base of recurring service usage.
- **Casual riders take longer trips**, averaging **18.57 minutes** versus **12.06 minutes** for members.
- Member activity shows clear commute-style peaks around **8 AM** and **5 PM**.
- Casual usage is relatively more concentrated around weekends and leisure-oriented periods.
- Ridership is strongly seasonal, with demand increasing in warmer months and falling in winter.
- The behavioural split suggests that member and casual segments should not be marketed to identically.

---

## 💼 Business Recommendations

- Target frequent casual riders with membership-conversion messaging during high-demand spring and summer periods.
- Use weekend and leisure-oriented campaigns for casual riders.
- Position membership around convenience, frequent usage and commuting value.
- Use daypart segmentation to align messaging with commute and leisure peaks.
- Treat seasonal demand as a planning variable for acquisition and retention activity.

---

## 🧠 Analytical Engineering

The project demonstrates:

- combining 12 monthly source files;
- duplicate and timestamp validation;
- ride-duration quality checks;
- derived weekday, hour, month, season and weekend features;
- Parquet/CSV analytical outputs;
- pandas-based exploratory analysis;
- Power BI dashboard engineering;
- DAX measures and Power Query preparation;
- source-controlled notebooks and documentation.

---

## 🧰 Technology Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square" alt="pandas">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-7C3AED?style=flat-square" alt="DAX">
  <img src="https://img.shields.io/badge/Power%20Query-10B981?style=flat-square" alt="Power Query">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square" alt="Jupyter">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square" alt="GitHub">
</p>

**Python · pandas · Jupyter Notebook · Power BI · Power Query · DAX · CSV · Parquet · Git · GitHub · VS Code**

---

## ✅ Quality & Reproducibility

The repository includes an automated **Portfolio Quality** workflow validating required assets and notebook JSON integrity.

The analytical workflow also includes duplicate checks, timestamp validation, ride-duration investigation and rider-category validation.

---

## ⚖️ Methodology & Limitations

- The analysis is observational; behavioural patterns should not be interpreted as causal.
- Weather is likely to affect bike-share demand but is not directly modelled.
- Membership recommendations are analytical hypotheses and should be validated through controlled campaigns.
- The analysis period covers one year, so longer-term structural trends are outside scope.

---

## 📁 Repository Structure

```text
cyclistic-rider-behaviour-analysis/
├── .github/workflows/portfolio-quality.yml
├── docs/
│   ├── RECRUITER_PROJECT_SUMMARY.md
│   └── TECHNICAL_ARCHITECTURE.md
├── images/
│   ├── readme/hero.svg
│   └── Cyclist_Powerbi_Dashboard.png
├── outputs/
├── powerbi/
├── 01_data_preparation.ipynb
├── 02_data_cleaning.ipynb
├── 03_exploratory_analysis.ipynb
└── README.md
```

---

## 👨🏾‍💻 Author

**Oluwatosin Oluwaseun Mulero**  
**Data Analyst | Data Scientist | Business Intelligence**
