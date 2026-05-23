# Fuel Sales BI Pipeline

End-to-end BI project for a network of 10 fuel stations in Brazil.
Built entirely by me, from raw data extraction to executive dashboard.

## What this project does

- Migrated 1M+ rows of sales data from Excel to PostgreSQL 18
- Built an incremental load script in Python to append new data monthly
- Connected Power BI to PostgreSQL and developed an executive dashboard
- Performed exploratory data analysis (EDA) in Google Colab

## Tech Stack

- **Database:** PostgreSQL 18
- **ETL:** Python (pandas, SQLAlchemy)
- **Visualization:** Power BI
- **EDA:** Python (pandas, matplotlib, seaborn) — Google Colab

## Pipeline Architecture
## Dashboard Pages

- **General** — Revenue KPIs, weekly/monthly variation, product mix, performance by station
- **Unidentified Sales** — Analysis of transactions without customer ID (% volume, ticket average, trends)
- **Price Analysis** — Average fuel price over time (monthly and weekly)
- **Customer Analysis** — Top customers, retention, ticket segmentation
- **Risk Analysis** — Anomaly detection and operational risk indicators

## Dataset

The data in this repository is **synthetic** — numeric values were anonymized using randomized scaling factors per station, and all customer/station names were replaced with generic aliases. The original dataset contains confidential business information and is not publicly available.

## Key Results

- Reduced report generation time from hours (manual Excel) to minutes (automated pipeline)
- Enabled cross-station performance comparison for 3 regional clusters
- Identified patterns in unidentified sales representing a significant share of total volume

## Author

Lucas Zanella — BI Analyst & Data Science student
[LinkedIn](#) · [GitHub](https://github.com/lucaszanella00)
