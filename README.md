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

### OrbitFall · `2026` · in development

> A geometry-driven, top-down survivors-like where orbiting weapon nodes form links and fields—and the geometry itself becomes the weapon.

- Built in **C++20** with **SDL3**, CMake, ImGui, and data-driven JSON configuration
- Generic combat graph composed of nodes, ports, edges, cycles, and fields
- Deterministic fixed-step simulation with bounded pools and spatial-hash collision
- Ordered event, reaction, effect-intent, and resolution pipelines
- Graph-aware build construction with modular motion, trigger, payload, and geometry components
- Dedicated parity, determinism, soak, allocation, combat, and visual-state tests

`C++20` `SDL3` `CMake` `Catch2` `ImGui` `Deterministic simulation`

### Spit · `2026` · in development

> A top-down bullet-heaven roguelite built around item combinations that create emergent, screen-breaking behavior.

- TypeScript/Canvas 2D implementation without a game engine
- Data-driven, priority-ordered hook system for composable item behavior
- Shared `Spitter` interface for players, converted enemies, allies, and future clones
- Seeded fixed-timestep simulation with deferred spawn and lifecycle queues
- Object pooling, spatial hashing, recursive-depth caps, and per-frame spawn budgets
- Headless deterministic scenarios and permanent runtime instrumentation

`TypeScript` `Canvas 2D` `Vite` `Seeded RNG` `Object pooling` `Spatial hashing`

## Trading & Quantitative Projects

| Project | Description |
|---|---|
| [PM-BTC](https://github.com/Brianlee7281/PM-BTC) | Research-to-execution system for short-horizon BTC markets. Includes causal event backtests, streaming market-data recorders, volatility/skew/regime signals, post-only execution, risk gates, recovery paths, VPS services, and execution-quality audits. |
| [Systematic Equity Trading System](https://github.com/Brianlee7281/Systematic-Equity-Trading-System) | Multi-strategy equity system combining residual momentum and mean reversion with HMM + XGBoost regime detection across a layered research, capital-allocation, portfolio-risk, and validation architecture. |
| [EPGP Research](https://github.com/Brianlee7281/EPGP-Research) | Reimplementation of Gaussian processes constrained by linear PDEs, including heat/wave experiments and a Black–Scholes-to-heat-equation pricing pipeline. |

### Research and engineering themes

`point-in-time data` · `walk-forward validation` · `market microstructure` · `Monte Carlo` · `factor models` · `cointegration` · `execution systems` · `portfolio risk`

## Machine Learning & Deep Learning Projects

| Project | Description |
|---|---|
| [Food & Beverage Sales Forecasting](https://github.com/Brianlee7281/Food-Beverage-Outlet-Prediction) | LSTM-based time-series forecasting with individualized models per store-menu combination. Uses a 28-day lookback to predict 7 days ahead. |
| [Power Usage Prediction — Deep Learning](https://github.com/Brianlee7281/PowerUsagePrediction-DeepLearning) | Industrial electricity forecasting using a 5-layer MLP with K-Means feature engineering and learning-rate scheduling. |
| [Power Usage Prediction](https://github.com/Brianlee7281/PowerUsagePrediction) | Electricity-consumption forecasting with a stacking ensemble of Decision Tree, KNN, and Huber Regressor models tuned through Bayesian optimization. |
| [Loan Status Prediction](https://github.com/Brianlee7281/Loan-Status-Prediction) | Hybrid K-Means + MLP pipeline for loan-approval prediction with SMOTE-based class-imbalance handling. |
| [Student Retention Prediction](https://github.com/Brianlee7281/StudentCertificatePrediction) | Stacking classifier using Naive Bayes, Decision Tree, and XGBoost with Optuna hyperparameter tuning to identify at-risk students. |
| [Korean News Classification](https://github.com/Brianlee7281/SW_news_category_classification) | Fine-tuned KoBERT model for categorizing Korean news articles from titles and keywords. |
| [Spam URL Detection](https://github.com/Brianlee7281/spam_url_classification) | Malicious-URL classifier using TF-IDF feature extraction and a deep neural network with early stopping. |

### Modeling themes

`time-series forecasting` · `deep learning` · `ensemble learning` · `NLP` · `feature engineering` · `class imbalance` · `Bayesian optimization` · `model evaluation`

## Tech Stack

**Languages:** Python, C++20, TypeScript, JavaScript, SQL

**Game & Simulation:** SDL3, Canvas 2D, CMake, ImGui, Catch2, fixed-timestep simulation, object pooling, spatial hashing

**Trading & Research:** pandas, NumPy, PyTorch, XGBoost, Hidden Markov Models, Gaussian Processes, Monte Carlo, Parquet

**ML / DL:** scikit-learn, PyCaret, Optuna, Transformers (KoBERT), LSTM, MLP, ensemble methods

**Systems:** REST APIs, WebSockets, asyncio, pytest, Docker, Linux/systemd, PostgreSQL, Git

---

<div align="center">

*Building systems where models, simulation, and software meet.*

</div>
