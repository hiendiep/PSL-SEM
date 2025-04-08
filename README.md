Introduction
+ This repository contains a Python-based implementation for analyzing the impact of green marketing strategies on green purchase intention (GPI) within Vietnam's cosmetics industry, focusing on Gen Z and Millennial consumers in Ho Chi Minh City. 
+ The code was developed as part of my essay, "Effect of Green Marketing Strategies on Green Purchase Intention for Cosmetic Products of Gen Z and Millennial Consumers in Ho Chi Minh City: Further Explanation by Mediating Factors"
+ The thesis explores how green advertising (GA), eco-labeling (GL), and sustainable packaging (GP) influence GPI, mediated by Green Perceived Value (PV), After-Marketing Environmental Awareness (AW), and After-Marketing Environmental Attitude (AT), using survey data collected in December 2024.

Purpose: The primary objectives of this code are to:
+ Load and preprocess survey data from Excel files, mapping Vietnamese questions to concise variable names.
+ Conduct measurement model assessments (e.g., Factor Loadings, AVE, CR, CA, VIF) to ensure construct validity.
+ Perform discriminant validity checks using Fornell-Larcker and HTMT criteria.
+ Fit an SEM to analyze direct and mediated effects of green marketing strategies on GPI.
+ Compare generational differences in responses between Gen Z and Millennials.

Features
+ Data Loading: Imports survey data from Excel, handling Vietnamese column names with a custom abbreviation mapping.
+ Measurement Model: Computes convergent validity metrics (e.g., Factor Loadings, AVE, CR, CA, VIF) and within-construct correlations.
+ Discriminant Validity: Generates Fornell-Larcker and HTMT matrices to assess construct distinctiveness.
+ SEM Analysis: Fits a full SEM with mediation analysis using semopy, evaluating direct, indirect, and total effects.
+ Output Formatting: Produces structured DataFrames for easy interpretation of results.
+ For detailed methodology and findings, refer to the attached thesis document.

File:
+ Essay pdf file
+ Code and analysis .py file
