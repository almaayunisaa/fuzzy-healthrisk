# Fuzzy Logic-Based Health Risk Prediction Using U.S. Pollution Dataset

## Description

This project implements a Fuzzy Logic model to predict health risk levels based on U.S. pollution data.  
The model utilizes AQI, SO₂ mean, O₃ mean, NO₂, and CO measurements to estimate the health risk.  
Predictions are derived from AQI values categorized through fuzzy membership functions.

## Features

- Utilizes Fuzzy Logic with inputs:
  - AQI (Air Quality Index)
  - SO₂ Mean
  - O₃ Mean
  - NO₂
  - CO
- Predicts health risk levels based on pollution data
- Uses U.S. Pollution Dataset
- Visualization of fuzzy membership functions and inference results

## Usage

1. Clone this repository
2. Open `Fuzzy-HealthRisk.ipynb` with Jupyter Notebook or Jupyter Lab
3. Run all cells to execute the health risk prediction

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-fuzzy

You can install the requirements with:

```bash
pip install numpy pandas matplotlib scikit-fuzzy
