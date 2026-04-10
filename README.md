<div align="center">

# Piyush Panthi
### Data Analyst · SQL · Python · BigQuery · Snowflake · Tableau · Power BI · Excel · Machine Learning

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/piyushpanthi)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:piyushpanthiofficial@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PiyushPanthi07)

</div>

---

## About

I build **end-to-end analytics systems** — from raw data extraction through cloud warehousing to live executive dashboards. My internship at Verve Advisory had me owning a full production pipeline: ingested 1M+ CRM rows into a BigQuery Medallion warehouse, wrote advanced SQL for cohort retention and LTV modeling, and delivered a Google Sheets dashboard (Apps Script + BigQuery API) that cut manual reporting by ~70%.

Currently targeting **Financial Data Analyst** roles in fintech and financial services — JPMC, Amex, Barclays, Razorpay, Big 4.

---

## Tech Stack

| Layer | Tools |
|---|---|
| **Languages** | Python (Pandas, NumPy) · SQL (Window Functions, CTEs, Subqueries) |
| **Cloud & Warehouse** | Google BigQuery · Snowflake · AWS S3 · GCP |
| **Orchestration & ETL** | Python ETL pipelines · Stitch.io · Apps Script · DBeaver |
| **BI & Visualization** | Tableau · Google Sheets · Power BI |
| **Data Architecture** | Medallion Architecture (Bronze→Silver→Gold) · Star Schema · Data Modeling |
| **Other** | Microsoft Excel · GitHub · PostgreSQL |

---

## Featured Projects

### 🏦 Banking Fraud & Risk Analytics Platform
> Python · Snowflake · SQL · AWS S3 · Tableau

Production-grade fraud detection system replicating pipelines used at financial institutions.

- Engineered **1M-row synthetic dataset** across 6 source tables with realistic fraud signals: country mismatches, channel-region bias, AML behavioral patterns
- Architected **Medallion data warehouse on Snowflake** (Bronze→Silver→Gold) with Star Schema and layer-by-layer data quality validation
- Built a **5-component risk scoring model (0–100 pts)** covering velocity, amount anomaly (1.5×/2×/3× baseline), geographic mismatch, merchant risk, device risk — calibrated to realistic distribution: 60% Low / 25% Medium / 12% High / 3% Critical
- Flagged **80K+ orphaned transactions (8%)** in Gambling, Crypto, and Offshore categories as AML/synthetic identity fraud signals with documented governance rationale
- Delivered **5 role-specific Tableau dashboards** with 11 Gold layer analytical views, USD-normalized fraud exposure, and a `recommended_action` decision field

**Scale:** 1M rows · 3-layer pipeline · 5 dashboards · 11 analytical views

---

### 📊 Sales & Customer Analytics Dashboard
> Tableau · Data Modelling · Star Schema

Executive-grade dual dashboard on a 9,994-row, $2.3M retail dataset (2020–2023).

- Designed a star schema connecting 4 tables: Orders, Customers, Products, Location
- Built YoY growth, profit margin %, and KPI flag calculated fields
- **Key finding:** Discounted orders ran at −2.9% margin vs. +29.5% non-discounted — flagged critical pricing inefficiency for the business
- Identified Tables sub-category as a **loss center** ($206K revenue, −$17.7K profit) despite being a top-5 revenue driver — separated volume from profitability
- Implemented container-based layouts with cross-dashboard navigation, dynamic filters (Category, Sub-Category, Region, City), and chart-as-filter interactivity

[![View Project](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/PiyushPanthi07/Sales-Customer-Analytics-Dashboard)

---

## Work Experience

### Data Analyst Intern — Verve Advisory *(Jun–Aug 2025)*
*Built a fully automated cohort analytics system for a US-based subscription client — CRM extraction through BigQuery warehouse to live dashboard.*

- Designed a BigQuery data warehouse using **Medallion Architecture** with **star schema** — 4 fact tables (transactions, refunds, rebills, subscriptions) and 4 dimension tables; tracked KPIs across 6 subscription plans
- Built a **Python ETL pipeline** ingesting **1M+ rows** from Sticky.io CRM CSVs into BigQuery in chunks — handled 155+ columns, auto-detected schema, validated row counts end-to-end
- Wrote advanced SQL in BigQuery for **cohort retention**, churn %, **Net/Gross ARPU**, LTV, refund analysis, and rebill cycle modeling across 5+ marketing channels (Facebook, TikTok, Google Ads)
- Automated a Google Sheets dashboard using Apps Script + BigQuery API — dynamic filters, 20+ KPIs, one-click refresh; **reduced manual reporting by ~70%**
- Integrated multi-platform marketing spend data via Stitch.io; mapped AFID attribution to **CAC/LTV** calculations for channel-level ROI analysis
- Profiled and validated **155+ raw CRM fields**; cross-validated output against PostgreSQL tables via DBeaver to ensure KPI accuracy

*Stack: BigQuery · Python (Pandas) · SQL · Google Sheets · Apps Script · Stitch.io · DBeaver*

---

## Architecture I've Worked With

```
Raw CRM CSVs (Sticky.io)
        │
        ▼
  [Bronze Layer]  ── Raw ingestion, no transformation, full row count validation
        │
        ▼
  [Silver Layer]  ── Cleaned, typed, deduplicated, FK relationships enforced
        │
        ▼
  [Gold Layer]    ── Fact/Dimension star schema, KPI views, cohort models
        │
        ▼
  Google Sheets Dashboard (Apps Script + BigQuery API)
  ── 20+ KPIs │ Dynamic Filters │ One-click refresh
```

---

## Certifications

- 🟣 **Deloitte Australia** — Data Analytics Job Simulation (Forage)
- 🔵 **Microsoft & LinkedIn** — Career Essentials in Data Analysis
- 🟠 **NPTEL** — Data Analytics with Python
- 🟠 **NPTEL** — Big Data Computing
- 🟢 **HackerRank** — SQL (Basic + Intermediate)

---

## Research Publications

- 📄 **"Fall Activity Detection Framework using Deep CNN"** — Presented at *ICIVC 2025*, ICFAI University Dehradun
- 📄 **"Safety Measures in Smart Car Using IoT"** — Published in *Springer Nature, ICSM 2024 Proceedings*

---

## Education

**B.Tech — Artificial Intelligence & Robotics**
Madhav Institute of Technology & Science (MITS), Gwalior · CGPA: 7.7 · *2022–2026*

---

<div align="center">

*Open to Data Analyst roles in Financial Services, Fintech & Consulting.*
*Let's connect — [piyushpanthiofficial@gmail.com](mailto:piyushpanthiofficial@gmail.com)*

</div>
