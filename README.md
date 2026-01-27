# Maternal Mortality: Progress, Plateaus, and Who Is Being Left Behind (2000–2023)

## Overview

Maternal mortality is one of the most sensitive indicators of health system performance, equity, and resilience.  
Over the past two decades, the world has made undeniable progress in reducing maternal deaths, yet that progress has slowed, stalled, and in some places reversed.

This repository analyzes **global, regional, and country-level maternal mortality trends from 2000 to 2023**, using **WHO data released in April 2025**, to understand:

- Where progress has occurred — and where it has stalled
- How absolute burden and relative improvement tell different stories
- Whether current trajectories are sufficient to meet the **SDG 2030 target** of fewer than **70 maternal deaths per 100,000 live births**

Rather than relying on single-year snapshots, this work examines **long-term trends**, highlights **structural patterns**, and projects **current trajectories forward to 2030**.

---

## Data Source

- **World Health Organization (WHO)**
- Maternal Mortality Estimates, published **April 2025**
- Coverage: **2000–2023**
- Metric: Maternal Mortality Ratio (MMR), deaths per 100,000 live births

> Regional groupings follow **WHO classifications**, which differ from geographic continents  
> (e.g., *North America includes only the United States and Canada*).

---

## Methodology

### Trend Analysis
- Computed global, regional, and country-level average MMR by year
- Examined trends across:
  - MDG era (2000–2015)
  - SDG era (2016–2023)

### Measuring Progress
Two complementary lenses were used:

- **Absolute change**  
  Reduction in maternal deaths per 100,000 live births

- **Relative change**  
  Percentage change over time

This distinction matters:
- Low-burden countries may show large percentage changes with small absolute shifts
- High-burden countries may show large absolute improvements while remaining far from global targets

### Forecasting
- Fitted linear regression models to historical trends
- Projected maternal mortality to **2030** at regional and country levels
- Assessed alignment with the **SDG target (MMR < 70)**

> Forecasts illustrate trend continuation, not causal prediction.

---

## Key Findings

### Global Trends
- **2000–2015 (MDG era):** Rapid progress (~2.7% annual decline)
- **2016–2020 (SDG era):** Progress stalled
- **2021:** Temporary spike linked to COVID-19 disruptions
- **2022–2023:** Decline resumed, but too slowly

**The world is not on track to meet the SDG 2030 maternal mortality target.**

---

### Regional Patterns
- Early gains in several regions have plateaued
- **Sub-Saharan Africa** remains the highest-burden region despite improvements
- **North America** shows a long-term increase despite low overall MMR
- WHO regional groupings reveal dynamics masked by geographic classifications

---

### Country-Level Insights
- Some high-burden countries achieved large **absolute reductions**
- Several low-burden countries show **worsening trends**
- Maternal health gains are fragile and reversible without sustained investment

---

## Why This Matters

Maternal mortality reflects more than clinical care:

- Health system strength
- Equity in access to services
- Political and economic stability
- Long-term investment in women and girls

Stalled progress is not a failure of medical knowledge.  
It is a failure of **systems, governance, and sustained commitment**.

---

## Repository Structure

- data/ # Raw and cleaned WHO datasets
- notebooks/ # Analysis and modeling notebooks
- figures/ # Final visualizations
- forecasts/ # Regional and country projections to 2030
- README.md

---

## Limitations

- Linear forecasts do not capture shocks, reforms, or nonlinear change
- Regional classifications may differ from common geographic assumptions
- Data quality varies across countries and years
- Forecasts should be interpreted as **scenarios**, not predictions

---

## Communication & Outputs

This analysis is shared through:
- A **3-part LinkedIn series** (global → regional → country insights)
- Public-facing visualizations
- Policy-relevant framing aligned with SDG 2030 discussions

---

## Author

*Anthonia Agbonile*  
Public Health • Data Science • Global Health Equity
