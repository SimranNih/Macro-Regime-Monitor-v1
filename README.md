# Macro-Regime-Monitor-v1

# Global Macro Dashboard

## Overview

The Global Macro Dashboard is an Excel-based macroeconomic monitoring framework designed to compare economic conditions, monetary policy, financial conditions, and market sentiment across a diversified universe of developed and emerging market economies.

The objective is to provide a structured, data-driven approach to assessing country attractiveness, identifying macroeconomic regimes, and monitoring central bank policy stances.

The dashboard currently covers 19 economies across:

* Developed Markets
* Asia Growth Block
* Latin America
* Strategic Emerging Markets

---

## Dashboard Structure

### Sheet 1 – Macro Regime Monitor

The Macro Regime Monitor evaluates countries using four pillars:

#### Macro Score

Measures economic momentum using:

* GDP Momentum
* Unemployment Momentum
* PMI Momentum

#### Policy Score

Measures monetary policy stance using:

* Real Rate
* Inflation Gap

#### Financial Conditions Score

Measures market and funding conditions using:

* 10Y Government Bond Yield
* Yield Curve Slope
* Equity Market Returns
* FX Performance
* Sovereign Spread

#### Sentiment Score

Measures investor risk appetite using:

* Equity Momentum
* FX Momentum
* Market Stress Proxy

The four pillars are combined into a composite score used to rank countries and classify them into macroeconomic regimes.

---

### Regime Classification

Countries are classified into:

* Expansion
* Late Cycle
* Recovery
* Stress
* Stagflation Shock
* Neutral

Regime definitions are based on economic conditions rather than ranking outcomes to minimise overfitting.

---

### Sheet 2 – Central Bank Comparator

The Central Bank Comparator evaluates monetary policy across the country universe using:

* Policy Rates
* Inflation Targets
* Inflation Gaps
* Real Rates
* Most Recent Policy Actions

Central banks are classified into four categories:

* Restrictive
* Fighting Inflation
* Accommodative
* Behind the Curve

This framework provides a simple cross-country comparison of policy stance and inflation control.

---

## Methodology

All indicators are standardized using Min-Max Normalization:

For indicators where higher values are favourable:

Score = ((Value - Minimum) / (Maximum - Minimum)) × 100

For indicators where lower values are favourable:

Score = ((Maximum - Value) / (Maximum - Minimum)) × 100

Scores are relative to the selected country universe and therefore represent relative attractiveness rather than absolute economic strength.

---

## Data Sources

The dashboard uses publicly available macroeconomic and market data including:

* Inflation (CPI)
* GDP Growth
* Unemployment Rates
* Manufacturing PMI
* Policy Rates
* Government Bond Yields
* Equity Index Levels
* Foreign Exchange Rates

---

## Current Features

* Country Ranking Framework
* Macro Regime Classification
* Central Bank Comparator
* Composite Scoring Engine
* Top/Bottom Country Rankings
* Policy Stance Classification
* Automated Data Structure for Future Updates

---

## Planned Enhancements

* Policy Divergence Monitor
* FX Implications Dashboard
* Emerging Market Monitor
* Central Bank Policy Quadrant
* Restrictiveness Rankings
* Inflation Credibility Rankings
* Historical Regime Tracking
* Automated Python-Based Data Refresh

---

## Disclaimer

This project is intended for educational and research purposes only and should not be considered investment advice.
