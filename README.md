# EUROGREEN-Japan: Stock-Flow Consistent Model for Japan's Net-Zero Pathways

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## Overview

Stock-Flow Consistent (SFC) macroeconomic model for Japan, inspired by EUROGREEN (D'Alessandro et al., 2020). Integrates environmental, economic, and distributional dimensions to evaluate Japan's net-zero pathways by 2050.

**Target Journal**: Ecological Economics
**Date**: January 2026

## Key Features

- 23-equation hybrid SFC model
- Endogenous finance with credit constraints
- 4 policy scenarios (BAU, Green Growth, Degrowth)
- Complete dataset 1994-2023 (91 variables)

## Quick Start
```bash
# Install dependencies
pip install -r requirements.txt

# Run analysis
jupyter notebook notebooks/01_data_preparation.ipynb
```

## Key Results

| Scenario | GDP 2050 | CO₂ Reduction | Debt/GDP |
|----------|----------|---------------|----------|
| BAU | -5% | 26% | 545% |
| Moderate Green | +2% | 42% | 536% |
| Ambitious Green | **+6%** | **48%** | **531%** |
| Degrowth | -3% | **61%** | 420% |

## Novel Findings

1. **Fiscal Sustainability Paradox**: Green growth → better debt ratios
2. **Pareto-Optimal**: Ambitious green dominates on all dimensions
3. **Feasible Degrowth**: With fiscal reforms, degrowth is sustainable

## Repository Structure
```
EUROGREEN-Japan/
├── README.md
├── requirements.txt
├── data/raw/              # Place df_eurogreen_japan_complete.csv here
├── notebooks/             # Jupyter analysis notebooks
├── src/                   # Python model code
└── results/              # Outputs
```

See EXECUTION_GUIDE.md for detailed workflow.
