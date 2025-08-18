# PS1: Nonstationary Rainfall Frequency Analysis

**Assigned:** August 25, 2025 | **Due:** October 6, 2025 | **Module:** 1 | **Points:** 10%

## Core Problem

How likely is a part of Houston to experience different daily rainfall amounts, and how is this changing over time?

## Overview

This problem set develops skills in extreme value theory, Bayesian statistics, and hierarchical modeling through analysis of Houston-area precipitation data. Students will investigate changing flood risks and their implications for infrastructure design using state-of-the-art statistical methods.

## Provided Materials

- Daily precipitation data for 5-6 Houston-area stations (1970-2023)
- Boilerplate Quarto template with data loading and basic plotting functions

## Tasks

1. **Stationary GEV Analysis**: Fit stationary GEV model using MLE and Bayesian approaches
2. **Nonstationarity Assessment**: Analyze trends across multiple stations using rolling windows and Mann-Kendall tests
3. **Regional Comparison**: Identify spatial patterns in trend strength and consistency
4. **Nonstationary Modeling**: Fit time-varying GEV models with climate covariates
5. **Hierarchical Pooling**: Implement regional partial pooling to improve parameter estimates
6. **Stakeholder Communication**: Address engineering concerns about climate-informed design values

## Learning Objectives

- Apply extreme value theory fundamentals (AMS vs POT approaches)
- Implement Maximum Likelihood Estimation and understand its limitations
- Use Bayesian statistics and MCMC methods for uncertainty quantification
- Apply regional pooling through hierarchical models to address data scarcity
- Model non-stationary extremes with covariate approaches
- Select between competing models using formal criteria

---

This is a problem set for [CEVE 543 at Rice University](https://ceve543.github.io/), taught by James Doss-Gollin.
Please see the [assignment file](./index.qmd) for the assignment details.
