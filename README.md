# OpsGuard: Early-Warning Anomaly Detection for Operational Time Series

## Project goal

This project builds an end-to-end anomaly detection pipeline for operational time-series data.  
The goal is to detect unusual behavior early, compare multiple baselines and models, and evaluate them with time-aware validation.

## Why this project matters

Operational anomalies can indicate incidents, system degradation, load spikes, sensor failures, or unusual behavior in monitored services.  
This repository focuses on a realistic and reproducible workflow instead of a toy example.

## What this repository demonstrates

- structured machine learning project setup
- time-series-aware anomaly detection
- feature engineering for operational metrics
- baseline comparison
- reproducible evaluation
- clear visual communication of results
- separation of notebooks and reusable Python code

## Dataset

The first version of the project uses a public anomaly detection benchmark dataset.

Planned workflow:
1. Load and inspect the data
2. Build rolling statistical features
3. Create time-aware train/validation splits
4. Compare baselines and anomaly detection models
5. Perform error analysis
6. Summarize findings and limitations

## Repository structure

```text
opsguard-anomaly-detection/
├── README.md
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
├── notebooks/
├── src/
│   └── opsguard/
├── reports/
│   ├── figures/
│   └── results/
└── tests/
```
## Current status
Project setup in progress.
