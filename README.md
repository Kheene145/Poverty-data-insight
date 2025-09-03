#  📊 Extreme Poverty Analysis (1985–2018)
## 📌 Project Overview
### This project analyzes global and regional trends in extreme poverty between 1985–2018, with a case study on Nigeria.
### We combine poverty share data with GDP per capita to explore how poverty reduction relates to economic growth, and whether GDP growth translates to improved living standards.


## Dataset

### Poverty Dataset

#### Country, Year, Poverty_Share (% of population in extreme poverty).

#### Source: World Bank & Our World in Data.

#### GDP Dataset (Nigeria)

#### Year, GDP_per_capita.

#### Derived daily income = GDP_per_capita / 365.



## ⚙️ Steps Taken


### 🔹 Step 1: Data Preparation

#### Cleaned missing values, converted columns to numeric.

#### Ensured consistent Year format for merging datasets.

#### Calculated Daily Income ($) = GDP per capita ÷ 365.


## 🔹 Step 2: Exploratory Data Analysis (EDA)

### Global Trend ➡️ Poverty declined from ~40% (1985) to ~10% (2018).

#### Regional Comparison ➡️

#### East Asia reduced poverty fastest (China, Vietnam).

#### Sub-Saharan Africa still has the highest poverty rates.

#### Country Highlights ➡️ Identified top 10 countries with the greatest poverty reduction.


### 🔹 Step 3: Visualizations

#### Global Line Chart ➡️ Global average poverty share (1985–2018).

#### Regional Multi-Line Chart ➡️ Africa vs. Asia vs. Latin America.

#### Bar Chart ➡️ Top 10 countries with largest % reduction.

#### Nigeria Dual-Axis Plot ➡️

#### ◾ Left axis: Poverty Share (%)

#### ◾ Right axis: Average Daily Income ($)


### 🔹 Step 4: Nigeria Case Study

#### Key finding: Nigeria’s dataset shows “daily income”  ~ $2.7/day, but millions live on <$2/day.

###  🔹 Why the mismatch?

#### 🔹 GDP per capita != wages ➡️ It’s an average of total economic output.

#### 🔹 Inequality ➡️ A small elite earns much more, pulling the average up.

#### 🔹 Informal economy ➡️ Many livelihoods are undercounted.

#### 🔹 PPP adjustments ➡️ Poverty lines use purchasing power, not direct USD.

#### Conclusion: Economic growth has not translated into broad poverty reduction in Nigeria.


### 📈 Insights

#### Global poverty has declined significantly, but unevenly.

#### East Asia’s progress was rapid, Africa’s slower.

#### Nigeria’s case highlights the gap between GDP and lived experience.

#### GDP growth != poverty reduction when inequality remains high.

#### Poverty analysis requires both macro indicators (GDP) and micro measures (household surveys, PPP, inequality).

#### Reveals mismatch between GDP growth and poverty reduction.
