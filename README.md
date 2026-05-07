# Global Forest Report — Deforestation & Coverage Analysis

**Tools:** Power BI, DAX  
**Domain:** Environmental Analytics | Geographic Analysis | Trend Forecasting  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes global forest coverage, deforestation rates, and fire-affected forest areas from 1990 to 2020 across all major nations. The dashboard tracks how forest area has changed over three decades, identifies the countries driving the most deforestation, and surfaces correlations between deforestation levels and total forest area — providing data-backed insights into the state of global forests.

---

## Dashboard Preview

<img width="978" height="551" alt="image" src="https://github.com/user-attachments/assets/f00c3d51-9026-4218-bb02-cfa0cbcd589e" />

---

## Dataset

| Field | Description |
|---|---|
| Period | 1990, 2000, 2010, 2015, 2020 (5 snapshot years) |
| Countries | All major nations with forest data |
| Metrics | Total land area, forest area, deforestation volume, fire-affected area |
| Units | Square kilometers (thousands) |

---

## Key Metrics (All-Time / Latest)

| Metric | Value |
|---|---|
| Total Land Area | 65.19M km² |
| Total Forest Area | 20.64M km² |
| Forest Coverage % | 31.67% |
| Total Deforestation | 37.57K km² |
| Deforestation % | 0.18% |
| Fire Affected Forest | 490.21K km² |
| Fire Affected % | 2.37% |

---

## Dashboard Features

- **Year filter** (1990 / 2000 / 2010 / 2015 / 2020) — snapshot comparisons across decades
- **Forest Area over Years** — declining trend line from 1990 to 2020
- **Most Forest Area** — top countries by total forest coverage
- **Highest Deforestation** — top countries by deforestation volume
- **Relation b/w Deforestation and Forest Area** — scatter plot showing if larger forests lose more
- **Relation b/w Forest Fire and Forest Area** — scatter showing fire impact vs forest size

---

## Forest Area Trend (1990–2020)

| Year | Global Forest Area |
|---|---|
| 1990 | 4,236K (units) |
| 2000 | 4,158K |
| 2010 | 4,106K |
| 2015 | 4,084K |
| 2020 | 4,059K |

**Net loss over 30 years: ~177K units — a consistent, unbroken decline every decade.**

---

## Countries with Most Forest Area

| Country | Forest Area |
|---|---|
| Russian Federation | 815K |
| Brazil | 589K |
| Canada | 348K |
| United States | 310K |
| China | 220K |

---

## Countries with Highest Deforestation

| Country | Deforestation |
|---|---|
| Brazil | 1,696 |
| India | 668 |
| Indonesia | 650 |
| United Republic of Tanzania | 474 |
| Myanmar | 294 |

---

## Key Findings

**1. Global forest area has declined every single decade from 1990 to 2020**
The forest area trend line shows an unbroken downward trajectory — from 4,236K in 1990 to 4,059K in 2020. There has been no decade of net recovery in 30 years of data.

**2. Brazil is simultaneously the second largest forest nation AND the highest deforestation country**
Brazil holds 589K units of forest (2nd globally) but leads all nations in deforestation at 1,696 units — a direct reflection of Amazon deforestation driven by agriculture and cattle ranching expansion.

**3. Deforestation is concentrated in tropical nations despite Russia holding the most forest**
Russia has the largest forest area (815K) but minimal deforestation. The highest deforestation happens in tropical regions — Brazil, India, Indonesia, Tanzania, Myanmar — where economic pressure on forest land is highest.

**4. Fire-affected forest (490K km²) is 13x larger than directly deforested area (37.57K)**
Forest fires affect far more land than direct deforestation — suggesting that fire, often linked to deforestation activity, is the larger acute threat to forest coverage.

**5. The deforestation-forest area scatter shows no strong size dependency**
Larger forest nations don't necessarily deforest proportionally more — the scatter is diffuse, suggesting that policy environment and economic pressure matter more than forest size in driving deforestation rates.

**6. Only 31.67% of total land area is forested**
Less than a third of Earth's total land is covered by forest — context that makes the ongoing 0.18% annual deforestation rate more significant in absolute terms.

---

## Technical Highlights

- Year-based snapshot filtering enabling decade-by-decade comparison
- Dual scatter plots for deforestation correlation analysis
- Trend line chart showing 30-year forest decline trajectory
- DAX measures for forest %, deforestation %, and fire-affected % calculations
- Country-level bar rankings for forest area and deforestation side by side

---

## Data Source

World Bank — Forest Area Dataset. FAO Global Forest Resources Assessment.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
