# Archive

This folder contains exploratory and intermediate notebooks created during the development of the MLB Win Percentage Modeling project.

These files document the experimentation, iteration, and learning process. While not part of the final streamlined pipeline, they offer transparency into how the modeling approaches evolved over time and may serve as useful references for future work.

## Contents

### `linear-regression.ipynb`
- Full exploratory workflow for building regression models
- Includes manual variable selection, Lasso, Ridge, Elastic Net, and OLS
- Useful for understanding the feature engineering and trial-and-error process

### `time-series.ipynb`
- Initial SARIMAX modeling experiments
- Includes team-by-team stationarity checks and iterative model testing
- Reflects raw development work and multiple exploratory directions

### 🧪 `time-series-2.ipynb`
- Quick prototype to test 80/20 train-test split for time series models
- Evaluates SARIMAX forecasting accuracy across all MLB teams

---

**Note**: These notebooks are not maintained and may contain deprecated code, unused functions, or incomplete tests. For the finalized models and documentation, refer to:
- `linear-regression-final.ipynb`
- `time-series-final.ipynb`
