# Health Insurance Cost Analysis

# Project Overview

This project explores how personal characteristics and regional factors affect healthcare insurance charges. Using a dataset of insurance policyholders, we investigate patterns in cost distribution that can then be used to build predictive models to estimate healthcare expenses in the future.
The aim is to identify which features most strongly influence insurance charges based on user attributes and demographics.

# Hypothesis

Individuals who smoke, have a higher BMI, or are older will incur significantly higher insurance charges. Additionally, geographic region may contribute to variations in cost due to external factors such as cost of living, differing healthcare practices, or economic conditions.

# The Dataset

The dataset has been provided by Kaggle and includes the following columns:
age: Age of primary beneficiary
sex: Gender (encoded)
bmi: Body Mass Index
children: Number of dependents covered by insurance
smoker: Smoking status
region: Residential area in the US (northeast, southeast, southwest, northwest)
charges: Individual medical costs billed by health insurance

# Ethics

The dataset used did not contain any personal or identifiable information in the set.
Objectives

Understand how personal and regional factors correlate with insurance charges
Visualize relationships using scatter plots and correlation analysis
Evaluate model performance and feature importance
Methods & Tools

Python, pandas, NumPy for data processing
Matplotlib & Seaborn for visualisations
Jupyter Notebook for analysis and documentation

# Key Insights

Smoking has the greatest impact on high costs of healthcare insurance. If all other variables are consistent, the cost for smokers compared to non-smokers is nearly three times as much.
High BMI and age also contribute to higher prices.
Regionally, Northwest and Southwest insurance costs are lower, with the Southeast being the most expensive of all four regions analysed.
The number of children does not appear to significantly affect charges.
There is a positive correlation between age and charges, particularly among smokers.
Males and females do not show large cost differences when other variables are held constant.

# Further Investigation

Linear regression can be used moving forward to better predict the degree to which smoking, BMI, age, and region will affect healthcare insurance costs.
Additional exploration using regularized models (e.g., Lasso, Ridge) or tree-based models (e.g., Decision Trees, Random Forests) could improve predictive performance and help with feature selection.

# References

Resources used include:

Code Institute LMS https://learn.codeinstitute.net/ci_program/daai_5

ChatGPT https://chatgpt.com/

Data to Viz https://www.data-to-viz.com/

# Acknowledgements

Thanks to John Readon for support on a number of IT issues.
