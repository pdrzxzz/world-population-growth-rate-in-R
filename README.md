# World Population Growth Rate Analysis

## Overview
Analysis of world city population growth rates using R. The project includes data cleaning, summary statistics, outlier detection, visualization, normality testing, and hypothesis testing.

## Data
- Dataset: `world-population-growth-rate.csv`
- Contains population data for 2023, 2024, growth rates, continent, country, and city.

## Key Steps
- Data preprocessing: convert growth rate to %, fix typos, remove missing continents.
- Descriptive statistics: mean, median, sd of growth rates and populations.
- Outlier detection: boxplot and identification of cities with extreme growth rates.
- Visualization: histograms and bar charts by continent.
- Normality test: Anderson-Darling test before and after removing outliers.
- Hypothesis testing:  
  1. Growth rates in Americas vs other continents.  
  2. Growth rate in Japan vs other countries.

## Results
- Americas have significantly lower growth rates than other continents.
- Japan’s growth rate is significantly lower than other countries.
- Growth rate distribution improves normality after removing positive outliers.

## Requirements
- R packages: `dplyr`, `ggplot2`, `plotly`, `nortest`

## Usage
1. Put CSV file in working directory.
2. Run script to see statistics, plots, and test results.

---

Made by [pdrzxzz](https://github.com/pdrzxzz) | Computer Science Student 🎓
