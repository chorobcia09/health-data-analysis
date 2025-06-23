# Health Data Analysis

## Project Description

This project involves analyzing health-related data using the R programming language. The main goals include:

- Importing and exploring the dataset `health.csv`
- Creating histograms for selected variables
- Performing correlation analysis
- Building simple and multiple linear regression models

---

## How to Run the Project

1. Just open `analysis_eng.html` or `analysis_pl.html`.

## Results

The generated HTML report includes:

Histograms

Distribution plots of key variables such as:

- Systolic blood pressure
- Body Mass Index (BMI)
- Age
- Weight
- Waist circumference
- Diabetes status
- Smoking habits
- Fast food consumption

Correlation Matrix

- A numerical and visual representation of correlations between variables, created using corrplot.

Regression Models

Two models were built:

1. Simple Linear Regression:

- systolic ~ age

This model estimates how age affects systolic blood pressure.

2. Multiple Linear Regression:

- systolic ~ age + bmi + waist

This extended model improves prediction by including more explanatory variables.
