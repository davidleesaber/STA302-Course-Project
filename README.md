# NBA Salary Analysis Using Linear Regression

## Overview
This project investigates factors influencing NBA player salaries, focusing on performance metrics such as points, assists, rebounds, age, and popularity. Using statistical modeling techniques, the analysis identifies which factors most strongly impact player earnings, providing actionable insights for NBA team decision-making.

## Key Features
- **Data Cleaning & Exploration**: Processed and analyzed a dataset of NBA players (2016–2019) from Kaggle, including cleaning missing values, generating summary statistics, and identifying key patterns.  
- **Modeling & Transformation**: Applied linear regression with transformations (Box-Cox, logarithmic, quadratic) to address violations of normality and heteroscedasticity.  
- **Feature Analysis**: Evaluated predictors through ANOVA, t-tests, and confidence intervals to identify significant factors such as assists, rebounds, and player popularity.  
- **Key Insights**: Found that assists, rebounds, and Wikipedia popularity views have the strongest positive influence on salaries. Position-based analysis revealed centers earn the most while point guards earn the least.

## Tools & Techniques
- **Languages**: R (statistical analysis and modeling)  
- **Libraries**: `ggplot2`, `dplyr`, `car`, and other R packages for data visualization and regression diagnostics.  
- **Statistical Methods**: Linear regression, partial F-tests, variance inflation factor (VIF), and diagnostic plotting for model validation.

## Key Findings
- Players’ assists (AST) and total rebounds (TRB) positively influence salaries, with confidence intervals showing strong statistical significance.  
- Popularity (measured via Wikipedia views) also emerged as a significant salary determinant.  
- Despite multicollinearity challenges, interaction terms like age-points and position-popularity highlighted nuanced team decision-making trends.  

## Limitations
- Transformations, while improving model fit, complicated interpretability by altering variable scales.  
- Moderate multicollinearity impacted coefficient reliability, particularly for interaction terms.  
- Outliers such as high-leverage players skewed model predictions slightly.  

## Team Contributions
- **David Lee**: Methods, results analysis, poster design, and final editing.  
- **Youyu Fu**: Code development, results analysis, and conclusions.  
- **Ryan Li**: Introduction, results, and editing.

## Dataset
The dataset is publicly available on Kaggle and includes detailed player statistics from 2016–2019. It is verified with NBA’s official statistics.  

## Poster
The project poster provides a concise overview of the findings and methodology: [View Poster](Upload link here or specify location).  
