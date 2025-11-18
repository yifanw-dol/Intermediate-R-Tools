# From Raw Data to Regional Insights: Intermediate R Tools for Workforce & Economic Development

This repository contains all materials (slides, live-coding scripts, exercises, and examples) for the two-day R training.

Dates: Nov 19–20, 2025  
Format: In-person, RStudio Desktop

## Overview

Across eight hands-on sessions, participants build a complete, reproducible R workflow:

- Environment setup (R / RStudio / packages / API keys)
- R basics and working efficiently in RStudio
- Data acquisition from official federal APIs (FRED, ACS/Census, BLS, BEA)
- Data wrangling with dplyr and the tidyverse
- Visualization with ggplot2
- Publication-quality tables with gt
- Spatial analysis for county and state labor indicators
- Microdata analysis for workforce and demographic research

The focus is on reproducible, agency-ready workflows that support state and regional labor market analytics.

## Prerequisites

Participants should have:

- R ≥ 4.3  
- RStudio ≥ 2023.12  
- Ability to install packages from CRAN  

##  API Keys

If you plan to run all live-coding examples, please obtain the following API keys in advance:

- **FRED API Key:**  
  https://fred.stlouisfed.org/docs/api/api_key.html  

- **Census API Key:**  
  https://api.census.gov/data/key_signup.html  

- **BLS API Key:**  
  https://www.bls.gov/developers/  

- **BEA API Key:**  
  https://apps.bea.gov/API/signup/  

API keys can be stored in `.Renviron` or passed directly during the session (as shown in `_setup.Rmd`).

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
