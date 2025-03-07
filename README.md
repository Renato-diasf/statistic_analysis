# PNAD 2015 Data Analysis: A Statistical Exploration

## Overview
This project is a comprehensive statistical analysis of the 2015 National Household Sample Survey (PNAD) data from Brazil. The goal is to explore and understand various socio-economic variables such as income, education, age, height, and regional distribution. The analysis includes data cleaning, frequency distributions, measures of central tendency, dispersion, and visualizations using Python libraries like Pandas, NumPy, and Seaborn.

## Dataset
The dataset used in this project is sourced from the Brazilian Institute of Geography and Statistics (IBGE). It includes variables such as:
- **Income**: Monthly income from the main job for individuals aged 10 or older.
- **Age**: Age of the resident in years.
- **Height**: Height of the resident in meters.
- **State (UF)**: Brazilian state codes.
- **Gender**: Binary classification (Male/Female).
- **Years of Education**: Categorized into levels.
- **Race/Color**: Self-declared race/color categories.

The dataset was preprocessed to remove invalid or missing income records and focus on household reference persons.

## Project Structure
The analysis is divided into the following sections:

1. **Data Exploration**:
   - Understanding the dataset structure.
   - Identifying variable types (qualitative, quantitative, ordinal, nominal).

2. **Frequency Distributions**:
   - Frequency tables for qualitative variables (e.g., gender, race).
   - Custom and fixed-width frequency distributions for quantitative variables (e.g., income, age).

3. **Measures of Central Tendency**:
   - Mean, median, and mode for variables like income, age, and height.
   - Comparative analysis of central tendencies across different groups.

4. **Measures of Dispersion**:
   - Calculation of variance and standard deviation.
   - Analysis of income and education variability.

5. **Data Visualization**:
   - Histograms and box plots for variables like income, height, and years of education.
   - Comparative visualizations by gender and state.

## Tools and Libraries
- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Seaborn**: Data visualization.
- **Matplotlib**: Additional plotting capabilities.

## Key Insights
- The income distribution is highly skewed, with most individuals earning below R$ 2,000 per month.
- The average years of education is approximately 9.47, with significant variability across states.
- Height and age distributions follow expected patterns, with slight variations by gender.
