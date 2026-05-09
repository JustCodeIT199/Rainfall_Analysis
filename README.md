<div align="center">

<img src="https://img.shields.io/badge/Rainfall%20Analysis-India%20Climate%20Data-0EA5E9?style=for-the-badge&logo=cloud&logoColor=white" alt="Rainfall Analysis Banner" />

# Rainfall Analysis — India 🇮🇳

**Exploratory analysis of historical rainfall patterns across Indian states using Python**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)](https://plotly.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## Overview

This project performs an in-depth exploratory data analysis (EDA) of historical rainfall data across Indian states and union territories. Using statistical methods and rich visualizations, it uncovers long-term trends, seasonal patterns, regional disparities, and drought or flood-risk indicators from multi-decade climate records.

---

## Objective

> Understand and visualize rainfall trends across India over the years — enabling data-driven insights for agriculture planning, water resource management, and climate research.

---

## Dataset

The dataset contains **monthly and annual rainfall records** for Indian states and union territories spanning multiple decades.

| Attribute | Details |
|-----------|---------|
| **Coverage** | All major Indian states & union territories |
| **Frequency** | Monthly + Annual aggregates |
| **Format** | CSV (`rainfall_data.csv`) |
| **Source** | Historical Indian meteorological statistics |

---

## Key Analyses

| Analysis | Description |
|----------|-------------|
| **Year-wise Distribution** | Track how total rainfall has changed over decades |
| **State-wise Comparison** | Identify high and low rainfall regions across India |
| **Trend & Time Series** | Detect long-term increasing or decreasing patterns |
| **Heatmaps & Boxplots** | Visualize monthly spread and outliers per region |
| **Drought / Excess Detection** | Flag years and states with critically low or high rainfall |

---

## Tools & Libraries

| Category | Tools |
|----------|-------|
| **Language** | Python 3.x |
| **Environment** | Jupyter Notebook |
| **Data Processing** | `pandas`, `numpy` |
| **Static Visualization** | `matplotlib`, `seaborn` |
| **Interactive Charts** | `plotly` |

---

## Project Structure

```
Rainfall_Analysis/
│
├── Rainfall_Analysis.ipynb     # Main EDA and visualization notebook
├── rainfall_data.csv           # Raw historical rainfall dataset
├── requirements.txt            # Python dependencies
└── README.md
```

---

## Sample Visualizations

| | |
|--|--|
| ![Viz 1](https://github.com/user-attachments/assets/bad0b194-d8b8-4e30-959e-379f9ff2ff1c) | ![Viz 2](https://github.com/user-attachments/assets/8da4be97-acd8-4d58-9cfa-428eeb1a1bb0) |
| ![Viz 3](https://github.com/user-attachments/assets/aedb9e16-a755-48a1-8f3d-0a6dc5752f6e) | ![Viz 4](https://github.com/user-attachments/assets/403e55f4-b771-4aab-9d5c-664bc37aa1dd) |

---

## Getting Started

### Prerequisites

- Python 3.8+
- pip
- Jupyter Notebook

---

### 1. Clone the Repository

```bash
git clone https://github.com/JustCodeIT199/Rainfall_Analysis.git
cd Rainfall_Analysis
```

### 2. Set Up a Virtual Environment

```bash
python -m venv env

# macOS / Linux
source env/bin/activate

# Windows
env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the Notebook

```bash
jupyter notebook Rainfall_Analysis.ipynb
```

---

## Analysis Workflow

```
Raw CSV Data
     │
     ▼
Data Cleaning & Preprocessing
(nulls, type casting, reshaping)
     │
     ▼
Exploratory Data Analysis
(summary stats, distributions)
     │
     ▼
Visualization
(trends, heatmaps, boxplots,
 interactive Plotly charts)
     │
     ▼
Pattern & Anomaly Detection
(drought years, excess rainfall,
 regional outliers)
```

---

## Roadmap

- [ ] Integrate IMD (India Meteorological Department) live data
- [ ] Predictive modeling for future rainfall forecasting
- [ ] Choropleth map for state-wise rainfall visualization
- [ ] Seasonal decomposition (trend + seasonality + residual)
- [ ] Deploy as an interactive Streamlit / Dash web app

---

## Authors

- [@JustCodeIT199](https://github.com/JustCodeIT199)
- [@Kshitij15042004](https://github.com/Kshitij15042004)

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---
