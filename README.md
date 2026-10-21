# TfL Passenger Footfall Forecasting — Reproducibility Repository

Study: **Multi-Horizon Temporal Demand Representation for Explainable Passenger-Footfall Forecasting and Public-Transport Scheduling Support**

This repository should contain the exact analysis scripts, dependency specification, figures, and compact result tables used for the manuscript. Raw datasets, local environments, IDE configuration, secrets, and unrelated files are excluded by default.



## Forecast protocol

The reported evaluation uses lagged and rolling predictors derived from previously observed footfall. Describe it as rolling one-step-ahead only under the assumption that those observations are available before each prediction is issued. Do not describe it as fixed-origin long-horizon forecasting without a separate experiment.

The manuscript's baseline model comparison and station-level feature-group ablation are distinct experiments; their metrics must not be silently merged.

