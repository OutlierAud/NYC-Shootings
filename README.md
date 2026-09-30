# The Geography Of Gun Violence In New York City

### A 19-Year Spatial Analysis of Shooting Incidents in NYC

This project examines the geographic distribution of recorded shooting incidents in New York City from **2006 to 2024** using data from the **NYPD Shooting Incident Dataset**.

The analysis looks at where shooting incidents occurred across:

- NYC boroughs
- Police precincts
- Latitude and longitude coordinates

The goal is to describe spatial patterns and identify areas with higher concentrations of recorded incidents, without making assumptions about the causes of those patterns.

## Research Question

**How does the frequency of shooting incidents in New York City vary across the city?**

## Analysis

The project includes:

- Data cleaning and validation
- Summary statistics
- Shooting incidents by borough
- Shooting incidents by precinct
- Analysis of the highest-count precincts
- Geographic heatmap of shooting incidents
- Analysis of annual trends from 2006–2024
- A descriptive linear model of the annual trend
- Discussion of potential sources of bias and limitations

The analysis uses **raw incident counts** rather than population-adjusted rates, so results should not be interpreted as measures of risk or crime rates. The report also discusses geographic aggregation and data collection limitations. 

## Key Findings

The analysis found an overall downward trend in recorded shooting incidents over the 19-year study period, with a notable increase in several precincts during 2020 before the downward trend resumed. 

The spatial analysis also shows that areas with high overall incident counts are not necessarily geographically uniform. The heatmap provides additional context by showing where incidents are concentrated within and across precincts. 

## Tools

- R
- tidyverse
- ggplot2
- sf
- tigris
- lubridate

## Files

`NYPD_NYC_shootings.Rmd` — R Markdown source file containing the complete analysis and code.

`NYPD_NYC_shootings_assignment.html` — knitted HTML version of the analysis.

## Data Source

**NYPD Shooting Incident Dataset (Historic)**  
New York City Open Data

The dataset contains information about shooting incidents including date, borough, precinct, and geographic coordinates.

## Limitations

This analysis uses recorded shooting incidents and raw counts. It does not account for differences in population or geographic area between locations.

The dataset also reflects incidents reported to and recorded by the NYPD, so unreported incidents and potential differences in data collection or recording may affect the results. 

The analysis is descriptive and does not attempt to identify causal explanations for changes in shooting incidents over time.
