# COVID-19 India Time-Series Analysis

This repo is about Alpha stable PAR model for time series forcasting. Analysis before the choosing model supports the choice of the model, which has been described in other files.

## Structure

```text
01_introduction_and_workflow.ipynb
02_decomposition.ipynb
03_stationarity_and_cyclostationarity.ipynb
04_heavy_tail_hill_analysis.ipynb
05_par_classical_yule_walker.ipynb
06_par_ncv.ipynb
07_par_floc.ipynb
08_model_comparison.ipynb
README.md
requirements.txt
.gitignore
```

## Execution order
Run `01` through `08` in order. `02_decomposition.ipynb` creates `data/residual_series.csv`; that derived file is ignored by Git.

## Dataset
The original dataset is not committed. Download `owid-covid-data.csv` from Kaggle: https://www.kaggle.com/datasets/bolkonsky/covid19

Place it in the working directory before running `02_decomposition.ipynb`.

## Installation
```bash
pip install -r requirements.txt
jupyter notebook
```

The analogies are for intuition only; the mathematical definitions and executed notebook code are the authoritative analysis.
