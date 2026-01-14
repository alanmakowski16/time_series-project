# Time Series Analysis of Electricity Demand (PJME)

## Project Overview

This project focuses on the analysis and forecasting of electricity demand using historical time series data from the PJM Interconnection (PJME region). The objective is to identify temporal patterns, examine statistical properties of the series, and develop forecasting models in accordance with academic time series analysis guidelines.

The project is implemented in **Python** and follows a structured workflow including preprocessing, exploratory data analysis, modeling, and forecast evaluation.

---

## Dataset

- **Source:** PJM Interconnection (public dataset)
- **Frequency:** Hourly (original data)
- **Region:** PJME
- **Variable:** Electricity load (MW)

Two cleaned datasets are used:

| File name | Description |
|----------|------------|
| `pjme_hourly_cleaned.csv` | Cleaned hourly electricity demand |
| `pjme_daily_cleaned.csv` | Daily-aggregated electricity demand (mean values) |

The datasets are stored on **Google Drive** and accessed programmatically to ensure reproducibility and team compatibility.

---

## Repository Structure

```text
project-timeseries/
│
├── data/                      # Optional local outputs
├── notebooks/
│   ├── 01_preprocessing_eda.ipynb
│   ├── 02_stationarity_tests.ipynb
│   ├── 03_modeling_forecasting.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore

