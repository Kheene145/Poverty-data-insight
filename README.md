#  📊 Extreme Poverty Analysis (1985–2018)

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitation](#limitations)
- [References](#references)


## Project Overview
- This project analyzes global and regional trends in extreme poverty between 1985–2018, with a special case study on Nigeria.
- By combining poverty share data with GDP per capita, the analysis explores whether economic growth translates into broad-based poverty reduction and improved living standards.
---



## Data Source

- Poverty Dataset:

- Columns: Country, Year, Share of Population in Poverty (% of population in extreme poverty)

- Source: World Bank, Our World in Data

- GDP Dataset (Nigeria):

- Columns: Year, GDP_per_capita

- Derived variable: Daily Income ($) = GDP_per_capita ÷ 365

---


### Tools
Python Libraries: Pandas, Matplotlib, Seaborn
Jupyter Notebook: Data cleaning, analysis, and visualization


## Data Cleaning Preparation

In the initial data preparation phase, the following steps were carried out:

Cleaned missing values and ensured numeric formatting for key variables.

Standardized Year format for merging across datasets.

Created derived feature: Daily Income = GDP per capita ÷ 365.
---

## Exploratory Data Analysis (EDA)

Key questions explored:

How has global poverty changed between 1985–2018?

Which regions reduced poverty fastest, and which lagged?

Which countries achieved the largest poverty reduction?

In Nigeria, does rising GDP per capita correspond to falling poverty share?

---

### Data Analysis

The analysis involved:

Line Charts: Global and regional poverty share trends.

Multi-Line Comparison: Africa, Asia, and Latin America.

Bar Plots: Top 10 countries with largest poverty reduction.

---


### Results/Findings

- Global: Poverty declined from ~40% (1985) to ~10% (2018), showing major progress.

#### Regional:

- East Asia (e.g., China, Vietnam) achieved the fastest poverty reduction.

- Sub-Saharan Africa remains the region with the highest poverty rates.

- Country-Level: Top 10 countries demonstrated significant reductions, led by East Asian economies.

#### Nigeria Case Study:

- Average daily income ~ $2.7/day, yet millions live on <$2/day.

- Revealed mismatch between GDP growth and poverty reduction.

- Key drivers: inequality, reliance on averages, informal economy, and differences in PPP-based poverty measures.

---


### Recommendations

- Policy Focus: Pair GDP growth with redistributive policies to ensure benefits reach low-income households.

- Targeted Programs: Increase investment in education, health, and rural development in Sub-Saharan Africa.

- Income Measures: Complement GDP with household surveys, PPP-adjusted data, and inequality indices for realistic poverty tracking.

- Nigeria: Implement poverty alleviation programs that directly target vulnerable populations, rather than relying solely on GDP growth.in Nigeria.

---


### Limitations

- Poverty dataset limited to broad indicators, lacking household-level detail.

- GDP per capita is an average and does not capture income inequality or wealth distribution.

- Informal economic activity and regional disparities may be underrepresented.

- No integration of qualitative data (e.g., employment, access to services, social protection).

---

### References

1. ourworldindata.org[https://ourworldindata.org/grapher/share-of-population-in-extreme-poverty?]
   dataworldbank.org[https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?locations=]

2. Python libraries such as:
   - Pandas
   - Matplotlib
   - Seaborn
  
     ---




