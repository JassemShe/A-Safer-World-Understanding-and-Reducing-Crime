# A Safer World: Understanding and Reducing Crime

> _Exploring how gender demographics relate to crime — to help build safer, smarter societies._

---

## 🔍 Project Overview

This data-driven project investigates whether **male-to-female population ratios correlate with crime rates** across countries, with a deeper focus on **age-specific demographics** and **crime categories** (violent, sexual, and economic). The goal: uncover patterns that inform **policy-making**, **urban planning**, and **insurance risk models**.

Using global datasets from trusted sources like **UN Crime & Demographics**, **Our World in Data**, and **Kaggle**, the study applies rigorous data cleaning, transformation, and statistical analysis to derive actionable insights.

---

## 📊 Summary of Work

### Methodology Highlights:
- **Data Integration** from multiple sources with heterogeneous structures.
- **Advanced Data Wrangling** to align age groups, calculate gender ratios, and engineer new features (e.g., population density, education spending categories).
- **Exploratory Data Analysis** (EDA) with visualizations, correlation studies, and outlier inspection.
- **Statistical Testing** using ANOVA and Tukey HSD to validate observed differences.
- **Dashboarding** to make findings digestible and interactive.

### Key Findings:
- Weak overall correlation (0.089) between male-to-female ratios and crime rates, but **higher gender imbalances correlate with greater variability in crime**.
- For **Mature Adults (45–64)**, male-heavy populations show a **moderate positive correlation (~0.25)** with violent and corruption crimes.
- **High male-to-female ratios in other age groups** (especially Young Adults) are also associated with **elevated mean crime rates**.
- Surprisingly, **higher public education spending correlates with higher crime rates (0.43)** — likely due to **reporting quality or misallocated resources**.
- Female populations consistently outnumber males, yet **gender ratio fluctuations show predictive potential** for crime trends.

---

### 🔧 Data Strategy & Quality Focus
- Emphasized **data quality early** through profiling: checking nulls, duplicates, outliers, and inconsistencies.
- Made nuanced decisions like **excluding zeroes in crime columns** (treating them as missing, not true zeros).

### 🧪 Smart Feature Engineering
- Grouped population data into **analytically meaningful age brackets**.
- Created **derived features** like male-to-female ratios, population density, and categorical education spending for sharper comparisons.

### 🔬 Beyond Surface-Level Insights
- Went deeper than overall correlations: **segmented by age group, crime type, and region**.
- Interpreted counter-intuitive results (e.g., education vs. crime) with **hypothesis-driven reasoning** 

### 📐 Statistical Rigor
- Used **ANOVA + Tukey HSD** to test if crime rate differences across gender ratio groups were statistically significant.
- Validated insights with **quantitative evidence**, not just visuals.

### 🚀 Actionable Implications
- Proposed real-world applications: e.g., governments should track male-heavy demographics in crime prevention, and insurers can refine crime-risk pricing.
- Outlined **future directions** for more granular research in specific regions or cities, with standardized crime definitions.





