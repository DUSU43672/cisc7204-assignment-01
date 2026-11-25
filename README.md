# CISC7204 Assignment 01 — Data Analytics Labs

**Author:** Sun Yuanjiao (MC65343), University of Macau
**Course:** CISC7204 — Assignment 01

This repository collects the completed lab notebooks and supporting datasets for
Assignment 01. The work follows a typical data-analytics pipeline on two price-prediction
datasets (used cars and laptops), and finishes with two capstone projects on insurance costs
and house pricing.

## Topics Covered

- Data loading and preliminary inspection
- Data wrangling: handling missing values, data normalisation, data formatting
- Exploratory data analysis: distributions, correlations, group comparisons
- Model development: simple and multiple linear regression, polynomial regression
- Model evaluation and refinement: train/test split, evaluation metrics, cross-validation, ridge regression

## Repository Structure

```
cisc7204-assignment-01/
├── README.md
├── module1/   # Lab01 Used Car Pricing, Lab02 Laptop Pricing (introduction)
├── module2/   # Data Wrangling — Used Car / Laptop Pricing; raw and cleaned CSVs
├── module3/   # Exploratory Data Analysis — Used Car / Laptop Pricing
├── module4/   # Model Development — Used Car / Laptop Pricing
├── module5/   # Model Evaluation and Refinement — Used Car / Laptop Pricing
└── module6/   # Practice project: Insurance Cost; Final project: House Pricing
```

## Datasets

The CSV files in `module2/`, `module4/` and `module5/` are public course datasets used for
lab exercises. They contain no personal identifiers. No passwords, API keys or restricted
datasets are included in this repository.

## How to Run

The notebooks are Jupyter notebooks. To reproduce an analysis:

1. Install Python 3 and the required packages (pandas, NumPy, Matplotlib, Seaborn, scikit-learn).
2. Open the notebook in the matching `moduleX/` folder with Jupyter Notebook or JupyterLab.
3. Run the cells in order; the CSV datasets are stored alongside the notebooks.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Jupyter Notebooks
