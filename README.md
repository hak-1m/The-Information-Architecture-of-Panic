# The Information Architecture of Panic 📰⚡

> **Quantifying the Asymmetrical Impact of Global Media Sentiment on Commodity Volatility**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![R-Project](https://img.shields.io/badge/Language-R%20%7C%20Econometrics-blue)](https://www.r-project.org/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--4999--1861-green)](https://orcid.org/0009-0003-4999-1861)
[![DOI](https://img.shields.io/badge/Zenodo-Record%2022096182-blue)](https://zenodo.org/records/22096182)
[![Research Status](https://img.shields.io/badge/Status-Research%20Preprint-orange)](#)

---

## 📌 Executive Summary

Standard economic models often assume that commodity prices adapt purely to physical shifts in supply and demand curves. However, in an interconnected global economy, informational cascades and media-driven sentiment shifts can artificially amplify market volatility long before physical supply shocks manifest.

This research repository establishes a behavioral econometric framework to evaluate the predictive capacity of a media-generated Global Fear Index over the price dynamics and conditional volatility of strategic commodity asset classes. 

By analyzing daily data from 2018 through 2024, the study demonstrates that high-frequency media panic acts as an asymmetric leading indicator for energy markets, while precious metals and agricultural commodities remain largely insulated from headline noise.

---

## 🔬 Methodology and Approach

To evaluate how high-frequency textual news flows materialize as physical market variance, this project bridges computational natural language processing metrics with advanced financial econometrics.

The dataset integrates daily spot prices across three distinct commodity classes—Crude Oil (energy exposure), Gold (systemic macro-anchor), and Corn (agricultural cycle exposure)—with official sentiment and market risk indicators from the Federal Reserve Bank of St. Louis (FRED) database. These include the CBOE Volatility Index and the Economic Policy Uncertainty Index.

The analytical pipeline executes two primary econometric evaluations:
1. **Granger Causality Verification:** Evaluates directional informational lead times from media fear metrics to daily asset returns and conditional volatility across one-to-three-day lag horizons.
2. **Asymmetric HAC Regression Framework:** Decomposes daily changes in media fear into positive spikes (anxiety expansion) and negative drops (calming market signals) to quantify whether bad news destabilizes markets faster than good news restores stability.

---

## 📊 Key Findings

Our empirical evaluation confirms the main research hypotheses, revealing critical insights into market microstructure and information processing:

* **Energy Sector Hyper-Sensitivity:** Systemic spikes in media fear exercise a direct, statistically significant expansionary force on Crude Oil conditional volatility. Energy markets operate under just-in-time supply chains and geopolitical chokepoints, making them uniquely vulnerable to immediate news streams.
* **The Asymmetry of Fear:** Media fear shocks exhibit severe structural asymmetry in energy markets. Sudden expansions of geopolitical panic trigger defensive option hedging and volatility surges almost instantaneously. Conversely, an equivalent reduction in fear fails to compress uncertainty or compress asset variance at the same speed.
* **Informational Lead Time:** Directional causality tests prove that media sentiment metrics lead Crude Oil volatility shifts with a clear one-to-three-day informational lead time, establishing news tracking as a genuine nowcasting vector.
* **Cross-Asset Insulation:** Neither Gold nor Corn displays statistically significant volatility transmission from high-frequency media noise. Gold acts as a long-term macro store of value, filtering out daily headline spikes, while agricultural commodities remain governed by multi-month crop cycles and weather fundamentals.

---

## 🛠️ Data Pipeline & Technology Stack

* **Automated Market Data Retrieval:** Programmatic fetching of multi-asset market prices and FRED uncertainty indices using API connectors in R.
* **Stationarity & Return Transformations:** Processing daily logarithmic asset returns and rolling conditional volatility proxies.
* **Robust Econometrics:** Execution of Granger Causality tests and Ordinary Least Squares regressions equipped with Newey-West robust standard errors to correct for heteroskedasticity and autocorrelation.

---

## 🎯 Quantitative Risk Management & Policy Implications

The empirical confirmation of media-driven volatility lead times enables the integration of text-mined sentiment directly into institutional risk architectures:

1. **Sentiment-Adjusted Value-at-Risk:** Portfolio risk managers holding energy assets should dynamically expand their daily liquidity buffers and risk thresholds upon detecting positive media fear spikes prior to physical options repricing.
2. **Cross-Asset Hedging:** During sudden media panic cascades, institutional investors can execute automated rebalancing by shorting energy volatility while reallocating capital into insulated structural anchors like Gold.
3. **Algorithmic Trading Filters:** Quantitative desks can incorporate natural language processing news feeds into market-making algorithms to widen bid-ask spreads dynamically during headline spikes, mitigating adverse selection risks.

---

## ✒️ Citation & Author Info

**Author:** Bekdaulet Abzhamiev  
**Role:** Researcher  
**ORCID:** [0009-0003-4999-1861](https://orcid.org/0009-0003-4999-1861)  
