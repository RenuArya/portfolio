# Drift Diffusion Model Analysis

## Overview

Modeling 8,000+ behavioral decision-making trials using Drift Diffusion Models (DDM) to estimate latent cognitive parameters in value-based decision making across different stake sizes.

## Objectives

1. **Model Fitting**: Parameter estimation using Hierarchical Bayesian modeling
2. **Latent Variable Recovery**: Estimate drift rate, loss aversion, utility weighting, evidence accumulation
3. **Stake Size Effects**: Compare decision parameters across different monetary stakes
4. **Computational Implementation**: Full pipeline in Python

## Methods

- **Data Collection**: 8,000+ trials from behavioral experiments
- **Modeling Framework**: Drift Diffusion Model with hierarchical structure
- **Bayesian Estimation**: Stan/PyMC for parameter recovery
- **Validation**: Posterior predictive checks, cross-validation

## Key Parameters Estimated

- **Drift Rate (v)**: Speed of evidence accumulation
- **Boundary Separation (a)**: Response caution
- **Non-decision Time (Ter)**: Perceptual/ motor processing time
- **Loss Aversion**: Asymmetry in processing gains vs. losses
- **Utility Weighting**: Subjective value transformation

## Technical Stack

- **Primary**: Python (PyMC, ArviZ, NumPy, pandas)
- **Visualization**: matplotlib, seaborn
- **Analysis**: Jupyter Notebooks for interactive analysis

## Results

- Successfully recovered DDM parameters from behavioral data
- Demonstrated stake-size effects on loss aversion
- Identified individual differences in evidence accumulation
- Validated model fit through posterior predictive checks

## Contact

For collaboration inquiries: renu@iitdalumni.com