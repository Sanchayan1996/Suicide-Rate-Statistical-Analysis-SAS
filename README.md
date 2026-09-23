# Suicide Rate Analysis: Relationship with GDP and Age Groups

## Overview

This project investigates patterns in suicide mortality across selected Asian and European countries, with particular emphasis on economic and demographic factors.

The analysis examines whether GDP per capita is associated with suicide rates and whether suicide rates differ significantly across age groups.

The project was originally completed as part of the **Data Analysis and Statistics** module of my **MSc in Data Analytics at the University of Huddersfield**.

## Research Questions

1. Is there an association between GDP per capita and suicide rates?
2. Do suicide rates differ significantly across age groups?

## Dataset

The analysis combines publicly available suicide, demographic and economic data obtained from sources including:

- World Health Organization (WHO)
- World Bank
- Kaggle

The dataset contains information on:

- Country
- Year
- Sex
- Age group
- Number of suicides
- Population
- Suicide rate per 100,000 population
- GDP per capita
- GDP for year
- Geographic region

The analysis focused on six countries with historically high suicide rates:

**Asia**
- Japan
- Republic of Korea
- Kazakhstan

**Europe**
- Lithuania
- Russian Federation
- Ukraine

## Data Preparation

Data preprocessing and preparation were performed using **SAS OnDemand for Academics, Python and Microsoft Excel**.

The preparation process included:

- Combining data from multiple sources
- Selecting countries relevant to the study
- Reviewing missing observations
- Removing variables with substantial missing information
- Creating geographic classifications
- Preparing variables for statistical analysis

## Statistical Analysis

The project applied several statistical techniques to investigate the research questions.

### GDP and Suicide Rates

The relationship between economic conditions and suicide rates was investigated using:

- Exploratory data analysis
- Scatter plots
- Pearson correlation analysis
- Linear regression
- Box plots and outlier investigation

### Age Groups and Suicide Rates

Differences in suicide rates between age categories were investigated using:

- One-way Analysis of Variance (ANOVA)
- Tukey-adjusted post-hoc comparisons
- Least Squares Means (LSMEANS)
- Box plots and comparative visualisations

## Key Findings

### GDP per Capita

The linear regression analysis identified a statistically significant negative association between GDP per capita and suicide rates.

However, the model produced an **R² of approximately 0.016**, indicating that GDP per capita alone explained only a small proportion of the variation in suicide rates.

This suggests that suicide mortality is influenced by factors beyond economic conditions alone.

### Age Groups

ANOVA identified statistically significant differences in suicide rates across age categories (**p < 0.0001**).

The ANOVA model explained approximately 28.15% of the variation in suicide rates, indicating meaningful differences across the analysed age categories.

Tukey-adjusted post-hoc comparisons were subsequently used to investigate differences between individual age groups.

## Tools & Technologies

- **SAS OnDemand for Academics** – statistical analysis
- **Python** – data preprocessing
- **Microsoft Excel** – data preparation and inspection
- **Statistical Methods** – Pearson Correlation, Linear Regression, ANOVA, Tukey Post-hoc Analysis
- **Data Visualisation** – Scatter Plots, Box Plots and Comparative Charts

## Limitations

This analysis should be interpreted as an exploratory statistical study rather than evidence of a causal relationship between GDP and suicide mortality.

The analysis is subject to limitations including differences in data availability across countries and years, missing observations, country selection and the influence of socioeconomic, demographic and other factors not included in the statistical models.

## Academic Context

This project was completed as individual coursework for the **CMI3508-2324 Data Analysis and Statistics** module during my MSc in Data Analytics at the University of Huddersfield.

The repository has been organised retrospectively to present the original analysis, dataset and report as part of my academic data science portfolio.

## Author

**Sanchayan Vivekananthan**  
MSc Data Analytics – University of Huddersfield
