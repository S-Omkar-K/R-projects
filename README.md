# R-projects
Statistics, Program Evaluation and Research methodology using R

-------

## CALBEARS - Determining Effect of Average Groundwater costs on Consumption
### Overview
This repository contains the analysis and findings from a project conducted for CALBEARS, focusing on understanding the impact of groundwater costs and electricity prices on groundwater consumption. The analysis involves using instrumental variable regression methodologies to estimate causal effects.
### Approach
The analysis is performed using a two-stage least squares (2SLS) regression methodology.
### Project repo: [impact-gwater-costs-on-consumption](/impact-gwater-costs-on-consumption/)

------

## Electricity Disconnection Impact Study
This repository contains the code and documentation for a study on the impact of electricity disconnection programs on payment behavior. The study employs statistical methods and the potential outcomes framework to estimate treatment effects.
### Overview
The main objective is to investigate the payment impacts of electricity disconnection programs. The analysis focuses on measuring the impact of treatment, defined as disconnecting a household's electricity, on household payments in rupees.
### Approach
The study explores the challenges in estimating treatment effects due to unobservable outcomes and discusses the use of average treatment effects (ATE) and average treatment effects on the treated (ATT).
Balance tests are conducted to ensure the randomization of treatment and control groups.
Regression analysis is performed to estimate treatment effects, considering various covariates.
It also highlights the importance of understanding the difference between Intent to Treat (ITT) estimates and actual treatment effects.
### Project repo: [impact-of-electricity-disconnects](/impact-of-electricity-disconnects/)

------

## FIONA Impact Analysis Study
This project involves the impact analysis of the FIONA program on farmer profits in India. The analysis includes the assessment of assumptions, different statistical approaches, and recommendations based on the findings.
### Assumptions, Approach and Analysis
##### Common Support
The common support assumption is validated across covariates, including crop, district, and isyoung. The analysis demonstrates that the assumption holds for these variables.
##### Conditional Independence
The conditional independence assumption, crucial for causal inference, cannot be directly validated due to the nature of potential outcomes. However, the analysis proceeds with SOO approaches, acknowledging this limitation.
### Statistical Approaches
##### Regression Adjustment 
The regression model includes relevant covariates such as crop variety, district, and farmer age. The results indicate that the ATE of FIONA on farmer profits is statistically significant.
#### Matching
The exact matching approach is employed with covariates iswheat, isrice, and islentils. The matched data are then used to estimate both ATE and Average Treatment on the Treated (ATT). The results are consistent with the regression-based approach.
### Project repo: [insurance-effects-on-farmer-profits](/insurance-effects-on-farmer-profits/)

------

## Effect of air quality regulations on particulate matter levels in Muncipalities
### Overview
This project focuses on analyzing the impact of air quality regulations on particulate matter (PM 2.5) levels in municipalities. The analysis employs regression analysis, difference-in-differences (DiD) estimation, and event study methodologies to understand the causal effects of introducing air quality regulations over time.
### Objective
The primary objective of this project is to assess the effectiveness of air quality regulations in reducing local particulate matter. Specific goals include:
- Estimating the difference in means between municipalities with and without air quality regulations.
- Implementing DiD analysis to identify the Average Treatment Effect (ATE) for municipalities introducing regulations in specific years.
- Conducting panel fixed effects regression to examine the causal impact of air quality regulations on particulate matter over time.
### Findings, Interpretations and Recommendations
- The analysis reveals a significant reduction in particulate matter after the introduction of air quality regulations, as observed through various methodologies.
- The effectiveness of regulations varies across different years, with a notable impact persisting over time in certain cases.
- Identified shortcomings and potential biases in the analysis are discussed, emphasizing the need for careful interpretation.
- Strong promotion and enforcement of air quality regulations.
### Project repo: [effects-airquality-regulations-on-PM](/effects-airquality-regulations-on-PM/)
