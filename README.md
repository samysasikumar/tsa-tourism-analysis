# International Tourism Arrivals — India & United States (1995–2025)

**TSA Data Science Competition Project**  
Samyuktha Sasikumar · Redmond High School · 2025

---

## Overview

This project analyzes international tourist arrivals for India and the United States using 25 years of open data from the World Bank. Using linear regression in Microsoft Excel, historical trends from 1995–2019 were modeled and used to forecast post-pandemic recovery through 2025.

Submitted as a scientific poster for the TSA (Technology Student Association) Data Science event.

---

## Dataset

| Field | Details |
|---|---|
| Name | International tourism, number of arrivals |
| Source | World Bank — World Development Indicators |
| Indicator code | ST.INT.ARVL |
| URL | https://data.worldbank.org/indicator/ST.INT.ARVL |
| File | `API_ST_INT_ARVL_DS2_en_csv_v2_8599.csv` |
| License | CC BY-4.0 — open data, free for research and educational use |
| Period used | 1995–2019 (latest complete pre-COVID data) |

---

## Methodology

1. Downloaded the World Bank CSV and filtered for **India** and **United States**
2. Plotted annual arrivals (1995–2019) as a line chart in Excel with Year on the X-axis and Number of Arrivals on the Y-axis
3. Applied a **linear regression trendline** to each country's data series
4. Displayed the regression equation (`y = mx + b`) and R² value on the chart
5. Used each equation to calculate predicted arrivals for 2021–2025

No programming was used — all analysis was performed in Microsoft Excel.

---

## Historical Data (Selected Years)

| Country | 1995 | 2000 | 2010 | 2019 |
|---|---|---|---|---|
| India | 2,124,000 | 2,649,000 | 5,776,000 | 17,914,000 |
| United States | 79,732,000 | 78,343,000 | 162,275,000 | 165,478,000 |

---

## Forecast (2021–2025)

Predicted values derived from linear regression equations applied to 1995–2019 data.

| Year | India (Predicted) | United States (Predicted) |
|---|---|---|
| 2021 | 15,601,555 | 182,732,501 |
| 2022 | 16,239,521 | 187,008,290 |
| 2023 | 16,877,486 | 191,284,078 |
| 2024 | 17,515,452 | 195,559,867 |
| 2025 | 18,153,417 | 199,835,655 |

---

## Key Findings

- **India** grew from approximately 2 million arrivals (1995) to nearly 18 million (2019) — a roughly 9x increase over 25 years, reflecting rapid expansion of its tourism sector
- **United States** maintained a consistently high volume of international visitors, with projections approaching 200 million arrivals by 2025
- The two countries show contrasting tourism profiles: India on a steep growth curve, the USA on a more gradual upward trend
- Linear regression applied to pre-pandemic data provides a useful baseline for estimating recovery timelines, though actual 2020 arrivals dropped sharply (India: data unavailable; USA: ~45 million) due to COVID-19

---

## Conclusion

Open-source datasets and basic statistical tools can yield meaningful insights into global tourism trends. Both India and the United States show long-term growth resilience. The linear regression approach demonstrates how Excel-based analysis can produce quantitative forecasts without requiring programming — a foundational data science skill.

---

## Files in This Repo

| File | Description |
|---|---|
| `README.md` | This document |
| `API_ST_INT_ARVL_DS2_en_csv_v2_8599.csv` | World Bank source data (all countries, 1960–2020) |
| `Tourism_Analysis_Poster_Report.docx` | Full scientific poster report |

---

## Citation

World Bank. (2025). *International tourism, number of arrivals (ST.INT.ARVL)*.  
World Development Indicators. Retrieved from https://data.worldbank.org/indicator/ST.INT.ARVL  
License: CC BY-4.0
