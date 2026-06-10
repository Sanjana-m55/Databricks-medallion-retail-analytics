# 🏬 Databricks Medallion Retail Analytics

An end-to-end retail analytics project built on Databricks using the Medallion Architecture (Bronze, Silver, and Gold layers). The project demonstrates modern data engineering practices by ingesting raw retail data, transforming it into analytics-ready datasets, and generating business insights through SQL and visual dashboards.

---

## 🚀 Project Objective

To design and implement a scalable retail analytics pipeline that converts raw transactional data into meaningful business insights using Databricks, Apache Spark, Delta Lake, and SQL.

---

## 🏗️ Architecture

The project follows the Medallion Architecture approach:

### 🥉 Bronze Layer – Data Ingestion
- Loaded raw retail data into Databricks.
- Stored source data in Delta format.
- Preserved the original dataset for traceability and auditing.

### 🥈 Silver Layer – Data Transformation
- Performed data cleansing and standardization.
- Handled missing values and inconsistencies.
- Applied business transformations to prepare analytical datasets.

### 🥇 Gold Layer – Data Modeling
- Created business-ready datasets.
- Developed aggregated views and KPIs for reporting.
- Optimized data structures for analytical consumption.

### 📊 Dashboard SQL
- Built SQL queries to analyze:
  - Sales performance
  - Profitability trends
  - Regional performance
  - Category-wise insights
  - Customer behavior patterns

### 📈 Dashboard Visualizations
- Developed visual reports to communicate key findings.
- Enabled data-driven decision-making through interactive analytics.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Databricks | Unified analytics platform |
| Apache Spark | Distributed data processing |
| PySpark | Data ingestion and transformations |
| Delta Lake | Reliable data storage layer |
| SQL | Business analysis and querying |
| GitHub | Version control and project collaboration |

---

## 📂 Project Structure

```text
Databricks-medallion-retail-analytics/
│
├── data/
│   └── superstore.csv
│
├── 01_Bronze_Ingestion.ipynb
├── 02_Silver_Transformation.ipynb
├── 03_Gold_Modeling.ipynb
├── 04_Dashboard_SQL.ipynb
├── 05_Dashboard_Visualizations.ipynb
│
└── README.md
```

---

## 🔄 Workflow

```text
Raw Retail Dataset
        │
        ▼
 Bronze Layer
(Data Ingestion)
        │
        ▼
 Silver Layer
(Data Cleaning & Transformation)
        │
        ▼
 Gold Layer
(Business Modeling & KPIs)
        │
        ▼
 SQL Analytics
        │
        ▼
 Dashboard Visualizations
```

---

## 📌 Key Insights Generated

- Identified top-performing product categories.
- Analyzed regional sales and profit trends.
- Evaluated customer purchasing behavior.
- Measured overall business profitability.
- Developed analytical datasets for reporting purposes.

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- Implementing the Medallion Architecture.
- Building ETL pipelines using Databricks.
- Working with Delta Lake tables.
- Performing large-scale data transformations using PySpark.
- Writing analytical SQL queries.
- Managing Databricks projects with GitHub integration.

---

## 👩‍💻 Author

**Sanjana M**

AI & Data Science Engineer | Data Engineering

GitHub: https://github.com/Sanjana-m55

LinkedIn: https://www.linkedin.com/in/sanjana-m--/

---
