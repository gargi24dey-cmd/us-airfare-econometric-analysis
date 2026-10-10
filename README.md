# The Impact of Jet Fuel Prices and Passenger Demand on Airline Fares in the United States

### An Econometric Analysis of U.S. Airline Fares (2000–2025)

## 📌 Project Overview

This research examines the relationship between jet fuel prices, passenger demand, and airline fares in the United States from January 2000 to September 2025. It investigates how changes in airline operating costs and passenger demand are associated with airfare movements, while accounting for major disruptions such as the September 11 attacks and the COVID-19 pandemic.

The study applies time-series econometric techniques to understand both short-run changes and longer-term relationships between these variables.

## 🎯 Research Objectives

- Examine the relationship between jet fuel prices and airline fares.
- Analyse the association between passenger demand and airfare movements.
- Investigate the effects of major economic and industry disruptions.
- Compare short-run airfare responses with relationships observed in log-level models.
- Assess the statistical reliability of the estimated models.

## 📊 Data and Variables

The analysis uses monthly secondary data covering January 2000 to September 2025, comprising 309 observations.

| Variable | Description |
|---|---|
| Airline Fares | U.S. airline fare price index |
| Jet Fuel Prices | Jet fuel Producer Price Index used as a proxy for fuel costs |
| Passenger Demand | Revenue Passenger Miles (RPM) |
| September 11 Dummy | Indicator for the September 11 disruption |
| COVID-19 Dummy | Indicator for the COVID-19 pandemic period |

### Data Sources
- **U.S. Bureau of Labor Statistics (BLS):** Airline fare price index
- **Federal Reserve Economic Data (FRED):** Jet fuel price proxy and Revenue Passenger Miles

## 🛠️ Methodology

The study uses **R** for time-series econometric analysis. The methods include:

- Logarithmic transformations of variables
- Augmented Dickey-Fuller (ADF) tests for stationarity
- Variance Inflation Factor (VIF) for multicollinearity assessment
- Short-run regression using differenced log variables
- Log-level regression analysis
- COVID-19 interaction model
- Durbin-Watson test for autocorrelation
- Breusch-Pagan test for heteroskedasticity
- Jarque-Bera test for residual normality
- Newey-West heteroskedasticity and autocorrelation-consistent standard errors

## 🔍 Key Findings

The reported regression results suggest that:

- **Jet fuel prices:** Changes in jet fuel prices have a positive and statistically significant association with short-run airfare changes.
- **Passenger demand:** Changes in passenger demand are positively associated with short-run airfare changes and are statistically significant in the short-run model.
- **COVID-19:** The COVID-19 indicator is statistically significant in the log-level model, suggesting a relationship between the pandemic period and airline fares.
- **September 11:** The September 11 indicator is not statistically significant in the reported models.
- **Interaction effects:** The estimated COVID-19 interaction effects are not statistically significant in the reported interaction model.

These findings are model-specific statistical associations and should not automatically be interpreted as causal effects.

## 💡 Conclusion

The research highlights the relevance of fuel costs and passenger demand in understanding U.S. airline fare movements. It also demonstrates the importance of accounting for structural disruptions and applying appropriate time-series diagnostic techniques when analysing economic data.

## 🧰 Tools and Technologies

- R
- Time-Series Econometrics
- Regression Analysis
- Statistical Hypothesis Testing
- Data Analysis and Visualisation

## 📄 Research Paper

The complete research paper is available in this repository as **`research-paper.pdf`**.

It contains the research framework, methodology, regression results, and interpretation.

## ⚠️ Reproducibility Note

This repository presents the completed research paper. The original dataset and R scripts are not currently included, so the reported analysis cannot be independently reproduced from this repository alone.

---

**Author:** Gargi Dey  
**Institution:** Symbiosis School of Economics  
**Research Area:** Applied Econometrics, Aviation Economics, and Time-Series Analysis
