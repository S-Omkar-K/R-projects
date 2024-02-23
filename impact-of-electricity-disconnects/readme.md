# Electricity Disconnection Impact Study

This GitHub repository contains the code and documentation for a study on the impact of electricity disconnection programs on payment behavior. The study employs statistical methods and the potential outcomes framework to estimate treatment effects.

# Objective
The main objective is to investigate the payment impacts of electricity disconnection programs. The analysis focuses on measuring the impact of treatment, defined as disconnecting a household's electricity, on household payments in rupees.

#Contents

R Markdown Script:
The core analysis is implemented in an R Markdown script (impact-of-electricity-disconnects.Rmd).
The script covers the potential outcomes framework, challenges in estimating treatment effects, balance tests, regression analysis, and the exploration of different variables.

Data:
The repository includes a CSV file (ps1_data_22.csv) containing the dataset used for the analysis.


# Usage:
Download and run the impact-of-electricity-disconnects.Rmd script using an R environment.

# Findings
The study explores the challenges in estimating treatment effects due to unobservable outcomes and discusses the use of average treatment effects (ATE) and average treatment effects on the treated (ATT).

Balance tests are conducted to ensure the randomization of treatment and control groups.

Regression analysis is performed to estimate treatment effects, considering various covariates.

The document highlights the importance of understanding the difference between Intent to Treat (ITT) estimates and actual treatment effects.


# Issues and Contributions
Feel free to open issues for any questions, suggestions, or improvements. Contributions are welcome through pull requests.
