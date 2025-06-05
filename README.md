# Health Insurance Cost Analysis

# Project Overview

This project explores how personal characteristics and regional factors affect healthcare insurance charges. Using a dataset of insurance policyholders, I investigate patterns in cost distribution that can then be used to build predictive models to estimate healthcare expenses in the future.

The aim is to identify which features most strongly influence insurance charges based on user attributes and demographics.

# Hypothesis

Individuals who smoke, have a higher BMI, or are older will incur significantly higher insurance charges. Additionally, geographic region may contribute to variations in cost due to external factors such as cost of living, differing healthcare practices, or wider economic conditions.

# The Dataset

The dataset has been provided by Kaggle and includes the following columns:
- Age: Age of primary beneficiary 
- Sex: Gender (encoded)
- BMI: Body Mass Index
- Children: Number of dependents covered by insurance
- Smoker: Smoking Status
- Region: Residential area in the US (northeast, southeast, southwest, northwest).
- Charges: Individual medical costs billed by health insurance

# Ethics

The dataset used did not contain any personal or identifiable information in the set.

# Objectives

Understand how personal and regional factors correlate with insurance charges
Visualize relationships using scatter plots and correlation analysis
Evaluate model performance and feature importance

# Methods & Tools

- Python, 
- pandas Library, 
- NumPy 
- Matplotlib 
- Seaborn for visualisations
- Jupyter Notebook for analysis and documentation

# Key Insights from Data Analysis 

Smoking has the greatest impact on high costs of healthcare insurance. If all other variables are consistent, the cost for smokers compared to non-smokers is nearly three times as much.

High BMI and age also contribute to higher prices.
Regionally, Northwest and Southwest insurance costs are lower, with the Southeast being the most expensive of all four regions analysed.

The number of children does not appear to significantly affect charges.
There is a positive correlation between age and charges, particularly among smokers.
Males and females do not show large cost differences when other variables are held constant.

# Further Investigation

Based on this analysis, linear regression is a helpful method for understanding how factors like smoking, BMI, age, and region influence healthcare insurance costs.
In the future, more advanced techniques—such as improved regression models or decision trees—could be explored to increase prediction accuracy and better identify which factors have the biggest impact.

# References

Resources used include:

Code Institute LMS https://learn.codeinstitute.net/ci_program/daai_5

ChatGPT https://chatgpt.com/

Data to Viz https://www.data-to-viz.com/

# Acknowledgements

Thanks to John Readon and Vasi Pavaloi for support on a number of IT issues.

