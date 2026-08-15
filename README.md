<div align="center">

# Hi, I'm Brian 👋

### Trading Systems · Game Development · Machine Learning

I build quantitative trading infrastructure, simulation-heavy games, and machine-learning pipelines—with an emphasis on robust systems, reproducible experiments, and models that work outside a notebook.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](#tech-stack)
[![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)](#tech-stack)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](#tech-stack)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](#tech-stack)

</div>

---

## C++ & Game Development

| Project | Description | Stack |
|---|---|---|
| **OrbitFall** | Geometry-driven, top-down survivors-like where orbiting weapon nodes form links and fields. Built around a generic combat graph, modular construction system, deterministic fixed-step simulation, bounded pools, ordered reaction/effect pipelines, and extensive parity, soak, allocation, and combat tests. | `C++20` `SDL3` `CMake` `Catch2` `ImGui` |
| **Spit** | Top-down bullet-heaven roguelite built around emergent item combinations. Uses priority-ordered hooks, a shared `Spitter` interface, seeded simulation, deferred lifecycle queues, object pooling, spatial hashing, recursive-depth caps, and headless deterministic scenarios. | `TypeScript` `Canvas 2D` `Vite` `Seeded RNG` |

## Trading & Quantitative Projects

| Project | Description | Stack |
|---|---|---|
| [PM-BTC](https://github.com/Brianlee7281/PM-BTC) | Research-to-execution system for short-horizon BTC markets. Includes causal event backtests, streaming market-data recorders, volatility/skew/regime signals, post-only execution, risk gates, recovery paths, VPS services, and execution-quality audits. | `Python` `WebSockets` `Parquet` `pytest` `systemd` |
| [Kalshi Soccer Trading Engine](https://github.com/Brianlee7281/Kalshi_Prediction_Soccer) | Real-time soccer prediction-market pricing engine combining XGBoost match priors with a Markov-Modulated Poisson Process, joint likelihood estimation, hybrid analytic/Monte Carlo pricing, event replay, calibration, and position sizing. | `Python` `PyTorch` `XGBoost` `Numba` `Monte Carlo` |
| [EPGP Research](https://github.com/Brianlee7281/EPGP-Research) | Reimplementation of Gaussian processes constrained by linear PDEs, including heat/wave experiments and a Black–Scholes-to-heat-equation pricing pipeline. | `Python` `Gaussian Processes` `PDEs` `Numerics` |

## Machine Learning & Deep Learning Projects

| Project | Description | Stack |
|---|---|---|
| [Food & Beverage Sales Forecasting](https://github.com/Brianlee7281/Food-Beverage-Outlet-Prediction) | LSTM-based time-series forecasting with individualized models per store-menu combination. Uses a 28-day lookback to predict 7 days ahead. | `Python` `LSTM` `Time Series` |
| [Power Usage Prediction — Deep Learning](https://github.com/Brianlee7281/PowerUsagePrediction-DeepLearning) | Industrial electricity forecasting using a 5-layer MLP with K-Means feature engineering and learning-rate scheduling. | `Python` `MLP` `K-Means` |
| [Power Usage Prediction](https://github.com/Brianlee7281/PowerUsagePrediction) | Electricity-consumption forecasting with a stacking ensemble of Decision Tree, KNN, and Huber Regressor models tuned through Bayesian optimization. | `scikit-learn` `Ensemble` `Bayesian Optimization` |
| [Loan Status Prediction](https://github.com/Brianlee7281/Loan-Status-Prediction) | Hybrid K-Means + MLP pipeline for loan-approval prediction with SMOTE-based class-imbalance handling. | `Python` `MLP` `SMOTE` `Clustering` |
| [Student Retention Prediction](https://github.com/Brianlee7281/StudentCertificatePrediction) | Stacking classifier using Naive Bayes, Decision Tree, and XGBoost with Optuna hyperparameter tuning to identify at-risk students. | `XGBoost` `Optuna` `Stacking` |
| [Korean News Classification](https://github.com/Brianlee7281/SW_news_category_classification) | Fine-tuned KoBERT model for categorizing Korean news articles from titles and keywords. | `KoBERT` `Transformers` `NLP` |
| [Spam URL Detection](https://github.com/Brianlee7281/spam_url_classification) | Malicious-URL classifier using TF-IDF feature extraction and a deep neural network with early stopping. | `TF-IDF` `Deep Learning` `Classification` |

## Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python, C++20, TypeScript, JavaScript, SQL |
| **Game & Simulation** | SDL3, Canvas 2D, CMake, ImGui, Catch2, fixed-timestep simulation, object pooling, spatial hashing |
| **Trading & Research** | pandas, NumPy, PyTorch, XGBoost, Hidden Markov Models, Gaussian Processes, Monte Carlo, Parquet |
| **ML / DL** | scikit-learn, PyCaret, Optuna, Transformers (KoBERT), LSTM, MLP, ensemble methods |
| **Systems** | REST APIs, WebSockets, asyncio, pytest, Docker, Linux/systemd, PostgreSQL, Git |

---

<div align="center">

*Building systems where models, simulation, and software meet.*

</div>
