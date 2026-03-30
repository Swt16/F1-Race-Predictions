# F1-Race-Predictions

This project utilizes multivariate regression analysis to decode the factors that determine a driver's points finish in modern Formula 1. By segmenting data based on pit-stop strategies, the model identifies how variables like starting grid position, fastest lap consistency, and tire management impact final race results.

## Analysis Notebooks
* **[Strategy: 1-2 Stop Races]** — Focused on high-efficiency, low-wear circuits.
* **[Strategy: 2-3 Stop Races]** — Focused on high-degradation tracks requiring aggressive pit management.

---

## Key Findings
* **Grid Position Correlation:** Quantified the exact "premium" a front-row start provides versus mid-pack volatility.
* **Pit Stop Optimization:** Analyzed the point-return on varying stop strategies, identifying the threshold where an extra stop for fresh tires outweighs the time lost in the pit lane.
* **Predictive Accuracy:** Achieved a **Test RMSE of ~2.94** for 1-2 stop strategies and **~3.16** for 2-3 stop strategies, highlighting the increased unpredictability in high-degradation races.

## Technical Stack
* **Statistical Modeling:** `Statsmodels` (OLS Regression), `Scikit-Learn` (Linear Regression)
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Seaborn`, `Matplotlib` (Heatmaps and Residual Plots)

## Repository Structure
* `/notebooks`: Contains regression analyses for different race strategy segments.
* `/data`: F1 driver performance data (2022-2025).
* `MSIS 510 - Formula 1 Championship Prediction.pdf`: Comprehensive breakdown of statistical significance and p-values for race variables.

## Data Source
Data was synthesized from historical F1 race results (2022-2025), focusing on driver standings, pit data, and qualifying metrics.

## License
This project is licensed under the MIT License.
