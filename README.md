<div align="center">

# Josh Bernard Magsipoc

**Data Engineering · SQL · Data Analytics**

Building practical data projects with an emphasis on **data quality, reproducible analysis, and useful results**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josh-bernard-magsipoc-12b78a2b1)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Jbpm3)

</div>

---

## Skills & Technologies

**SQL and databases**

![SQL](https://img.shields.io/badge/SQL-334155?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

- Relational modeling, joins, CTEs, conditional aggregation, date-based analysis, and data-quality checks.
- Translating business questions into SQL metrics and documenting assumptions and exclusions.

**Python and data workflows**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=python&logoColor=white)

- Built a Python/pandas and SQLAlchemy workflow for SQL extraction, automated validation checks, and CSV exports; deployed the resulting analytics dashboard with Streamlit.
- Continuing to strengthen independent Python skills; exposure to h5py, Shapely, satellite-data tooling, and automated checks through AI-assisted team development.

**Software and development tools**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111827)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

Git · GitHub · pgAdmin · VS Code · GitHub Actions (team-project exposure) · Shortcut · Codex

---

## Featured Projects

### 01 / Olist — E-Commerce Shipment Delay Analysis

**Independent analytics project · PostgreSQL · SQL · Python · pandas · SQLAlchemy · Streamlit**

[**Live dashboard**](https://olist-shipment-delay-analysis.streamlit.app/) · [**Repository**](https://github.com/Jbpm3/olist-shipment-delay-analysis) · [**SQL analyses**](https://github.com/Jbpm3/olist-shipment-delay-analysis/tree/main/sql) · [**Findings**](https://github.com/Jbpm3/olist-shipment-delay-analysis/blob/main/docs/findings.md)

Built and deployed an interactive dashboard for exploring delivery delays in a historical Brazilian e-commerce dataset. The workflow combines PostgreSQL analysis, Python data extraction and validation, and CSV-powered Streamlit visualizations.

| 99,441 | 96,470 | 6.77% | 10.62 days |
| :---: | :---: | :---: | :---: |
| Orders in dataset | Eligible delivered orders | Late-delivery rate | Avg. delay among late orders |

**Technical work and findings**

- Created relational PostgreSQL tables, imported order and customer records, and validated referential integrity.
- Used joins, CTEs, window functions, and aggregations to analyze delivery performance across **27 Brazilian states** and **23 purchase months**.
- Investigated **1,359** carrier-before-approval timestamp anomalies and documented missing delivery timestamps and analytical eligibility rules.
- Developed a reusable **Python/pandas + SQLAlchemy** extraction workflow, with assertions checking regional and monthly totals before exporting dashboard-ready CSVs.
- Deployed a **Streamlit dashboard** with three dynamic KPI cards, an interactive state-level delivery-volume filter, a regional bar chart, monthly late-delivery trends, and expandable data tables.

**[Explore the live dashboard →](https://olist-shipment-delay-analysis.streamlit.app/)**

### 02 / Hubas — NASA Space Apps Challenge 2026

**Team MangoSpace · Satellite data · AI-assisted engineering**

[**Live application**](https://hubas.vercel.app/) · [**Source repository**](https://github.com/watsonjph/MangoSpace)

Hubas is a team-built application for exploring soil moisture, dam conditions, and rice-field radar observations in **Cebu and Bohol**, using satellite data from NISAR and other sources.

**Project scope and contributions**

- Participated in an **autonomous Codex-assisted development workflow**, coordinating GitHub contributions related to NISAR data ingestion, file verification, soil-moisture quality checks, and Sentinel-1 processing.
- Contributed AI-assisted changes associated with validation of **76 NISAR granules (~6.35 GB)** and satellite coverage assessments.
- Worked through repository pull requests covering ASF HyP3 batch orchestration (**52 terrain-correction jobs submitted**), pipeline testing, and radar-image inspection features. Submission does not imply all jobs completed.
- Collaborated through **GitHub, GitHub Actions, and Shortcut** on a multi-contributor project.

**Technologies in the project:** Python, NumPy, h5py, Shapely, NASA Earthdata, ASF/HyP3, GitHub Actions, TypeScript.

> Hubas is a collaborative hackathon project. My assigned changes were implemented and tested autonomously with Codex; the broader application and its findings are team work.

### 03 / Room For Rent Management System

**Full-stack application · PHP · MySQL · JavaScript**

[**Repository**](https://github.com/Jbpm3/Room-For-Rent-Management-System)

- Built a rental-management web application using **PHP, MySQL, HTML, CSS, and JavaScript**.
- Designed relational tables and database-backed functionality for managing rental information.
- Practiced SQL integration between a web interface and application backend.

### Other Builds

| Project | Focus | Technologies |
| :--- | :--- | :--- |
| [**DailyDish**](https://github.com/Jbpm3/DailyDish) | AI-featured calorie-tracking mobile application; contributed to frontend development in a team | React Native, TypeScript, Expo |
| [**IsipKard**](https://github.com/Jbpm3/IsipKard) | Flashcard study application | Java |

---

## Current Focus

**Olist analytics workflow — deployed:**

```text
PostgreSQL + SQL analysis
    -> Python/pandas + SQLAlchemy extraction
    -> automated validation + CSV exports
    -> deployed Streamlit dashboard
```

[**View the live dashboard**](https://olist-shipment-delay-analysis.streamlit.app/)

Next, I'm deepening my Python and data engineering fundamentals while exploring API development and cloud storage as potential extensions.

---

<div align="center">
<sub>Projects over buzzwords. Evidence over assumptions.</sub>
</div>
