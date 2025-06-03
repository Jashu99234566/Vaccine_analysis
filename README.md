# 👬 Vaccine Coverage & Disease Incidence Analysis

## 📚 Overview

This project explores the relationship between **vaccination coverage** and **disease incidence** across countries and time periods. It combines structured WHO data, SQL-based data warehousing, exploratory data analysis in Python, and Power BI dashboards for interactive visualization and insight generation.

---

## 📊 Key Features

* ✅ **Data Cleaning & Integration** using Python
* 📊 **Relational Database Schema** for handling vaccine and disease datasets
* 🔢 **SQL-based Queries** for effective joins, filters, and aggregations
* 🔬 **Exploratory Data Analysis** (EDA) notebooks for each dataset:

  * Vaccine coverage
  * Disease incidence rate
  * Reported cases
  * Vaccine introduction & schedule
* 📈 **Power BI Dashboard** for end-user data exploration and storytelling

---

## ⚙️ Technologies Used

| Category            | Tools & Libraries                               |
| ------------------- | ----------------------------------------------- |
| **Data Processing** | Pandas, NumPy                                   |
| **Database**        | MySQL (`mysql-connector-python`)                |
| **Analysis**        | Jupyter Notebook                                |
| **Visualization**   | Power BI, Matplotlib, Seaborn                   |
| **ETL/SQL**         | SQL scripts for data loading and transformation |

---

## 📂 Project Structure

```
├── sqldatabase creation.ipynb      # Schema & table creation for vaccination DB
├── coverage data.ipynb             # EDA on vaccine coverage trends
├── incident rate.ipynb             # EDA on disease incidence rates
├── Reported cases  data.ipynb      # EDA on reported disease cases
├── Vaccine Schdule .ipynb          # Schedule and introduction analysis
├── vaccine analysis.pbix           # Power BI dashboard with visual insights
└── /cleaned_data                   # (optional) cleaned .csv/.xlsx source files
```

---

## ✅ Objectives

* Identify regions with poor vaccine coverage or declining booster uptake
* Correlate disease outbreaks with delays in vaccine introductions
* Highlight inconsistencies between reported coverage and actual cases
* Analyze dropout rates across multi-dose vaccines
* Detect gaps in schedule compliance across geography and time

---

## 🛋️ Setup Instructions

1. **MySQL Setup**: Use `sqldatabase creation.ipynb` to create and populate tables.
2. **Jupyter EDA**: Run the notebooks to clean and explore each dataset.
3. **Power BI**: Open the `.pbix` file to interact with visualizations built on cleaned, joined data.

---

## 📌 Sample Questions Answered

* Which countries have high disease incidence despite high coverage?
* Are there dose drop-off patterns in multi-dose vaccines?
* Which regions have effective vaccine programs over time?
* Are urban vs. rural populations equally vaccinated?
* Do certain diseases resurge even with continued vaccine availability?

---

## 🚀 Outcome

An integrated pipeline from raw WHO datasets to SQL-powered insights and interactive business intelligence dashboards—suitable for public health research, policymaking, and vaccine effectiveness monitoring.

---

Feel free to fork, contribute, or adapt for regional disease research!
