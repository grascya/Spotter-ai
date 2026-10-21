# Spotter Freight Rate Model

## Overview

This project trains a freight rate prediction model using the labeled development data in data/train-test.csv and produces final predictions for data/validation.csv.

## Files

- Freight_Model.ipynb: main analysis, feature engineering, model training, and prediction notebook
- validation_predictions.csv: final submission file
- scorer_results/candidate_december.png: December chart produced by score.py

## Setup

Install the required Python packages:

pip install -r requirements.txt

## How to run

1. Open and run `Freight_Model.ipynb` from top to bottom.
2. The notebook creates `validation_predictions.csv`.
3. The notebook also runs `score.py` to generate the December prediction chart.

## Final output format

The submission file must contain exactly:

- `load_id`
- `predicted_rate`
