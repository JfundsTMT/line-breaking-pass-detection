# Detecting Line-Breaking Pass Attempts in Professional Football

**BSc Computer Science Dissertation | Aston University | 2026**

## Overview
ML model to detect and predict line-breaking pass attempts (LBPAs) in professional football using StatsBomb 360 event data. Achieved ROC-AUC of 0.88 using Gradient Boosting on spatial and contextual pass features.

## Key Results
- ROC-AUC: 0.88
- Model: Gradient Boosting Classifier
- Dataset: StatsBomb 360 open data

## Tech Stack
Python · pandas · scikit-learn · mplsoccer · matplotlib

## Methodology
1. Extracted pass events from StatsBomb JSON event data
2. Enriched with 360 freeze-frame spatial context
3. Engineered features: pass angle, distance, defensive line position
4. Trained and evaluated Gradient Boosting model

## Data
Uses StatsBomb open data (not included). Download from [StatsBomb Open Data](https://github.com/statsbomb/open-data) and place in `data_raw/`.

## Setup
```bash
pip install -r requirements.txt
```
Then run the notebooks in order.
