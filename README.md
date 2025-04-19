# toxoplasmosis-analysis
Risk factor analysis of toxoplasmosis in cats using R
# Toxoplasmosis Analysis in Cats

This project investigates the **prevalence and risk factors of toxoplasmosis** in cats using statistical methods in R. It combines data from cat owners, cat characteristics, and test results (IGM and IGG) to understand which factors are associated with a higher likelihood of infection.

## Project Structure

- `merged_toxoplasmosis_data.xlsx` — Cleaned and merged dataset
- `toxoplasmosis_analysis.Rmd` — R Markdown file for technical analysis and reporting
- `toxoplasmosis_analysis.html` — Rendered report from the R Markdown file
- `README.md` — Project overview and documentation

## Tools & Packages

- **R**
- `tidyverse`
- `readxl`
- `dplyr`
- `ggplot2`
- `epitools`
- `broom`
- `knitr`
- `rmarkdown`

## 🔍 Analysis Overview

- **Data Cleaning & Merging**: Combined data from three sheets — owner info, cat info, and toxoplasmosis results — into one dataframe using `cat_number` as a key.
- **Derived Variable**: Created `toxo_status` based on IGM and IGG results.
- **Descriptive Statistics**: Summarized key variables using tables and plots.
- **Statistical Testing**:
  - Chi-square tests for categorical relationships
  - Fisher’s Exact Test where appropriate
  - Logistic regression to identify risk factors

## Key Outcomes

- Identified specific factors that may be associated with a higher prevalence of toxoplasmosis in cats
- Produced both technical and non-technical reports to cater to different stakeholders

## Sample Visualizations

- Bar charts showing distribution of positive cases
- Odds ratio tables for risk factors
- Regression coefficient plots

## How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/jonathan-ndayisenga/toxoplasmosis-analysis.git
   cd toxoplasmosis-analysis

