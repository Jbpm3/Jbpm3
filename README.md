<div align="center">

# Josh Bernard Magsipoc

**Data Engineering · SQL · Data Analytics**

Building practical data projects with an emphasis on **data quality, reproducible analysis, and useful results**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josh-bernard-magsipoc-12b78a2b1)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Jbpm3)

</div>

---

## Featured Projects

### 01 / Olist — E-Commerce Shipment Delay Analysis

**Independent data analysis · PostgreSQL · SQL · Data validation**

[**Repository**](https://github.com/Jbpm3/olist-shipment-delay-analysis) · [**SQL analyses**](https://github.com/Jbpm3/olist-shipment-delay-analysis/tree/main/sql) · [**Findings**](https://github.com/Jbpm3/olist-shipment-delay-analysis/blob/main/docs/findings.md)

Analyzing historical Brazilian e-commerce orders to measure shipping performance, detect data-quality issues, and identify where delivery delays are concentrated.

| 99,441 | 96,470 | 6.77% | 10.62 days |
| :---: | :---: | :---: | :---: |
| Orders in dataset | Eligible delivered orders | Late-delivery rate | Avg. delay among late orders |

**Technical work and findings**

- Created PostgreSQL tables with relational constraints, imported customer and order records, and validated referential integrity.
- Wrote SQL for delivery classification, delay-duration metrics, conditional aggregation, and comparisons across **27 Brazilian states**.
- Investigated **1,359** cases where carrier handoff timestamps preceded order approval; documented **2,965** missing delivery timestamps and the eligibility rules for delay analysis.
- Identified high late-delivery rates among orders purchased in **March 2018 (18.96%)**, **February 2018 (14.13%)**, and **November 2017 (12.40%)**. Monthly figures were calculated locally; the project is still being documented.

**Next milestone:** Extend the existing SQL work with a Python/pandas export workflow and deploy a **Streamlit dashboard**. *Not deployed yet.*

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

- Currently building independent Python/pandas proficiency for extracting, validating, and preparing analytical datasets.
- Exposure to h5py, Shapely, satellite-data tooling, and automated checks through AI-assisted team development.

**Software and development tools**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111827)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

Git · GitHub · pgAdmin · VS Code · GitHub Actions (team-project exposure) · Shortcut · Codex

---

## Currently Building

\`\`\`text
Olist SQL analysis
    -> Python + pandas data export
    -> validated analytical datasets
    -> interactive Streamlit dashboard
\`\`\`

The goal is an end-to-end analytics project that connects **database analysis**, **Python data processing**, **data validation**, and a **public-facing dashboard**.

---

<div align="center">
<sub>Projects over buzzwords. Evidence over assumptions.</sub>
</div>
