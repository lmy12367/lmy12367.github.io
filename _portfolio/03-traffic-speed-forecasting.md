---
title: "Short-Term Traffic Speed Forecasting"
excerpt: "A leakage-safe traffic forecasting pipeline with robustness evaluation under random masking and road-wise outage settings."
collection: portfolio
date: 2026-05-06
---

This individual project builds a leakage-safe time-series forecasting pipeline for Guangzhou urban traffic speed data. The data contains 214 roads, 61 days, and 10-minute panel observations, split chronologically for training, validation, and testing.

I compared Seasonal Naive, Linear Regression, Random Forest, Matrix Factorization with latent VAR, and online probabilistic low-rank models. The evaluation covers 10, 30, and 60-minute forecasting horizons using RMSE, MAE, sMAPE, NLL, and CRPS.

The project also includes robustness experiments under random masking and road-wise outage conditions to test model behavior when traffic inputs are incomplete.
