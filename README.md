<p align="center">
  <img src="./assets/profile-header.svg" width="100%" alt="Brian Lee — Quant Research and Software Engineering" />
</p>

<p align="center">
  <a href="#recent-work">Recent work</a> ·
  <a href="#research-to-production">How I build</a> ·
  <a href="#earlier-ml-work">ML work</a> ·
  <a href="#toolkit">Toolkit</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/FOCUS-Market_Microstructure-14B8A6?style=flat-square" alt="Market Microstructure" />
  <img src="https://img.shields.io/badge/FOCUS-Systematic_Trading-3B82F6?style=flat-square" alt="Systematic Trading" />
  <img src="https://img.shields.io/badge/FOCUS-Systems_Engineering-6366F1?style=flat-square" alt="Systems Engineering" />
</p>

I build quantitative trading systems, simulation engines, and machine-learning pipelines. My recent work focuses on turning ideas into **reliable system behavior**: causal data, deterministic simulation, robust validation, real-time feeds, risk controls, and observable software.

```text
hypothesis → data → model → backtest → execution → monitoring → iteration
```

## Recent work

### [PM-BTC](https://github.com/Brianlee7281/PM-BTC) · `2026.08` · latest

> Research-to-execution infrastructure for short-horizon BTC prediction markets.

| Quant research | Software engineering |
|---|---|
| Causality-safe event backtests | WebSocket market-data recorders |
| Volatility, skew, and regime signals | Post-only maker execution |
| Fill-aware strategy validation | Position recovery and risk gates |
| Tail and threshold attribution | VPS services, reports, and audits |

`Python` `asyncio` `WebSockets` `Parquet` `pytest` `Linux/systemd`

### Spit · `2026.08` · in development

> A top-down bullet-heaven roguelite built around emergent item combinations.

| Game architecture | Reliability & performance |
|---|---|
| Data-driven, priority-ordered hook system | Fixed-timestep deterministic simulation |
| Generic `Spitter` interface for players and allies | Object pools and spatial-hash collision |
| Deferred spawn and lifecycle queues | Per-frame spawn budgets and depth caps |
| Composable item behavior without item-ID branches | Headless scenarios and instrumentation |

`TypeScript` `Canvas 2D` `Vite` `Seeded RNG` `Object pooling` `Spatial hashing`

### Selected research

<table>
  <tr>
    <td width="50%" valign="top">
      <sub>2026.03 · SYSTEMATIC EQUITIES</sub><br><br>
      <b><a href="https://github.com/Brianlee7281/Systematic-Equity-Trading-System">Systematic Equity Trading System</a></b>
      <p>Regime-adaptive S&amp;P 500 system combining independent residual-momentum and mean-reversion books.</p>
      <p><b>Designed for:</b> point-in-time universes, calibrated probabilities, purged validation, and layered risk.</p>
      <code>HMM</code> <code>factor models</code> <code>cointegration</code>
    </td>
    <td width="50%" valign="top">
      <sub>2026.03 · COMPUTATIONAL FINANCE</sub><br><br>
      <b><a href="https://github.com/Brianlee7281/EPGP-Research">EPGP Research</a></b>
      <p>Reimplementation of Gaussian processes constrained by linear PDEs for heat and wave equations.</p>
      <p><b>Experiment:</b> Black–Scholes pricing through a heat-equation transformation.</p>
      <code>Gaussian processes</code> <code>PDEs</code> <code>numerics</code>
    </td>
  </tr>
</table>

## Research to production

| 01 · No silent leakage | 02 · Research ≠ execution |
|---|---|
| Point-in-time inputs, walk-forward splits, and explicit event ordering. | Signal P&amp;L and realized fill P&amp;L are measured separately. |

| 03 · Risk is a system | 04 · Make failure observable |
|---|---|
| Position limits, drawdown controls, kill conditions, and conservative sizing. | Structured logs, replayable events, audit reports, and recovery paths. |

## Earlier ML work

<details>
<summary><b>Forecasting, deep learning, and classification projects</b></summary>
<br>

| Project | Focus |
|---|---|
| [Food & Beverage Sales Forecasting](https://github.com/Brianlee7281/Food-Beverage-Outlet-Prediction) | LSTM time-series models with a 28-day lookback and 7-day forecast horizon. |
| [Power Usage — Deep Learning](https://github.com/Brianlee7281/PowerUsagePrediction-DeepLearning) | Industrial electricity forecasting with an MLP and K-Means feature engineering. |
| [Power Usage — Ensemble](https://github.com/Brianlee7281/PowerUsagePrediction) | Stacking ensemble tuned through Bayesian optimization. |
| [Loan Status Prediction](https://github.com/Brianlee7281/Loan-Status-Prediction) | K-Means + MLP classification with SMOTE imbalance handling. |
| [Student Retention Prediction](https://github.com/Brianlee7281/StudentCertificatePrediction) | Stacked classifiers with Optuna hyperparameter tuning. |
| [Korean News Classification](https://github.com/Brianlee7281/SW_news_category_classification) | Fine-tuned KoBERT news categorization. |
| [Spam URL Detection](https://github.com/Brianlee7281/spam_url_classification) | TF-IDF features with a neural-network classifier. |

</details>

## Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,pytorch,sklearn,vite,postgres,docker,aws,linux,git&theme=dark" alt="Python, TypeScript, PyTorch, scikit-learn, Vite, PostgreSQL, Docker, AWS, Linux, and Git" />
</p>

<p align="center">
  <code>time series</code> · <code>point processes</code> · <code>Monte Carlo</code> · <code>optimization</code><br>
  <code>REST / WebSocket APIs</code> · <code>streaming data</code> · <code>simulation</code> · <code>backtesting</code><br>
  <code>pytest</code> · <code>reproducible experiments</code> · <code>monitoring</code> · <code>safe defaults</code>
</p>

---

<p align="center">
  <i>Building models that can survive contact with markets.</i><br>
  <sub><a href="https://github.com/Brianlee7281">github.com/Brianlee7281</a></sub>
</p>
