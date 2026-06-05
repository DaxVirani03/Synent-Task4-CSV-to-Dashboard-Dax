# Dax Virani - Dashboard

Objective
- Provide an interactive, notebook-based dashboard that summarizes key metrics and visualizations from the original `dasboard.py`.

Steps performed
- Load and validate source data
- Compute summary KPIs and aggregated tables
- Create visualizations (time series, category breakdowns, interactive charts)
- Add notes and execution cells for reproducibility

Tools / Libraries
- pandas, numpy, matplotlib, seaborn, plotly

Outcome (brief)
- Notebook generates dashboard panels, summary tables, and exportable charts to help stakeholders review trends quickly.

How to run

```bash
pip install -r requirements.txt
jupyter lab
# or execute and save outputs
jupyter nbconvert --to notebook --execute "Dax Virani - dashboard.ipynb" --inplace
```

Notes
- Ensure any referenced CSVs are placed in the workspace (paths are relative).
- Author: Dax Virani
