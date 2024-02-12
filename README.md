# Enrollment Data Analysis for Secondary and Primary Schools: Impact of SGR using difference-in-difference estimation model

# Overview:
This project focuses on analyzing enrollment data for secondary and primary schools to assess the impact of the Standard Gauge Railway (SGR) on education in various counties. The primary objective is to determine whether the implementation of the SGR has had any significant effects on school enrollment in both secondary and primary education sectors.

# Project Structure:
The project consists of the following key components:

**Data Collection**: Enrollment data for secondary and primary schools across different counties is collected and organized into a structured format for analysis.

**Data Preprocessing**: The collected data is cleaned, processed, and prepared for analysis. This includes handling missing values, formatting dates, and creating relevant features.

**Analysis**: Statistical analysis techniques are applied to the data to assess the impact of SGR on school enrollment. Regression analysis, including Difference-in-Differences (DID) estimation, is used to quantify the relationship between SGR implementation and enrollment figures.

**Visualization**: Graphical visualizations, such as line plots and regression plots, are generated to present the findings of the analysis in an interpretable format.

**Reporting**: A comprehensive report summarizing the analysis results, including key findings, statistical metrics, and visualizations, is compiled to provide insights into the impact of SGR on school enrollment.


Data Collection: Enrollment data for secondary and primary schools across different counties is collected and organized into a structured format for analysis.

Data Preprocessing: The collected data is cleaned, processed, and prepared for analysis. This includes handling missing values, formatting dates, and creating relevant features.

Analysis: Statistical analysis techniques are applied to the data to assess the impact of SGR on school enrollment. Regression analysis, including Difference-in-Differences (DID) estimation, is used to quantify the relationship between SGR implementation and enrollment figures.

Visualization: Graphical visualizations, such as line plots and regression plots, are generated to present the findings of the analysis in an interpretable format.

Reporting: A comprehensive report summarizing the analysis results, including key findings, statistical metrics, and visualizations, is compiled to provide insights into the impact of SGR on school enrollment.

# The project consists of the following key components:
**enrollment_data.csv**: CSV file containing enrollment data for secondary and primary schools, organized by county and year.
**enrollment_analysis.ipynb**: Jupyter Notebook containing the Python code for data analysis, preprocessing, modeling, and visualization.
**README.md**: This readme file providing an overview of the project, its objectives, and file structure.

# Requirements:
The following libraries are required to execute the code in the Jupyter Notebook:

pandas
numpy
statsmodels
scipy
matplotlib
seaborn

# Instructions:
1.Clone the repository to your local machine.
2.Ensure that Python and Jupyter Notebook are installed on your system.
3.Install the required Python libraries using pip or conda: pip install pandas numpy statsmodels scipy matplotlib seaborn.
4.Open the enrollment_analysis.ipynb notebook using Jupyter Notebook.
5.Run each cell in the notebook sequentially to execute the code and generate analysis results.
6.Review the generated visualizations and analysis findings.
7.Modify the notebook as needed for further analysis or customization.
8.Refer to the report for a detailed summary of the analysis results and insights.


Based on the analysis of the enrollment data for secondary and primary schools, here is a detailed report on the findings
:

### Regression Analysis for Secondary Schools:

1. **R-squared and Adjusted R-squared:**
   - The R-squared value of 0.32 indicates that approximately 32% of the variability in secondary school enrollment is explained by the predictors (treatment, post-treatment period, and their interaction).
   - However, the adjusted R-squared value of -0.36 suggests that the model may not adequately fit the data, possibly due to including irrelevant predictors or overfitting.

2. **Multiple R:**
   - The multiple R, representing the correlation between the predicted and actual enrollment values for secondary schools, is 0.57, signifying a moderate positive correlation.

3. **Intercept Coefficient:**
   - The intercept coefficient is nearly zero (-2.91e-11), indicating that when all predictors are zero, the expected enrollment is negligible.
   - Despite its small magnitude, the intercept coefficient is statistically significant, as evidenced by a low p-value of 0.00033.

4. **T-Statistic:**
   - The t-statistic for the intercept coefficient is 3.99, indicating its statistical significance at the 5% level.
   - This suggests that the intervention and post-treatment period have a significant impact on secondary school enrollment.

5. **Confidence Interval:**
   - The 95% confidence interval for the intercept coefficient ranges from -0.49 to 0.49, providing a range of plausible values for the intercept.

### Regression Analysis for Primary Schools:

1. **R-squared and Adjusted R-squared:**
   - The R-squared value of 0.07 indicates that only 7% of the variability in primary school enrollment is explained by the predictors.
   - The adjusted R-squared value of -0.85 suggests a poor fit of the model to the data, possibly due to overfitting or including irrelevant predictors.

2. **Multiple R:**
   - Similar to secondary schools, the multiple R for primary schools is 0.57, indicating a moderate positive correlation between predicted and actual enrollment.

3. **Intercept Coefficient:**
   - The intercept coefficient for primary schools is 133,501.79, indicating the expected enrollment when all predictors are zero.
   - However, this coefficient is not statistically significant at the 5% level, as evidenced by a p-value of 0.118.

4. **T-Statistic:**
   - The t-statistic for the intercept coefficient is 1.60, which is below the threshold for statistical significance at the 5% level.
   - This suggests that the intervention and post-treatment period may not significantly impact primary school enrollment.

5. **Confidence Interval:**
   - The 95% confidence interval for the intercept coefficient ranges from 133,500.08 to 133,503.50, providing a range of plausible values.

### Conclusion:

- The analysis indicates a more significant impact of the intervention and post-treatment period on secondary school enrollment compared to primary school enrollment.
- Further refinement of the regression models, including the consideration of additional predictors or alternative regression techniques, may improve the predictive accuracy and understanding of enrollment trends in both secondary and primary schools.
- Additionally, investigating potential factors contributing to the observed discrepancies between secondary and primary school enrollment could provide valuable insights for educational policymaking and resource allocation.

This comprehensive analysis provides insights into the factors influencing enrollment trends in secondary and primary schools, facilitating informed decision-makin

g in educational planning and policy formulation.
