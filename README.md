# Bayesian Kelly | Graduate Thesis

**Spring 2026 — STAT GR 5224 Bayesian Statistics / Graduate Thesis:** Columbia graduate thesis on stabilizing Kelly portfolio optimization under estimation risk using Bayesian shrinkage, posterior diagnostics, and BOCPD regime-aware sizing.

## Project Context

- **Date:** Spring 2026
- **Course:** STAT GR 5224 — Bayesian Statistics
- **Institution:** Columbia University
- **Project Type:** Graduate thesis
- **Author:** Syed Bashir Hydari
- **Research Area:** Bayesian portfolio construction, Kelly Criterion stabilization, estimation risk, and regime-aware allocation

## Overview

This thesis investigates why plug-in Kelly portfolio optimization fails out-of-sample on equity panels and whether Bayesian regularization can stabilize its performance.

The central finding is that the binding constraint is **mean-estimation noise**, not covariance ill-conditioning. Static Bayesian shrinkage on expected returns improves performance modestly, while BOCPD-driven regime-aware sizing produces the strongest practical improvement.

## Methods

- Kelly Criterion portfolio optimization
- Normal-Normal Bayesian shrinkage on expected returns
- Ledoit-Wolf covariance shrinkage
- Bayesian Online Changepoint Detection, or BOCPD
- Hierarchical Bayesian partial pooling
- Metropolis-Hastings verification
- Gibbs sampling
- Delta-method Sharpe ratio inference
- Jump-diffusion Monte Carlo stress testing

## Key Result

The strongest Kelly variant is **RegimeDial**, which uses BOCPD regime labels as state-dependent fractional Kelly multipliers rather than as filters for moment estimation. This suggests that regime information is more robust when used for sizing than when used to condition noisy return estimates.

## Note

This repository contains selected academic thesis materials only. It is not investment advice and does not contain production trading infrastructure.
