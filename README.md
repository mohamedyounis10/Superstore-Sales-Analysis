<div align="center">
  <h1>Superstore Sales Analysis 📊📉🛒</h1>
  <p>End-to-end sales data analysis (EDA 🔍 → preprocessing 🧹 → visualization 📈) using Python and Power BI 🚀.</p>

  <p>
    <a href="#overview">Overview 🧾</a> •
    <a href="#project-structure">Project Structure 🗂️</a> •
    <a href="#dataset">Dataset 🧩</a> •
    <a href="#results">Results 📊</a> •
    <a href="#dashboard">Dashboard 🖥️</a>
  </p>

  <p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3.x-blue" />
    <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-Notebook-orange" />
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-Data_Analysis-150458" />
    <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-Visualization-blue" />
    <img alt="PowerBI" src="https://img.shields.io/badge/PowerBI-Dashboard-F2C811" />
  </p>
</div>

---

## Table of Contents 🧭

- [Overview 🧾](#overview)
- [Project Structure 🗂️](#project-structure)
- [Dataset 🧩](#dataset)
- [Results 📊](#results)
- [Dashboard 🖥️](#dashboard)
- [How to Run ▶️](#how-to-run)
- [Author ✍️](#author-️)

---

<a id="overview"></a>
## Overview 🧾

This repository focuses on **Superstore Sales Analysis**, extracting insights from retail data through:

- **Data Cleaning 🧹**: Handling missing postal codes and removing duplicate entries.
- **EDA 🔍**: Analyzing sales trends across regions, categories, and time.
- **Key Metrics 📈**: Calculating Total Revenue, Order Volume, and Average Order Value.
- **Visualization 🎨**: Using `Matplotlib` and `Seaborn` for in-depth data storytelling.

---

<a id="project-structure"></a>
## Project Structure 🗂️

- [`Dataset/` 🧩](#dataset) — historical sales data
  - `train.csv`
- [`Dashboard/` 🖥️](#dashboard) — interactive reports
  - `Sales.pbix` (Power BI Report)
  - `data.csv`
- [`notebook.ipynb` 📒](#notebook) — full analysis workflow

Tree 🌳:

```text
Superstore Sales/
├─ Dashboard/
│  ├─ Sales.pbix
│  └─ data.csv
├─ Dataset/
│  └─ train.csv
└─ notebook.ipynb
```

---

<a id="dataset"></a>
## Dataset 🧩

The analysis is performed on the **Superstore Sales Dataset**, containing 18 columns and nearly 10,000 rows of transactional data.

Target Columns 🎯:
- **`Sales`**: Revenue generated per order line.

Key Features 🧾:
- `Order Date`, `Ship Date`, `Ship Mode`.
- `Segment`, `Country`, `City`, `State`, `Region`.
- `Category`, `Sub-Category`, `Product Name`.

---

<a id="results"></a>
## Results 📊

### Key Performance Indicators (KPIs) 🧪

From the notebook analysis 🖨️:

| Metric | Value |
|---|---:|
| **Total Revenue** | **$2,261,255.41** |
| **Total Orders** | **9,799** |
| **Average Order Value** | **$459.42** |

### Insights 💡
- **Growth Trend**: Significant increase in order volume from 2015 to 2018.
- **Seasonal Patterns**: Monthly analysis shows peaks during holiday seasons.

---

<a id="dashboard"></a>
## Dashboard 🖥️

An interactive **Power BI Dashboard** is included to provide a visual breakdown of:
- Sales by Category & Sub-category.
- Regional Performance.
- Profitability and Shipping analysis.

Check [`Dashboard/Sales.pbix`](file:///c:/Users/moham/Desktop/Elevvo/Superstore%20Sales/Dashboard/Sales.pbix) to explore the interactive report.

---

<a id="how-to-run"></a>
## How to Run ▶️

### 1) Setup Environment 🧪
```bash
python -m venv .venv
.\.venv\Scripts\activate
```

### 2) Install Dependencies 📦
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3) Launch Notebook 🚀
```bash
jupyter notebook
```
Open `notebook.ipynb` 📒 to see the full analysis.

---

## Author ✍️

- **Name**: Mohammed Younis 

---
