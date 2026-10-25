# STAI-X Computational Epidemiology

This repository contains the R code developed for the STAI-X Challenge 2026 [Award A], a computational epidemiology forecasting competition focused on predicting overdose-related emergency department visit rates.

## Project Overview

The objective of this project was to develop predictive models capable of forecasting overdose-related emergency department visit rates using demographic, socioeconomic, environmental, and administrative data sources.

A stacked ensemble framework combining Ridge Regression and XGBoost was implemented to capture both linear and non-linear relationships within the data.

## Methods

### Data Preparation

- Missing data assessment and imputation
- Missingness indicator engineering
- Feature transformation and normalization
- Log-transformation of skewed variables
- Data integration from multiple sources

### Feature Engineering

- Socioeconomic feature construction
- Text-derived metrics
- Target encoding
- Spatial and jurisdiction-level aggregation

### Machine Learning Models

- Ridge Regression
- XGBoost
- Stacked Generalization Ensemble

### Model Optimization

- Cross-validation
- Out-of-fold prediction generation
- Meta-model weight optimization
- Ensemble calibration

## Software

- R
- tidymodels
- dplyr
- xgboost
- glmnet
- ggplot2

## Key Skills Demonstrated

- Computational Epidemiology
- Predictive Modeling
- Feature Engineering
- Ensemble Learning
- Target Encoding
- Forecasting
- Reproducible Research

## Data Availability

Competition datasets are not included in this repository. Only analytical code and selected outputs are provided. Please visit the competition link for the data:
https://www.kaggle.com/competitions/stai-x-challenge-2026

## Author

Farshad Parsayan

## License

MIT License
