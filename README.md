# Clay-Algae_Dynamics_Data
Repository for submission to journal Harmful Algae

Submitted to *Harmful Algae*.

## Overview

This repository contains the data and code used to reproduce the analyses and figures presented in the manuscript.

## Repository structure

```
data/
    raw/            # Original data
    processed/      # Processed datasets used for analysis

notebooks/
    HAB_publication_figures.ipynb


README.md
requirements.txt
```

## Requirements

- Python 3.x
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from scipy import stats
from scipy.stats import linregress


## Data

Raw data are located in `data/raw/`.
Save all raw data to same folder as notebook to properly generate figures.

Processed datasets used to generate the figures are located in `data/processed/`.

## Citation

If you use this repository, please cite: TBD
