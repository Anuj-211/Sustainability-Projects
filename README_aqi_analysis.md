
# 😷 AQI & Respiratory Health Risk Analysis (Delhi vs. Mumbai)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Data](https://img.shields.io/badge/Data-Time%20Series-orange)
![Focus](https://img.shields.io/badge/Focus-Public%20Health%20%26%20ESG-green)

## 📖 Project Overview
Air pollution is not just an environmental issue; it is a public health emergency. This project analyzes a **24-month longitudinal dataset (2023-2024)** of Air Quality Index (AQI) concentrations in India's two largest metros: Delhi and Mumbai.

By correlating environmental data with medical impact studies, this project identifies critical **"Risk Windows"**—specific periods where respiratory health risks for vulnerable populations (children, elderly) spike significantly. This model serves as a prototype for **Anticipatory ESG Governance**, allowing cities and corporations to implement mitigation strategies *before* pollution peaks.

## 📊 Key Findings
Based on the analysis of 48 months of aggregated data:
* **The "120-Day Crisis":** Winter months (Nov-Feb) identified as a critical hazard zone, with AQI consistently exceeding 200 ("Very Poor").
* **City Comparison:** While both cities exceed WHO safety limits, **Delhi** averaged significantly higher winter pollution (~225 AQI) compared to **Mumbai** (~210 AQI), primarily due to temperature inversion and lower wind speeds.
* **Health Correlation:** Periods of "Very Poor" AQI (>200) correlate with a projected **40-60% increase** in respiratory hospital admissions.
* **The "Safe" Window:** Monsoon months (Jun-Sep) provide the only window of "Satisfactory" air quality (AQI 50-100).

## 🛠️ Tech Stack & Methodology
* **Language:** Python
* **Data Processing:** `Pandas` (Time-series aggregation), `NumPy`
* **Visualization:** `Seaborn` (Heatmaps for seasonal trends), `Matplotlib`
* **Data Source:** CPCB (Central Pollution Control Board) & Real-time monitoring stations.

**Methodology:**
1.  **Data Ingestion:** Aggregated hourly PM2.5/PM10 readings into monthly averages.
2.  **Seasonal Decomposition:** Isolated Winter, Pre-Monsoon, Monsoon, and Post-Monsoon trends.
3.  **Risk Mapping:** Overlaid WHO Air Quality Guidelines ($15 \mu g/m^3$) to visualize the "Safety Gap."

## 📉 Visualizations
<img width="4734" height="3566" alt="aqi_analysis_visualizations" src="https://github.com/user-attachments/assets/a5dcfdaf-7d2b-4328-a8b7-8134ac38fc83" />

> *Figure 1: Seasonal Heatmap showing the 'Red Zone' transition starting in October.*

## 💡 Policy & ESG Recommendations
Derived from the data analysis, the following interventions are recommended for urban planning and corporate "Employee Well-being" policies:
1.  **Anticipatory Alerts:** Issue health advisories starting **September 15th**, two weeks before the observed spike.
2.  **Corporate Policy:** Implement mandatory "Work From Home" (WFH) for vulnerable employees when AQI > 200.
3.  **Urban Planning:** Enforcement of Odd-Even vehicle schemes specifically during the **Nov 1 - Feb 28** window.



## 📜 License

This project is for educational and research purposes. Data credits: CPCB, Govt of India.

-----

**Author:** Anuj Choubey

  * **Role:** Sustainability Data Analyst | Life Sciences Researcher
  * [LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/anuj-choubey) | [GitHub](https://www.google.com/search?q=https://github.com/anujchoubey)

<!-- end list -->




