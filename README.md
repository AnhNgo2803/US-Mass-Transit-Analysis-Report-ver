# 🚌 U.S. Mass Transit Analysis 🚌

A data analysis project investigating the trends and socio-economic drivers of public transportation ridership in the United States.

### View Project Outputs:

[Insight Dashboard](https://leduyanhngo-dashboard-mass-transit.share.connect.posit.cloud/)

[Detailed Analysis Report](https://leduyanhngo-us-mass-transit-analysis-report.share.connect.posit.cloud/)

# Project Objective
The primary goal of this project is to evaluate the performance of the U.S. mass transit system by identifying key ridership patterns and the major economic and structural factors that influence them. The findings are used to provide policy-oriented recommendations to support recovery and future growth.

# Key Analyses

- Data Preparation: Processed and cleaned a large dataset (136 columns) to retain essential variables for the period from 2005 to 2022.

- Trend Analysis: Visualized and analyzed annual ridership trends for three main transit modes: Route Bus, Urban Rail, and Other Modes.

- Regression Modeling: Applied multiple linear regression models to determine the impact of factors such as:

  - Government Spending

  - Fuel Prices (Diesel & Gasoline)

  - Unemployment Rate

  - Real GDP

- COVID-19 Impact Assessment: Analyzed the structural break in ridership patterns caused by the pandemic.

# Key Findings

| Transit Mode | Key Influencing Factors | Model Fit (Adj. R²) |
|--------------|--------------------------|----------------------|
| **Route Bus** | Gov. Spending (+), Diesel Price (+), Unemployment (–), GDP (–) | 85.3% |
| **Urban Rail** | Gasoline Price (+), Unemployment (+), GDP (+) | 70.8% |
| **Other Modes** | Spending (+), Diesel (–), Gasoline (+), Unemployment (+), GDP (+) | 83.1% |


**Primary Insight:** Real GDP and the unemployment rate are the most consistent drivers across all transit modes. However, each mode exhibits unique sensitivities to different factors; for example, diesel prices are more critical for buses, while gasoline prices significantly impact urban rail.

# Data Source
The dataset for this analysis was sourced from the [U.S. Monthly Transportation Statistics on Kaggle](https://www.google.com/search?q=https://www.kaggle.com/datasets/utkarshx27/monthly-transportation-statistics/data).

## Tools Used

- Language: R

- Libraries: tidyverse, ggplot2, ggcorrplot, knitr, car

- Reporting: Quarto
