# Structural Reorganization of Failure-Sensitive Mortality in Adolescence
## Derived Data and Analytical Code Repository

This repository contains:

• All R code used to compute structural metrics  
• All derived datasets used to generate publication figures and tables  
• Prism-ready CSV files corresponding to manuscript figures  

⚠ Raw Global Burden of Disease (GBD) exports are NOT included.  
GBD 2023 cause-of-death estimates are publicly available via the IHME Results Tool.

---

## What is included

### 1. Analytical code (R)
- Universe‑1 construction (95% cumulative YLL threshold, ages 5–24)
- Proportional cause composition
- Age‑transition magnitude (sum of absolute proportional differences, 10–14 vs 15–19)
- Jensen–Shannon distance (JSD)
- Monte Carlo uncertainty propagation (2,000 draws; log‑normal parameterization)

### 2. Derived datasets
Located in:

```
outputs/prism_inputs/
```

These files contain the exact numeric values used to generate all main and supplementary figures.

---

## Data source

Global Burden of Disease (GBD) 2023 cause‑of‑death results  
IHME Results Tool: https://ghdx.healthdata.org/gbd-results-tool

Required extraction parameters are documented in:

```
docs/GBD_extraction_guide.md
```

---

## Code availability statement (manuscript-ready)

All structural metrics were computed in R (version 4.5.1). Publication figures were generated in GraphPad Prism using CSV outputs derived from the R analytical pipeline. The full analytical code and all derived datasets used to generate figures are publicly available in this repository.

---

## Data availability statement (manuscript-ready)

The study used publicly available Global Burden of Disease (GBD) 2023 cause‑of‑death estimates accessed via the IHME Results Tool. Raw GBD exports are not redistributed. All derived datasets supporting the findings of this study are available in this repository.
