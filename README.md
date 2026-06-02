<h1 align="center">Hi, I'm Piotr 👋</h1>
<h3 align="center">Data Analyst & BI Developer</h3>

<p align="center">
  I build end-to-end data pipelines — from raw public datasets to interactive dashboards.<br/>
  Focused on logistics & transport analytics, SQL, Python ETL, and Power BI.
</p>

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📦 Featured Projects

### 🚛 [Transport Cost Analytics Dashboard](https://github.com/kutpiotr/transport-cost-analytics)

> SQL + Power BI end-to-end analytics for a fictional logistics company

**Stack:** PostgreSQL · Power BI · DAX  
**What I built:**
- Relational schema with 5 tables (`shipments`, `carriers`, `routes`, `costs`, `delays`)
- 1 000-row synthetic dataset with intentional anomalies for data quality demo
- Data cleansing pipeline in SQL: duplicate removal, NULL imputation, outlier reclassification
- 3 analytical views: `vw_cost_per_km`, `vw_on_time_rate`, `vw_monthly_trends`
- Power BI dashboard: cost overview + delivery performance pages, built-in forecast

**Key KPIs:** Cost per km · On-time delivery rate · Delay rate · Monthly cost trend

---

### 🌍 [European Freight & Logistics Market Analysis](https://github.com/kutpiotr/european-freight-analysis)

> Real Eurostat data (road_go_ta_tott) analysed with Python → PostgreSQL → Power BI

**Stack:** Python (pandas) · PostgreSQL · SQLAlchemy · Power BI · DAX  
**What I built:**
- Eurostat API client parsing JSON-stat 2.0 → flat CSV
- Multi-step ETL: missing value strategy, country code standardisation (ISO 3166-1), unit normalisation
- Star schema: `fact_freight` + 3 dimension tables (`dim_country`, `dim_year`, `dim_cargo_type`)
- 5 analytical SQL views including YoY growth with LAG window functions and market share %
- Power BI dashboard: Europe filled map + country rankings + YoY trend with cross-filtering

**Key KPIs:** Total volume (tonnes) · YoY Growth % · Market Share % · CAGR

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kutpiotr&show_icons=true&theme=default&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kutpiotr&layout=compact&theme=default&hide_border=true" height="150"/>
</p>

---

<p align="center">
  <a href="mailto:kutpiotr1@gmail.com">📧 kutpiotr1@gmail.com</a>
</p>
