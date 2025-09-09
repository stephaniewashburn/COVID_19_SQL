# COVID_19_SQL
COVID-19 SQL Project
# COVID-19 SQL Mini-Project

A quick, portfolio-style SQL analysis of COVID-19 case trends using **SQLite**.

## Goal
Showcase SQL skills by loading public CSVs and producing a compact **monthly trends** table per country (latest 3 months), including **month-over-month (MoM) deltas**, **MoM %**, and a **3-month total**.

## Data
CSV files (included with the project or from the same dataset):
- `full_grouped.csv` — country-by-day cumulative counts (Confirmed, Deaths, Recovered, …)
- `worldometer_data.csv` — latest country totals + **Population** (optional for per-million rates)
- `country_wise_latest.csv` — latest per-country snapshot (optional for CFR/WHO region)

## What’s produced
**Monthly last-3-months table** for selected countries (example: US, China, India):

Columns:
- `country`
- `latest_month`, `latest_cases`
- `prev_month`, `prev_cases`
- `prev2_month`, `prev2_cases`
- `mom_change` (latest − previous month)
- `mom_pct` (percent change vs previous month)
- `total_3mo` (sum of the last three months)


