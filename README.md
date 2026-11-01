<div align="center">

# Hi, I'm Brian 👋

### Data Science · Market Data · Probabilistic Modeling

Math & Philosophy @ Georgetown (CS minor)

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](#tech-stack)
[![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)](#tech-stack)
[![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](#tech-stack)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](#tech-stack)

</div>

---

## Featured

### [Ideological Distribution Dynamics in U.S. Legislatures](https://lauralintheair.github.io/Polarization/) — physics-informed inference of polarization
First author, with Francesco Caffrey, Nikki Raman, and Xin Li (Georgetown Mathematics & Statistics). Estimates the distribution of legislators' ideology over time from Voteview DW-NOMINATE (U.S. House) and Shor–McCarty (state legislatures) scores via kernel density estimation, then uses a physics-informed neural network to infer the drift and interaction kernel of a nonlinear, nonlocal Fokker–Planck equation that governs how those distributions evolve, enforcing the equation and boundary conditions through the training loss. The learned law is validated by forecasting later held-out densities without refitting. The results show polarization is not a uniform push to the extremes: attraction and repulsion coexist at different ideological distances.

📄 [Project page](https://lauralintheair.github.io/Polarization/) · 💻 [Code repository](https://github.com/LauralintheAir/Polarization)

`Python` `PyTorch` `Physics-Informed Neural Networks` `Automatic Differentiation` `Kernel Density Estimation` `NumPy` `SciPy` `Fokker–Planck` `Inverse Problems`


### [EPGP Research](https://github.com/Brianlee7281/EPGP-Research) — Gaussian processes constrained by linear PDEs
Reimplementation and extension of Ehrenpreis–Palamodov Gaussian Processes (EPGP), from undergraduate research with Prof. Bogdan Raita at Georgetown. Unlike physics-informed neural networks, which only approximately satisfy a PDE by penalizing its residual, EPGP uses the Ehrenpreis–Palamodov principle to build a Gaussian process prior directly on the solution space of a linear, constant-coefficient PDE, so every sample satisfies the equation exactly and learning reduces to fitting a small set of weights by marginal likelihood optimization. It recovers full solutions from sparse, noisy observations, validated against analytical solutions on the heat and 2D wave equations and extended to Maxwell's equations. A Black–Scholes pipeline transforms the pricing PDE into the heat equation, fits from boundary observations alone, and recovers option prices within 0.1% of the analytical solution.

`Python` `PyTorch` `Gaussian Processes` `Bayesian Inference` `Marginal Likelihood Optimization` `Kernel Methods` `NumPy` `SymPy` `PDEs`

### [Kalshi Soccer Pricing Engine](https://github.com/Brianlee7281/Kalshi_Prediction_Soccer) — calibrated in-play probabilities for soccer markets
Combines XGBoost pre-match priors with a Markov-modulated Poisson process fitted by joint likelihood, priced through hybrid analytic and Monte Carlo methods. Includes event replay and probability calibration against realized outcomes.
`Python` `XGBoost` `PyTorch` `Numba` `Monte Carlo`


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
| **Machine Learning** | scikit-learn, XGBoost, Optuna, Gaussian Processes, Bayesian inference, kernel density estimation, Hidden Markov Models, Monte Carlo |
| **Deep Learning** | PyTorch, physics-informed neural networks, automatic differentiation, LSTM, MLP, CNNs (VGG-19), Transformers (KoBERT) |
| **Scientific Computing** | NumPy, SciPy, SymPy, Numba, PDE solvers |
| **Engineering** | pytest, Git, Docker, Linux/systemd, C++20, TypeScript |
