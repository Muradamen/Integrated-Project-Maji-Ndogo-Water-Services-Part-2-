# Maji Ndogo – Part 2: Advanced SQL Analysis
## 📌 Overview

This is **Part 2** of the Maji Ndogo water crisis project, focusing on **advanced SQL techniques** to detect anomalies, identify high-risk water sources, and evaluate employee performance.
The ultimate goal is to improve **decision-making** in water resource management for both **rural and urban communities**.
## 🎯 Objectives
* Detect Data Inconsistencies between auditor and employee water source scores.
* Identify Problem Areas using location-based and quality-based water source analysis.
* Evaluate Employee Performance using ranking and aggregation functions.
* Investigate the Water Crisis Scope through data trends and anomalies.
* Generate Actionable Insights to inform effective water management strategies.

## 📂 Dataset Description

This analysis integrates multiple tables from the `md_water_services` database:

| Table               | Description                                               |
| ------------------- | --------------------------------------------------------- |
| auditor\_report | Auditor evaluations and official water source scores.     |
| visits       | Employee visit logs with assigned sources and timestamps. |
| water\_quality  | Employee-reported water quality scores.                   |
| employee     | Employee records and assignment details.                  |
| well\_pollution | Pollution level tests for various water wells.            |

## 🛠 Skills & SQL Concepts Covered

* Common Table Expressions (CTEs) – for clean, modular SQL queries.
* Window Functions – `RANK()`, `DENSE_RANK()`, `LAG()`, `AVG()` for ranking and trends.
* Joins– `INNER JOIN`, `LEFT JOIN` for combining multiple datasets.
* Anomaly Detection – filtering significant score discrepancies.
* Correlated Subqueries – retrieving context-specific values per row.

## 📊 Key Analyses & Insights

1. Employee Performance Ranking
   Ranked employees based on the number of scoring mistakes, revealing those who require further training.

2. Pollution Hotspots
   Identified wells with high pollution levels, prioritizing urgent interventions.

3. Score Discrepancy Detection
   Flagged cases where employee scores were **>9 points higher** than auditor scores for poor water sources.

4. Notable Findings

   * A small group of employees caused the majority of errors.
   * Rural wells showed higher pollution and lower maintenance levels.
   * Many communities rely on non-functional or unsafe water sources.


## 🚀 **How to Run the Project**

1. Clone the Repository

   ```bash
   git clone https://github.com/your-username/maji-ndogo-part2.git
   ```
2. **Navigate to the Project Folder**

   ```bash
   cd maji-ndogo-part2
   
3. **Explore SQL Queries**
   Open queries in the `sql_queries/` folder in your preferred SQL environment.
4. **Reproduce Analysis**
   Use the notebooks in `notebooks/` to follow the analysis steps and generate charts.
## 👤 **Author**

@Muradamen – Data Scientist | SQL Analyst


## ⭐ Support the Project

#DataScience #SQL #MajiNdogo


If you want, I can now create the **exact Git commands & folder structure** for pushing this Part 2 project to GitHub with this README included so it looks **professional and ready for recruiters**. Would you like me to prepare that?
