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
