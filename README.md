# Predicting German Party Polling Results with Google Trends Data

## Overview

This project investigates whether Google search interest in salient political issues can predict polling results of German political parties. Drawing on issue voting and issue ownership theories, it examines whether public interest in topics such as immigration, climate change, inflation, and social policy is associated with party support.

## Methods

- Data collection: Weekly German party polling data from FORSA, Google Trends data, and survey responses from the ZDF-Politbarometer.
- Validation: Evaluating Google Trends as a measure of issue salience using content and criterion validity.
- Time-series analysis: Assessing stationarity, removing seasonality, and examining correlations and OLS regressions.
- Predictive modelling: Comparing autoregressive models with and without Google Trends data using the Bayesian Information Criterion (BIC).

## Key Findings

- Google Trends data showed strong correlations between immigration-related searches and polling results for the AfD.
- Inflation-related search interest was significantly associated with CDU/CSU polling results in regression analysis.
- Most Google Trends indices did not meet the validation criteria for measuring issue salience.
- Adding search data did not improve the predictive performance of autoregressive polling models.
- Overall, the findings suggest that correlation between online search interest and party support does not necessarily translate into predictive value.

## Data Sources

- FORSA polling data
- GESIS – ZDF Politbarometer
- Google Trends
## Reference

Thiele, J. (2025). Predicting Polling Results of German Parties with Google Trends Data of Political Topics.
