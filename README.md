# Grade4_Math_Multilevel_Analysis_TIMMS2023
Identifying Key Predictors of U.S. Grade 4 Math Achievement (TIMMS  2023) 

This project examines how student- and school-level factors , including digital access, influence Grade 4 mathematics achievement in the U.S., integrating multiple datasets and applying advanced data science methods.

## Research Purpose
- **RQ1:** Which student-level factors (technology access, engagement, home resources/SES, school climate) are most predictive of math achievement using Random Forest under school-grouped validation?
- **RQ2:** How much variance in math achievement is explained by school-level technology support and climate when included in a two-level Hierarchical Linear Model (HLM)?

## Data Sources
- TIMSS 2023 Grade 4 U.S. Student, School, and Teacher Data

## Methodology & Data Preparation
1. **Data Selection & Integration:** Chose relevant datasets from multiple sources and merged them.
2. **Variable Identification:** Selected variables aligned with research questions.
3. **Data Cleaning & Missing Data Handling:** Prepared datasets, handled inconsistencies, and applied MICE for imputation.
4. **Scale Preparation & Reliability:** Reverse-coded items for scale consistency, calculated Cronbach's alpha, and conducted factor analysis to create composite variables.
5. **Random Forest:** Identified top student-level predictors.
6. **Hierarchical Linear Modeling (HLM):** Planned to estimate school-level effects.
7. **Planned Visualizations:** Will create plots and dashboards once analysis is complete.

## Current Status
- **Analysis:** Ongoing.
- **Preliminary Findings:** In progress
- **Publication Target:** Aiming for **Education and Information Technologies (EAIT)**.

## Tools & Skills
- **Python:** pandas, numpy, scikit-learn (Random Forest), MICE (via fancyimpute or statsmodels)
- **Data Analysis:** Descriptive statistics, correlation analysis, reliability testing, factor analysis
- **Statistical Methods (planned):** Hierarchical Linear Modeling (HLM), Multilevel Analysis
- **Data Visualization (planned):** Dashboards and plots



