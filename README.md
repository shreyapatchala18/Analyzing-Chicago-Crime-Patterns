# Analyzing Crime Patterns in Chicago

## Project Overview
This project examines crime data from Chicago to uncover patterns and correlations between demographic factors, geographic locations, and crime rates. The analysis focuses on cannabis-related and non-cannabis-related offenses from 2010 to 2012. Insights from this study can guide community planning, policy development, and crime prevention strategies.

---

## Objectives
- Explore the distribution of cannabis and non-cannabis crime rates across Chicago neighborhoods.
- Analyze the relationship between demographic variables (race, income, age) and crime rates.
- Identify temporal trends in crime, including seasonal variations and year-over-year changes.
- Develop predictive models to estimate crime counts for future periods based on historical data.

---

## Dataset Description
The dataset includes census block groups in Chicago, demographic details, and crime data. Key variables are:
- **Demographics**: Population by race (White, Black, Asian), income by gender, and age distributions.
- **Geographic Information**: Latitude, longitude, wards, and community areas.
- **Crime Data**: Cannabis-related and non-cannabis-related crime counts for 2010, 2011, and 2012.

---

## Methodology
1. **Data Cleaning**:
   - Removed sparse NA values and rows with zero population.
   - Calculated crime rates per 100 residents for meaningful comparisons.

2. **Exploratory Data Analysis**:
   - Visualized population and income distributions.
   - Mapped geographic distributions of high/low crime rates.
   - Examined seasonal and annual trends in crime rates.

3. **Statistical Modeling**:
   - Regression analysis to assess relationships between crime rates, demographics, and geographic factors.
   - Poisson regression to predict crime counts for late 2012 using historical data.

4. **Correlation Analysis**:
   - Analyzed the relationship between cannabis and non-cannabis crime rates across neighborhoods.

---

## Key Findings
- **Geographic Distribution**: Crime rates for cannabis and non-cannabis offenses are evenly distributed across Chicago.
- **Correlation**: Strong positive correlation (0.97) between cannabis and non-cannabis crime rates.
- **Demographics**: Higher proportions of White, Black, and Asian populations correlate with lower crime rates.
- **Income**: No significant impact on cannabis or non-cannabis crime rates.
- **Seasonal Trends**: Crime rates peak in summer months (June to August).
- **Predictive Accuracy**: Models successfully forecast crime rates for late 2012 based on prior data.

---

## Limitations
- Potential inaccuracies in crime reporting and demographic data.
- Lack of data on policing strategies and other external factors influencing crime.
- Limited generalizability beyond Chicago or the analyzed time period.

---

## How to Reproduce
1. **Requirements**:
   - Python 3.8+ with libraries: `pandas`, `matplotlib`, `statsmodels`.
   - Crime and demographic data files in CSV format.


