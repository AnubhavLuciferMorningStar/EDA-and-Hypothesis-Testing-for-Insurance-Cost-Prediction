# EDA-and-Hypothesis-Testing-for-Insurance-Cost-Prediction

For the Insurance Cost Prediction project, EDA will involve visualizing distributions, identifying outliers, and exploring correlations between different variables like age, diabetes status, weight, and premium costs. This analysis aims to unearth significant predictors of insurance costs and understand the demographic and health-related characteristics that most influence premium pricing.

Hypothesis testing will be used to formally test assumptions such as:

      * Are premium costs significantly higher for smokers compared to non-smokers?
      * Does the presence of chronic diseases lead to higher insurance premiums?
      * Is there a significant difference in premium costs based on the number of major surgeries a person has had?

These statistical tests will help validate whether the observed patterns in the data are statistically significant or occur by chance, thereby reinforcing the robustness of subsequent predictive modeling.

# Ideas for EDA and Hypothesis Testing
1. Distribution Analysis:
    * Plot any and all visualization that could not be made in tableau.
2. Correlation Analysis:
    * Generate a correlation matrix or heatmap to visualize the relationships between all numerical variables.
    * Focus on the correlation between premium prices and potential predictors to identify strong associations.
3. Outlier Detection:
    * Identify outliers in key variables using IQR (Interquartile Range) method or Z-scores.
    * Assess the impact of outliers on the overall distribution and consider strategies for handling them.
4. Hypothesis Testing:
    * T-tests/ANOVA: Use these tests to compare the means of premium prices across different groups defined by categorical variables (e.g., smokers vs. non-smokers, number of surgeries).
    * Chi-square tests: Evaluate the association between two categorical variables (e.g., presence of chronic disease and history of cancer in family).
    * Regression Analysis: Apply linear regression to test hypotheses about the impact of various predictors on premium prices.
