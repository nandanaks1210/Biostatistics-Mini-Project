# Analysis of Heart Disease Risk Based on Chest Pain Types and Maximum Heart Rate

### Project Overview

This project explores the relationship between chest pain types, maximum heart rate (MaxHR), and the presence of heart disease. By leveraging statistical tests, we aim to uncover patterns and associations that can aid in understanding heart disease risks based on patient characteristics.

### Objectives

To examine the association between chest pain type and heart disease.

To analyze variations in MaxHR across different chest pain types.

### Methodology

Data Overview: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

### Statistical Tests:

Chi-Square Test of Independence: To evaluate the association between chest pain type and heart disease.

Kruskal-Wallis Test: To assess differences in MaxHR across chest pain types, followed by post-hoc analysis for pairwise comparisons.

Visualization: Boxplots were used to illustrate the distribution of MaxHR across chest pain types.

### Key Results

The Chi-square test revealed a significant association between chest pain type and heart disease (X² = 268.07, p < 2.2e-16), suggesting that specific chest pain types are more strongly associated with the presence of heart disease.

The Kruskal-Wallis test identified significant differences in MaxHR across chest pain types (chi-squared = 126.25, p < 2.2e-16), with pairwise post-hoc comparisons highlighting differences between certain groups.

### Conclusion

The findings demonstrate that both chest pain type and MaxHR are valuable indicators for understanding heart disease risk. This analysis contributes to the broader effort of identifying key factors that can assist in heart disease diagnosis and prevention.

### How to Use
Refer to the heart_disease_analysis.R script for statistical analysis.
Refer to the project report to know more.
