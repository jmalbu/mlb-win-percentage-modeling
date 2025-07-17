# Data Folder – MLB Win Percentage Modeling

This folder contains all datasets and supporting documentation used in the MLB win percentage modeling project (1974–2024).

---

## Files

| Filename | Description |
|----------|-------------|
| `baseball-data-normalized.csv` | Version of the dataset with normalized numeric features, used for machine learning models and time series forecasting. |
| `baseball-data.csv` | Raw dataset of team-level statistics for all 30 MLB teams from 1974 to 2024. Includes batting, pitching, and performance metrics. |
| `data-dictionary.md` | Human-readable dictionary describing each variable in narrative, grouped format (with formulas and context). |
| `variable-summary-table.md` | Table-style summary of all variables with types and concise descriptions, designed for quick reference and modeling prep. |

---

## Data Overview

- **Observations**: 1 row per team-season (e.g., 2021 Yankees)
- **Coverage**: 30 MLB teams, 1974–2024 (≈1,500 rows)

## Notes

- Adjusted metrics like `OPS+` and `ERA+` are normalized to league and park factors for cross-season comparison.
- The normalized CSV was created using feature scaling (z-score) across the continuous variables to improve model convergence and interpretability.

## Data Source

- Data was retrieved from [Baseball Reference](https://www.baseball-reference.com/) using **StatHead**, a comprehensive database of baseball history that includes every player, team, season, league, award, record, and score dating back to 1871.
---

 See the main [`README.md`](../README.md) for full project context.
