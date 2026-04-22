# Fiscal Revenue, Trade Openness, and GDP in SAARC Countries

[![Live Site](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-blue?style=flat&logo=github)](https://faranabbas-repo.github.io/fiscal-trade-gdp)
[![Data Source](https://img.shields.io/badge/Data-World%20Bank%20WDI-orange?style=flat)](https://datacatalog.worldbank.org/search/dataset/0037712)

Regional macroeconomic analysis of how fiscal revenue capacity and trade openness relate to GDP across SAARC countries from 2000 to 2024.

This project is designed as an economics portfolio piece: it uses real World Bank data, focuses on a clear regional policy question, and presents the results through a reproducible Quarto website.

## Project Snapshot

- Region: SAARC
- Countries: Afghanistan, Bangladesh, Bhutan, India, Maldives, Nepal, Pakistan, and Sri Lanka
- Period: 2000-2024
- Data source: World Bank World Development Indicators
- Variables: GDP, trade openness, and revenue excluding grants
- Tools: R, WDI, tidyverse, ggplot2, Quarto

## Research Question

How do trade openness and fiscal revenue capacity relate to economic output across SAARC countries?

The project compares cross-country patterns in:

- GDP in current US dollars
- trade as a share of GDP
- revenue excluding grants as a share of GDP

The broader motivation is to connect macroeconomic policy conditions to differences in economic scale and regional performance.

## Why This Project Matters

SAARC economies differ sharply in size, openness, and fiscal capacity. That makes the region a useful setting for comparing how macroeconomic indicators move across neighboring countries with different development paths.

For a portfolio, this repo demonstrates the ability to:

- work with cross-country macroeconomic data
- use the World Bank WDI API in R
- clean and document regional panel data
- build visual analysis around an economics question
- communicate findings through a public website

## Data

Source: World Bank World Development Indicators (WDI)

Indicators used:

- `NY.GDP.MKTP.CD`: GDP (current US dollars)
- `NE.TRD.GNFS.ZS`: Trade openness as a percentage of GDP
- `GC.REV.XGRT.GD.ZS`: Revenue, excluding grants (% of GDP)

Coverage:

- 8 SAARC countries
- Annual observations from 2000 to 2024

## Method and Analysis

The project retrieves WDI data for all SAARC member countries, cleans missing values, and visualizes the relationship between trade openness and GDP across the full period.

The fiscal revenue variable is included to support a broader macroeconomic comparison of how external openness and state revenue capacity relate to economic performance in the region.

This project is best understood as an exploratory regional macroeconomic analysis rather than a causal identification exercise.

## Main Takeaway

The visual evidence suggests that more externally integrated SAARC economies tend to appear among the stronger economic performers in the sample, though country size differences are substantial and fiscal conditions vary across time and across countries.

That makes the project useful as a starting point for deeper work on:

- regional trade integration
- fiscal capacity and state revenue
- development differences within South Asia

## Economics Skills Demonstrated

- Regional macroeconomic analysis
- WDI data retrieval in R
- Data cleaning and variable construction
- Comparative interpretation across countries
- Visualization of economic indicators
- Quarto website publishing

## Live Output

- Live site: [fiscal-trade-gdp](https://faranabbas-repo.github.io/fiscal-trade-gdp)
- Repository: [faranabbas-repo/fiscal-trade-gdp](https://github.com/faranabbas-repo/fiscal-trade-gdp)

## Repository Structure

```text
fiscal-trade-gdp/
|-- index.qmd          Main project page and visualization
|-- index.rmarkdown    Alternate source version
|-- about.qmd          Author and project overview
|-- sources.qmd        Data definitions and sourcing
|-- _quarto.yml        Website configuration
|-- styles.css         Site styling
|-- README.md          Project overview
|-- _site/             Rendered site output
`-- site_libs/         Static site assets
```

## Reproducibility

Install the required packages in R:

```r
install.packages(c("WDI", "tidyverse", "ggplot2"))
```

Then render the site with Quarto after opening the project locally.

## Portfolio Value

This repo strengthens an economics CV because it shows a clear regional policy theme, a real dataset, and a public-facing analytical deliverable rather than just a list of software tools.

A concise CV description for this project could be:

> Built a regional macroeconomic project on SAARC countries using World Bank WDI data (2000-2024), analyzing the relationship between government revenue capacity, trade openness, and GDP in R and publishing the results as a Quarto website.

## Author

Faran Abbas
Graduate Student, World Economy, Shandong University

- Email: [faranabbas@hotmail.com](mailto:faranabbas@hotmail.com)
- GitHub: [faranabbas-repo](https://github.com/faranabbas-repo)

## Acknowledgment

This project was developed as part of [Kane's Data Science Bootcamp](https://bootcamp.davidkane.info/).
