# nifty50-volatility-analysis
Econometric analysis of NIFTY 50 returns using R: volatility clustering, fat tails, ARCH effects, and market efficiency diagnostics.
## Overview

This project analyzes the statistical properties and volatility dynamics of NIFTY 50 daily log returns from 2007–2025 using econometric and time-series methods in R.

The study examines whether NIFTY 50 returns exhibit:
- weak-form market efficiency
- volatility clustering
- fat-tailed behavior
- conditional heteroscedasticity
- asymmetric volatility effects

The analysis was conducted using R and published as an interactive HTML report via GitHub Pages.

---

## Key Findings

- Daily returns exhibit near-zero linear predictability
- Return distributions display strong excess kurtosis and fat tails
- Significant ARCH effects confirm volatility clustering
- Squared returns exhibit persistent autocorrelation
- Evidence consistent with the leverage effect was observed
- Gaussian VaR models underestimate downside risk

---

## Methods Used

- Log return transformation
- Descriptive statistics
- Jarque–Bera normality test
- Augmented Dickey–Fuller stationarity test
- ACF and PACF analysis
- Ljung–Box diagnostics
- ARCH LM test
- Rolling volatility analysis
- Value-at-Risk comparison

---

## Tools and Libraries

- R
- R Markdown
- quantmod
- tseries
- FinTS
- zoo
- knitr

---

## Live Report

[View Full HTML Report](https://aanyashrivastava.github.io/NIFTY50-Volatility-Analysis/)

---

## Repository Structure

```text
docs/
├── index.html
└── style.css

nifty50_analysis.Rmd
README.md
```

---

## Author

Aanya Shrivastava
