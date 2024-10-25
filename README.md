# Bayesian Analysis of Iris Dataset

## Overview
This project uses Bayesian statistical modeling to analyze the `sepal_width` feature of the Iris dataset. The project compares different models (Normal and Student's-T) and evaluates the robustness of each model in handling the data distribution. It further extends to group comparisons across three species of the Iris dataset (Setosa, Versicolor, and Virginica) using Bayesian modeling and statistical metrics.

## Objectives
- Estimate the **prior** and **likelihood** of the `sepal_width` feature using both Normal and Student's-T distributions.
- Compare the posterior results of these models to determine which is more robust.
- Group the data by species and analyze `sepal_width` using Bayesian models.
- Apply group comparison techniques, such as **Cohen’s d** and **Probability of Superiority**, to quantify differences between species.

## Requirements
The following libraries are required to run this project:
- `pymc`
- `arviz`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

Install them using:
```bash
pip install pymc arviz pandas numpy matplotlib seaborn scipy
