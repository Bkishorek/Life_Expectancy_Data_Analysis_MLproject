Life Expectancy Analysis & Prediction

Project Overview

This project analyzes global life expectancy data to understand the relationship between **health, education, mortality, and socioeconomic factors** and life expectancy across countries.

The project follows a complete data analytics and machine learning workflow:

**Raw Data → Excel Data Cleaning → Excel Dashboard → Python EDA → Statistical Analysis → Machine Learning → Model Evaluation**

The cleaned dataset contains **2,938 country-year records and 22 variables** covering the period from **2000 to 2015**.


Objectives

- Clean and prepare the raw life expectancy dataset using Microsoft Excel.
- Develop an interactive Excel dashboard to analyze life expectancy trends.
- Explore relationships between life expectancy and health, education, and socioeconomic indicators.
- Perform correlation analysis to identify important predictors of life expectancy.
- Perform statistical modelling using Ordinary Least Squares (OLS) regression.
- Develop a Multiple Linear Regression model using Python.
- Evaluate model performance using R², MAE, and RMSE.
- Use the trained model to predict life expectancy for new input values.

Dataset

The dataset contains country-level health and socioeconomic information from **2000–2015**.

Major Variables
- Country
- Year
- Status
- Life Expectancy
- Adult Mortality
- Infant Deaths
- Alcohol Consumption
- Percentage Expenditure
- Hepatitis B
- Measles
- BMI
- Under-Five Deaths
- Polio
- Total Expenditure
- Diphtheria
- HIV/AIDS
- GDP
- Population
- Thinness 1–19 Years
- Thinness 5–9 Years
- Income Composition of Resources
- Schooling


Dataset Summary

- **2,938 records**
- **22 variables**
- Multiple countries
- Years: **2000–2015**
- Developed and Developing country classifications

  Key Insights

- Analyzed global life expectancy data from **2000–2015**, with an overall average life expectancy of **69.22 years**, and observed a clear upward trend in average life expectancy over the study period.
- **Schooling showed the strongest positive correlation with life expectancy (0.72)**, while **Adult Mortality showed a strong negative correlation (-0.70)**, highlighting the importance of education and mortality-related factors in population health.
- **Income Composition (0.69)** and **BMI (0.56)** showed positive associations with life expectancy, while **HIV/AIDS (-0.56)** showed a substantial negative relationship; GDP also showed a moderate positive correlation (**0.43**).
- Developed countries generally showed higher life expectancy than developing countries, and the selected.
- **Multiple Linear Regression model explained 77.3% of the variation in life expectancy (R² = 0.773)** with an average prediction error of **3.21 years (MAE)**.


Project Workflow

Raw Life Expectancy Dataset
            ↓
Data Cleaning in Microsoft Excel
            ↓
Cleaned Dataset
            ↓
Interactive Excel Dashboard
            ↓
Python Data Import
            ↓
Exploratory Data Analysis
            ↓
Correlation Analysis
            ↓
OLS Statistical Modelling
            ↓
Feature Selection
            ↓
Multiple Linear Regression
            ↓
Model Evaluation
            ↓
Life Expectancy Prediction

Tools used

MS EXCEL
Data cleaning and processing
Visualization and dashboard

python
-pandas
-Numpy
-Matplotlip
-scikit-learn



