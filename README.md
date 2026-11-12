# Case-Exercise-1-Module-3
Case Exercise 1: Metocean EDA, seasonal analysis and feature engineering for Jubilee TRP3 dataset using Python.

Metocean EDA and Seasonal Analysis for Jubilee TRP3 - Exploratory data analysis, Weibull fit for Hs, Log-normal fit for Tp, Hs-Tp scatter, current rose, and feature engineering with 30+ temporal, seasonal, rolling and cumulative features.



## Case Exercise 2: Extreme Value Analysis

**Objective:** Estimate extreme significant wave height (Hs) for design return periods.
**Methods:**
1. **GEV Block Maxima Analysis** - Annual and monthly blocks on Hs data
2. **POT Analysis** - Peak-Over-Threshold with threshold selection using Mean Residual Life plot
3. **Return Level Comparison** - Compare GEV vs POT for 1, 10, 50, and 100-year return periods
4. **Return Period Plot** - With confidence intervals, compared to values in Table 3.6

**Deliverable:** Jupyter notebook with comparative analysis. Committed to Git.

**Key Outputs:**
- GEV fitted parameters (location, scale, shape)
- POT fitted parameters (threshold, scale, shape)
- 1, 10, 50, 100-year return levels from both methods


## Case Exercise 3: Metocean-Fatigue Correlation Model

**Objective:** Predict fatigue damage from metocean conditions and validate the model.
**Methods:**
1. **JONSWAP-based Spectral Fatigue Pipeline** - Built from Section 3.6
2. **Hourly Fatigue Damage** - Computed for the full year of Jubilee TRP3 data
3. **Polynomial Regression Models** - Degree 1, 2, 3 predicting fatigue from metocean features (Hs, Tp, etc.)
   - Reported R² and MAE for each model
4. **Validation** - 5-fold cross-validation, residual analysis, identification of systematic model weaknesses
5. **Dashboard** - Monthly damage accumulation, Hs vs. damage scatter, predicted vs. actual damage, cumulative damage trajectory

**Deliverables:** Jupyter notebook + correlation dataset CSV + model performance report. Committed to Git.

**Key Outputs:**
- Hourly fatigue damage time series
- Correlation dataset (metocean features vs. fatigue damage)
- Model comparison table (R², MAE, CV scores)
- Dashboard plots

