# Emission Probabilities Impact on LSTM Performance

This project implements an algorithm that evaluates whether emission probabilities from Gaussian Mixture Models (GMM) or Extreme Gradient Boosting (XGB) affect the performance of a Long Short-Term Memory (LSTM) network. The study involved performing an ANOVA test to determine statistical significance.

## Overview

The project builds on concepts from the study "Stock Market Trend Analysis Using Hidden Markov Model and Long Short Term Memory" by Mingwen Liu et al., which applies HMM and LSTM to stock market prediction. This repository explores the impact of using GMM-HMM and XGB-HMM as emission probability models for LSTM.

## Features

- **GMM-HMM**: Uses Gaussian Mixture Models for emission probabilities in a Hidden Markov Model.
- **XGB-HMM**: Utilizes XGBoost for emission probabilities in a Hidden Markov Model.
- **LSTM Integration**: Combines the emission probability models with LSTM to evaluate performance.
- **Statistical Analysis**: Includes ANOVA tests to assess the significance of the models' impact on LSTM performance.

## Results
he results showed a statistically significant change in LSTM performance when using emission probabilities compared to the reference, but no significant difference was observed between GMM-HMM and XGB-HMM models.
