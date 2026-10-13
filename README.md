# data_237

DATA 23700 group project: NASA Exoplanet Archive, Planetary Systems (PS) table.

- `data/PS_2026.10.11_20.14.11.csv`: raw download from https://exoplanetarchive.ipac.caltech.edu (2026-10-11 20:14:11). The `#` header lines describe each column.
- `initial_exploration.ipynb`: loads the data, summary statistics, missingness, and exploratory plots.
- `figures/`: plots saved by the notebook.
- `method_analysis.ipynb`: do orbital periods differ by discovery method (Transit vs. Radial Velocity) after adjusting for discovery year, distance and host-star mass? Covers a feasibility check, overlap check, stratified comparisons, regression and interactions. Figures are in `figures/method_analysis/`.
