# Suicide Rate Analysis: Relationship with GDP and Age Groups

## Overview

This project investigates patterns in suicide mortality across selected Asian and
European countries, with particular emphasis on economic and demographic factors.

The analysis examines whether GDP per capita is associated with suicide rates and
whether suicide rates differ significantly across age groups.

The project was originally completed as part of the Data Analysis and Statistics
module of my MSc in Data Analytics at the University of Huddersfield.

## Research Questions

1. Is there an association between GDP per capita and suicide rates?
2. Do suicide rates differ significantly across age groups?

## Data

The analysis integrates suicide mortality, demographic, and economic indicators
from publicly available datasets, including:

- World Health Organization (WHO)
- World Bank
- Kaggle

Variables considered include:

- Country
- Year
- Sex
- Age group
- Suicide count
- Population
- Suicide rate per 100,000 population
- GDP per capita
- Continent

The analysis focuses on six selected countries:

**Asia**
- Japan
- Republic of Korea
- Kazakhstan

**Europe**
- Russian Federation
- Ukraine
- Lithuania

## Tools & Technologies

- SAS OnDemand for Academics
- SAS PROC CORR
- SAS PROC GLM
- Microsoft Excel
- Python (data preprocessing support)

## Statistical Methods

### Exploratory Data Analysis

Scatterplots and boxplots were used to investigate distributions, temporal
patterns, relationships, and potential outliers.

### Pearson Correlation

Pearson correlation analysis was used to investigate linear relationships between
economic/time variables and suicide rates.

### Linear Regression

Linear regression was used to examine the association between GDP per capita and
suicide rates.

Model performance was evaluated using:

- R-squared
- Adjusted R-squared
- Root Mean Squared Error (RMSE)
- Regression coefficients
- Statistical significance

### Analysis of Variance (ANOVA)

One-way ANOVA was used to investigate whether mean suicide rates differed across
age groups.

### Tukey Post-hoc Analysis

Following ANOVA, Tukey-adjusted pairwise comparisons were performed to investigate
differences between individual age categories.

## Key Findings

The regression analysis identified a statistically significant but weak inverse
association between GDP per capita and suicide rate. The low R-squared value
indicated that GDP per capita alone explained only a small proportion of the
variation in suicide rates.

ANOVA identified statistically significant differences in suicide rates across
age groups. Tukey-adjusted post-hoc comparisons were subsequently used to
investigate differences between individual age categories.

These results demonstrate that suicide mortality is unlikely to be explained by
economic indicators alone and highlight the importance of demographic factors
when analysing population-level suicide patterns.

## Limitations

This is an observational ecological analysis and the identified associations
should not be interpreted as causal relationships.

The analysis also contains limitations related to missing data, country selection,
temporal differences, and potential confounding variables.

## Repository Structure

- `data/` - Dataset used for the analysis
- `sas/` - SAS programs for preprocessing and statistical analysis
- `figures/` - Selected analytical visualisations
- `report/` - Full academic report

## Author

**Sanchayan Vivekananthan**

MSc Data Analytics (Distinction)  
University of Huddersfield
