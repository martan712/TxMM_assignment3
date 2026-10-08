# Assignment 3 — Authorship attribution

Given 20 authors in PAN2020 dataset, predict who wrote a fanfiction snippet, using 150 hand-crafted features and a linear SVC. The final model reaches a macro-F1 of 0.944 on the test set.

## Repository Structure

- `src/` — data loading, feature extraction, model, evaluation and ablation
- `attribution.ipynb` — full pipeline: training, tuning, test run and ablation
- `failure_analysis.ipynb` — analysis of the test-set mistakes
- `outputs/` — figures and result tables
- `report/` — LaTeX source and PDF of the report

## Running

```
uv sync
```

Then run `the notebooks.
