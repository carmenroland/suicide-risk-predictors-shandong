# Analysis Scripts

## Purpose

This folder contains the code used to conduct exploratory data analysis, statistical modeling, model evaluation, and visualization for the Shandong suicide risk project.

The analysis was performed in R using a reproducible R Markdown workflow that integrates data preparation, statistical modeling, graphical analysis, and interpretation of results into a single document.

## Contents

### shandong_suicide_analysis.Rmd

The primary analysis script for the project. This document includes:

- Data import and preprocessing
- Exploratory data analysis (EDA)
- Univariate and bivariate visualizations
- Logistic regression modeling
- Confidence interval estimation
- Model diagnostics
- ROC curve analysis
- Interaction modeling
- Classification performance assessment

## Analysis Workflow

1. Import and inspect the dataset
2. Clean and prepare variables for analysis
3. Explore distributions and relationships among predictors
4. Fit logistic regression models
5. Evaluate model performance and assumptions
6. Interpret statistically significant predictors
7. Generate visualizations and summary results

## Software

The analysis was conducted using:

- R
- R Markdown
- tidyverse
- ggplot2
- pROC
- Additional statistical and visualization packages documented within the script

## Reproducibility

The script is designed to provide a transparent record of the analytical process. Users wishing to reproduce the analysis should obtain the original dataset (see the `data/` directory for information on data sources and availability) and update file paths as needed.

## Related Materials

Additional project materials can be found in:

- `../docs/` – Final report and presentation materials
- `../output/` – Generated figures and model outputs
- `../data/` – Dataset documentation and source information
