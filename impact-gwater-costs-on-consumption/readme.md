# CALBEARS Data Analysis Project

## Overview

This repository contains the analysis and findings from a project conducted for CALBEARS, focusing on understanding the impact of groundwater costs and electricity prices on groundwater consumption. The analysis involves using instrumental variable regression methodologies to estimate causal effects.

## Objective

CALBEARS requested an examination of the relationship between groundwater costs and consumption. The analysis is performed using a two-stage least squares (2SLS) regression methodology.

## Analysis Steps

### Groundwater Costs and Consumption Relationship

1. **Two-Stage Least Squares Regression:**
   - Using the instrumental variable regression method, the relationship between groundwater costs and consumption is examined.
   - Example code:
     ```R
     reg_3 <- ivreg(groundwater_use ~ groundwater_cost | electricity_price_pilot, data = data) 
     summary(reg_3)
     ```
   - The results show a statistically significant relationship between groundwater costs and consumption.

2. **Instrument Variables and Covariances:**
   - Covariances between variables such as groundwater costs, electricity prices, and consumption are calculated.
   - Insights are drawn from covariances, such as the impact of a dollar increase in groundwater costs on consumption.

### Back-Check Analysis

1. **Measurement Error in Outcome:**
   - A scatter plot is created to visualize the relationship between back-checks and farmer-reported groundwater usage.
   - Measurement errors are identified, indicating potential bias in reported groundwater usage.

2. **Regression with Back-Check Data:**
   - A regression analysis is performed using back-check data to estimate the impact of groundwater costs on consumption.
   - The results highlight the discrepancies between reported and actual groundwater usage.

### New Estimates from Alternative Data

1. **Exploration of New Data:**
   - Another dataset (groundwater_use_v2) is examined to determine its suitability for analysis.
   - A scatter plot is created to visualize the relationship between back-checks and new measurements.

2. **Regression with New Data:**
   - Regression analysis is conducted using the new dataset to estimate the impacts of groundwater costs on consumption.
   - The results from the new dataset are compared with earlier estimates.

### Electricity Price Measurement Issues

1. **Utility-Specific Analysis:**
   - Due to data issues in electricity price reporting, separate analyses are performed for different utilities.
   - Utility 1 has non-classical measurement error, while Utility 2 has classical measurement error.

2. **Instrumental Variable Estimation:**
   - Instrumental variable regression is used to estimate the causal effect of electricity prices on groundwater consumption.
   - Utility-specific results are compared.

### Survey Price as an Instrument Variable

1. **Analysis Using Survey Price:**
   - The survey-reported electricity prices (survey_price) are considered as instrument variables.
   - Conditions for the effective use of survey price as an instrument are discussed.

2. **Instrumental Variable Regression:**
   - Instrumental variable regression is performed for each utility using survey price as an instrument.
   - The reliability of the estimates is evaluated based on the nature of measurement errors.

## Conclusion

The analysis provides insights into the relationship between groundwater costs, electricity prices, and consumption. Recommendations and findings from the instrumental variable regression analyses are communicated to CALBEARS.

For detailed code and results, refer to the corresponding sections in the analysis script.

---

## Repository Structure

- `impact-gwater-costs-on-consumption.Rmd`: R script containing the entire analysis process.
- `ps3_data.csv`: Directory containing the datasets used for analysis.

---

## Dependencies

The analysis is performed using R programming language. Ensure that R and required packages are installed to replicate the analysis.

