# Time Series Forecasting System Design Projects

A portfolio of independent, production-style time-series forecasting systems
built on classical statistical and gradient-boosting methods. The projects cover
benchmark protocols, exponential smoothing and ARIMA, harmonic regression,
intermittent demand, state-space models with missing-data handling, and
conformal prediction intervals. No project uses a neural network.

Each project is its own GitHub repository with a reproducible data pipeline,
forecast evaluation on time-ordered folds, interval calibration where relevant,
and a README that records the data, split, metric, and main limitation.

## Projects

| # | Name | Dataset | Main method | Repository |
|---|------|---------|-------------|-------------|
| 1 | M4 Classical Benchmark Forecaster | M4 Forecasting Competition | Theta, ETS, and ARIMA combinations vs. naive baselines | [m4-classical-benchmark-forecaster](https://github.com/Patotricks15/m4-classical-benchmark-forecaster) |
| 2 | PJM Harmonic Regression Forecaster | Hourly Energy Consumption (PJM) | Harmonic regression with ARIMA errors | [pjm-harmonic-regression-forecaster](https://github.com/Patotricks15/pjm-harmonic-regression-forecaster) |
| 3 | Retail Intermittent Demand | Online Retail II (UCI) | Croston, SBA, and TSB | [retail-intermittent-demand-croston](https://github.com/Patotricks15/retail-intermittent-demand-croston) |
| 4 | Household Load SARIMAX Imputation | Electric Power Consumption (UCI) | SARIMAX with Kalman imputation | [household-sarimax-imputation](https://github.com/Patotricks15/household-sarimax-imputation) |
| 5 | Metro Traffic Conformal Intervals | Metro Interstate Traffic Volume | LightGBM quantile regression with split and adaptive conformal intervals | [metro-traffic-conformal-intervals](https://github.com/Patotricks15/metro-traffic-conformal-intervals) |

## Scope

This is part of a larger time-series portfolio plan with twelve projects.
Projects are added here as they are completed; each repository listed above is
self-contained and can be cloned, tested, and run independently.
