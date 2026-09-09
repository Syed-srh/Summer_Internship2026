# Task 1: Data Understanding and Exploration

## Overview

This task introduces the initial steps of a data analysis workflow. Two datasets are loaded with pandas and inspected to understand their structure, contents, summary statistics, and data-quality considerations before applying machine learning techniques.

## Datasets

- `titanic.csv` - Titanic passenger records.
- `student_data.csv` - Student-related data.

## Objectives

- Load CSV files using pandas.
- Preview the first and last records.
- Inspect column names, data types, and non-null values.
- Review descriptive statistics for numerical columns.
- Identify possible data-quality issues, such as missing values and class imbalance.

## Analysis Performed

The notebook uses the following pandas operations on both datasets:

- `head()` to display the first records.
- `tail()` to display the last records.
- `info()` to inspect the dataset structure and missing values.
- `describe()` to generate descriptive statistics.

## Findings

The datasets require additional preprocessing before they can be used reliably for machine learning. Potential next steps include handling missing values, encoding categorical variables, scaling numerical features where appropriate, and evaluating whether the target classes are imbalanced.

## Requirements

- Python 3.x
- pandas
- NumPy
- Jupyter Notebook or Google Colab

Install the Python dependencies with:

```bash
pip install pandas numpy jupyter
```

## How to Run

1. Open `Task_1.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Keep the notebook and both CSV files in the same directory when running locally.
3. Run the notebook cells in order.

> When running locally, use relative file paths such as `pd.read_csv("titanic.csv")` and `pd.read_csv("student_data.csv")` instead of environment-specific paths.

## Files

```text
Task-1/
├── README.md
├── Task_1.ipynb
├── student_data.csv
└── titanic.csv
```
