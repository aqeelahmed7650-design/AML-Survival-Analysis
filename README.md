# AML-Survival-Analysis
# Univariate Survival Stratification in Acute Myeloid Leukemia (AML)

This repository holds a translational medicine pipeline executing **Kaplan-Meier survival modeling** in **R** (`survival`, `survminer`, `tidyverse`) to evaluate single-marker molecular risk metrics in acute leukemias.

## Study Objectives & Design
* **Clinical Intent:** Evaluate the isolated prognostic footprint of **NPM1 mutations** on overall patient survival curves.
* **Biostatistics Architecture:** Utilizes the classic non-parametric Kaplan-Meier estimator alongside the Log-Rank test to compare median cohort timelines over a 60-month follow-up window.

## Target Visualization: Curve Metrics
The plot below tracks cumulative survival percentages across the molecular cohorts, verified via 95% confidence intervals and an active patients-at-risk assessment grid.

![Univariate Survival](univariate_survival_plot.png)

## Translational Application
This script serves as a baseline data screening engine. It showcases how a researcher can rapidly audit incoming bone marrow trial registries to see if individual novel mutations correlate with significantly distinct patient survival windows before launching deeper multivariate hazard metrics.
