# U.S. Heart Disease Mortality Explorer (2020)

## Description
A project analyzing **age-adjusted heart disease mortality rates** across U.S. states in 2020.
Using CDC public health datasets, the project examines geographic disparities, explores demographic and regional patterns, and evaluates whether mortality significantly differs across census regions.

The analysis includes:

- Statistical comparison of regions
- Visualization of nationwide variation in heart-disease–related death risk
- Interpretation of spatial patterns and public health implications

The project is delivered as a structured exploratory analysis with statistical testing and visualizations.

## Author
Yuan Ying  

## Date
05/02/2025  

---

## How It's Made:

**Tech used:** R, tidyverse, ggplot2, dplyr, readr, stats, infer (or base hypothesis testing)

This project analyzes CDC-reported age-adjusted heart disease death rates by state (2020).
Using R, the data was cleaned, transformed, grouped by region, and analyzed statistically to understand whether mortality outcomes differ across U.S. Census regions.

**What the analysis does:**

**1. Data Wrangling & Preparation**

- Imported the CDC state-level mortality dataset (age-adjusted heart disease death rate, 2020)
- Selected relevant variables (State, Region, Age-Adjusted Death Rate)
- Created a clean dataset suitable for statistical comparison
- Computed summary statistics by region (mean, SD, IQR, min/max)

**2. Exploratory Data Analysis**

- Generated bar charts and boxplots showing mortality distribution across states and regions
- Identified the Southeast as the highest-burden area
- Highlighted regional patterns linked to structural health disparities
- Compared within-region vs. between-region variability

**3. Statistical Inference**
- Performed hypothesis testing to compare:
  - Midwest vs. West
  - Northeast vs. West
- Computed test statistics and p-values based on the dataset's regional summaries
- Interpreted the significance of differences in age-adjusted heart disease mortality
- Connected statistical results to real-world health implications (e.g., healthcare access, lifestyle, socioeconomic structure)

---

## Features
- Interactive map showing crash locations in California
- County-level choropleth maps of crash counts
- Trend analysis and exploratory plots by year, county, type of collision, and violation category
- User-friendly filtering options

---

## Packages
```markdown
library(tidyverse)
library(ggplot2)
library(dplyr)
library(readr)
```
## Lessons Learned:
Through this project, I gained experience in:
- Public-health data analysis using real CDC mortality datasets
- Statistical inference applied to real-world epidemiological outcomes
- Data cleaning and transformation for health informatics pipelines
- Designing visualizations to highlight geographic and structural disparities
- Comparing population-level outcomes using hypothesis tests
- Interpreting results in the context of health equity and regional determinants

Overall, the project strengthened my skills in data science for public health, combining statistical analysis, visualization, and domain reasoning to uncover meaningful population-level insights.
