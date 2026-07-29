# Pakistan Employment Trends & Global Comparison Dashboard | 1991–2030

An interactive Tableau dashboard analyzing employment rate trends in Pakistan (1991–2025) with forecasts through 2030, benchmarked against 183 countries worldwide.

![Dashboard Preview](Pakistan_Employment_Trends___Global_Comparison_Dashboard.png)

## Overview

This project analyzes Pakistan's employment rate (age 25+) by gender over 35 years and forecasts the trend to 2030 using Tableau's built-in forecasting model. It also benchmarks Pakistan against the top-performing countries globally on the same metric.

**Tools used:** Tableau · Data Visualization · Trend Forecasting

## Key Insights

- **Overall employment rate (age 25+)** has grown steadily from ~53% (1991) to ~55.8% (2016), and is forecast to continue rising toward 2030.
- **Male employment rate** has been on a long-term decline, from a peak of **90.61%** (1998) to a low of **83.54%** (2020).
- **Female employment rate** has more than doubled, rising from **13.39%** (1995) to over **25%** by 2025 — the most significant structural shift in the data, with continued growth (**25.53%**) forecast by 2030.
- **Global ranking (2025):** Pakistan is not among the top 9 countries by employment rate. The list is led by **Tanzania (81.71%)**, **Madagascar (80.71%)**, **Solomon Islands (80.44%)**, and **Cambodia (79.18%)**.

## Dashboard Views

1. **Pakistan Employment Rate Trend (Age 25+, 1991–2030)** — overall trend with a forecast band
2. **Male Employment Trend (Age 25+)** — long-term decline in male employment
3. **Female Employment Trend (Age 25+)** — long-term rise in female employment
4. **Top 9 Countries by Employment Rate (Age 25+, 2025)** — global benchmark comparison

Interactive filters: **Sex** (Female / Male / Total) and **Country** (183 countries available).

## Files

| File | Description |
|---|---|
| `Pakistan_Employment_Trends___Global_Comparison_Dashboard.twbx` | Packaged Tableau workbook (interactive dashboard) |
| `Pakistan_Employment_Trends___Global_Comparison_Dashboard.csv` | Source dataset |
| `Pakistan_Employment_Trends___Global_Comparison_Dashboard.png` | Dashboard image export |
| `Pakistan_Employment_Trends___Global_Comparison_Dashboard.pdf` | Dashboard PDF export |

## Dataset

~57,500 rows of employment rate observations across 183 countries and 35 years (1991–2025).

| Column | Description |
|---|---|
| `iso_code` | 3-letter ISO country code |
| `country` | Country name |
| `sex` | Total / Male / Female |
| `age` | Age group: 15+, 15–24, or 25+ |
| `year` | Observation year (1991–2025) |
| `obs_value` | Employment-to-population ratio (%) |

## How to View

1. Download the `.twbx` file.
2. Open it in [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/) (free).
3. Use the **Sex** and **Country** filters to explore other breakdowns.

Or view the `.png` / `.pdf` exports for a quick, no-install look.

## Author

**Shad Ali Shah**
MPhil Economics Candidate, Quaid-i-Azam University | Data Analytics & BI
[GitHub](https://github.com/shadalishah) · [LinkedIn](https://linkedin.com/in/shad-ali-shah) · [Portfolio](https://shad-data-science.lovable.app)
