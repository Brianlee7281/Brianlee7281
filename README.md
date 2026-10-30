<div align="center">

# Hi, I'm Brian 👋

### Data Science · Market Data · Probabilistic Modeling

Math & Philosophy @ Georgetown (CS minor). I work on the unglamorous half of quantitative research: collecting messy real-world data, making it causal and trustworthy, and only then asking a model what it says.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](#tech-stack)
[![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)](#tech-stack)
[![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](#tech-stack)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](#tech-stack)

</div>

---

## Featured

### [Kalshi Soccer Pricing Engine](https://github.com/Brianlee7281/Kalshi_Prediction_Soccer) — calibrated in-play probabilities for soccer markets
Combines XGBoost pre-match priors with a Markov-modulated Poisson process fitted by joint likelihood, priced through hybrid analytic and Monte Carlo methods. Includes event replay and probability calibration against realized outcomes.
`Python` `XGBoost` `PyTorch` `Numba` `Monte Carlo`

### [EPGP Research](https://github.com/Brianlee7281/EPGP-Research) — Gaussian processes constrained by linear PDEs
Learns PDE solutions from sparse, noisy observations with Gaussian processes whose samples satisfy the equation exactly. Heat and wave experiments, plus a Black–Scholes-to-heat-equation pipeline that recovers option prices from boundary data alone.
`Python` `Gaussian Processes` `PDEs` `Numerics`

## Machine Learning

| Project | Description | Stack |
|---|---|---|
| [Sales Forecasting](https://github.com/Brianlee7281/Food-Beverage-Outlet-Prediction) | Per store-and-menu LSTM forecasting, predicting 7 days ahead from a 28-day lookback. | `LSTM` `Time Series` |
| [Electricity Demand Forecasting](https://github.com/Brianlee7281/PowerUsagePrediction) | Industrial power forecasting comparing a stacking ensemble tuned with Bayesian optimization against a deep MLP ([DL version](https://github.com/Brianlee7281/PowerUsagePrediction-DeepLearning)). | `scikit-learn` `MLP` `Bayesian Opt.` |
| [Student Retention](https://github.com/Brianlee7281/StudentCertificatePrediction) | Stacked Naive Bayes, Decision Tree, and XGBoost classifier with Optuna tuning to identify at-risk students. | `XGBoost` `Optuna` |
| [Korean News Classification](https://github.com/Brianlee7281/SW_news_category_classification) | Fine-tuned KoBERT to categorize news articles from titles and keywords. | `KoBERT` `NLP` |

## Also building

Simulation-heavy games in C++20 and TypeScript, built around deterministic fixed-step simulation, seeded scenarios, and extensive parity and soak testing: **OrbitFall** (`C++20` `SDL3` `Catch2`) and **Spit** (`TypeScript` `Canvas 2D`).

## Tech Stack

| Category | Technologies |
|---|---|
| **Data** | pandas, NumPy, SQL / PostgreSQL, Parquet, WebSockets, asyncio |
| **Modeling** | scikit-learn, XGBoost, PyTorch, Gaussian Processes, Hidden Markov Models, Monte Carlo, Optuna |
| **Engineering** | pytest, Git, Docker, Linux/systemd, C++20, TypeScript |
