# F1 Championship Predictor: Strategy & Performance Analytics
**A multivariate regression suite predicting the 2025 World Championship outcomes.**

## Project Overview
Formula 1 is a high-stakes environment where teams spend between $100M–$400M annually. This project uses statistical modeling to predict race outcomes and championship standings. By analyzing historical data (2022-2025) and segmenting races by pit-stop strategy, we quantified the variables that translate to podium finishes and constructor points.

## Interactive Analysis
* **[Notebook: 1-2 Stop Strategy]** — High-efficiency race modeling.
* **[Notebook: 2-3 Stop Strategy]** — High-degradation race modeling.
* [View Presentation Slides](https://github.com/Swt16/F1-Race-Predictions/blob/main/MSIS%20510%20-%20Formula%201%20Championship%20Prediction.pdf) — *Includes 2025 Title Predictions.*

---

## Key Insights & Results
* **The "Strategy Gap":** Our model identified a distinct performance variance between low-stop and high-stop races, achieving a **Test RMSE of 2.94** for optimized 1-2 stop strategies.
* **Championship Prediction:** Based on current telemetry and regression results, the model successfully forecasted a tight title race between Lando Norris and Max Verstappen, with **McLaren** clinching the Constructor’s Championship.
* **Feature Importance:** Quantified the impact of starting grid position versus mid-race pace, providing a statistical look at "track position" value.

## Technical Stack
* **Modeling:** `Statsmodels` (OLS Regression), `Scikit-Learn` (Linear Regression)
* **Data Engineering:** `Pandas`, `NumPy`
* **Visualization:** `Seaborn` (Heatmaps, Residual Plots)
* **Data Source:** `Fast F1` Python package & historical race results.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
