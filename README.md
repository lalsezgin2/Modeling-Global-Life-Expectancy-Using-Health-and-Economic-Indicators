# Modeling-Global-Life-Expectancy-Using-Health-and-Economic-Indicators
Overview

This project analyzes the key predictors of life expectancy across countries between 2010 and 2015 using data from the World Health Organization (WHO) and the United Nations. While global life expectancy has increased overall, improvements have not been equal across countries. This analysis explores which economic, educational, and health-related factors are most strongly associated with life expectancy and how these relationships differ between developed and developing countries.

Research Question:

What are the key predictors of life expectancy across countries between 2010 and 2015?

Data:

Sources:

  1. World Health Organization (Global Health Observatory)
  
  2. United Nations economic data

Coverage:

  - 193 countries (filtered to 2010–2015)

  - 22 variables

  - 2,938 observations before cleaning

The dataset includes indicators related to health, education, income, and government spending.

Key Variables:

  - Life.expectancy (response variable): Average years a newborn is expected to live
  
  - Schooling: Average years of education
  
  - Income.composition.of.resources: Access to income and basic needs
  
  - percentage.expenditure: Share of GDP spent on healthcare
  
  - Alcohol: Per capita alcohol consumption
  
  - BMI: Average body mass index
  
  - Status: Developed vs. developing country classification

Methods:

The analysis was conducted in R using:

  - Exploratory data analysis and visualization
  
  - Correlation analysis to assess multicollinearity
  
  - Multiple linear regression
  
  - Stepwise regression using AIC
  
  - Lasso regression for variable selection

Packages used include tidyverse, dplyr, ggplot2, bestglm, reshape2, and glmnet.

Key Findings:

  - Education and income composition are the strongest predictors of life expectancy.
  
  - BMI and healthcare expenditure show positive but weaker associations.
  
  - Development status shows large raw differences in life expectancy but becomes less significant once economic and health variables are included.
  
  - Results are consistent across multiple modeling approaches, strengthening the reliability of the findings.

Limitations:

  - Missing data led to the exclusion of some countries, potentially introducing selection bias.
  
  - The analysis is cross-sectional, so results reflect associations rather than causation.
  
  - Some variables may capture multiple underlying effects (e.g., BMI).

Authors:

  - Oghap Kim
  
  - Lal Sezgin

Tools:

  - R (data cleaning, visualization, modeling)
