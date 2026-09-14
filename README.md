# Household Macroeconomic Indicator Analysis - OECD Countries

## 📊 [View the full analysis report](https://evanbok.github.io/Household-Macroeconomic-Indicator-Analysis---OECS-Countries/hh_budget_git.html)

This project uses R for data visualization and econometric modeling to analyze how household economic well-being—measured through debt, disposable income, wealth, expenditure, savings, and unemployment—drives and responds to macroeconomic shifts across four OECD countries (Australia, Canada, Japan, USA) from 1995-2016.

## Research Questions & Findings

**1. Did the 2008 financial crisis structurally change the relationship between household debt and savings behavior?**
Yes — the negative pre-2008 debt-savings relationship weakened significantly after 2008 (interaction p<0.001), with the effect most visible in Australia, Canada, and the USA.

**2. Is there a lagged relationship between household debt and unemployment?**
No significant relationship was found in either direction — rising debt did not predict future unemployment, nor did unemployment predict future debt, in this sample.

**3. Does household wealth explain differences in how closely spending tracks income across countries?**
Partially, but in the opposite direction hypothesized — higher-wealth countries showed a *stronger* (not weaker) link between income and spending (interaction p<0.01), contrary to a simple "wealth smooths spending" theory.

## Methods
Built in R using the tidyverse (dplyr, ggplot2, tidyr) and base R linear regression, including interaction models to test whether relationships between variables changed over time or varied by wealth level.

## Reproducing this analysis
The full [R Markdown source](hh_budget_git.Rmd) and [dataset](hh_budget.csv) are included in this repo — knit the `.Rmd` file in RStudio to regenerate the report.
