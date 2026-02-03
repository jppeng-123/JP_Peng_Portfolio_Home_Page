JP Peng
Quantitative Research & Systematic Trading Portfolio
Overview

This repository hosts my professional portfolio site and serves as a structured archive of my quantitative research, portfolio analytics, and systematic strategy development work.

My work focuses on building production-grade research and trading pipelines that convert statistical evidence into deployable investment decisions. The emphasis is consistently on:

robustness

interpretability

realistic execution

risk control

rather than optimizing backtest performance.

The projects presented here reflect a disciplined research workflow:

data engineering → modeling → validation → risk control → deployment readiness

Live site:
https://jppeng-123.github.io/

Research Philosophy

Markets reward process consistency, not clever ideas.

My research principles:

Statistical validity over in-sample performance

Out-of-sample robustness over complexity

Risk control over raw return maximization

All strategies follow an institutional workflow:

Walk-forward training · strict holdout · cross-sectional neutralization · transaction cost modeling · realistic liquidity constraints

Objective:
Build strategies that remain stable under real market conditions, not only in historical simulations.

Core Research Domains
Systematic Equity & Factor Research

Design and validation of cross-sectional alpha signals with strict inference standards.

Methods:

Information Coefficient screening

Regularization (LASSO / Ridge)

Factor stability diagnostics

Barra-style risk neutralization

Walk-forward backtesting

Newey-West HAC inference for statistical significance

Focus:

stable signals

low turnover

deployable exposures

minimized overfitting risk

Volatility & Risk Modeling

Construction of forward-looking risk and uncertainty engines.

Methods:

GARCH / EGARCH volatility forecasting

Hidden Markov Models for regime detection

Monte Carlo scenario simulation

Value-at-Risk / Expected Shortfall estimation

Tail event stress testing

Focus:

distribution shape awareness

regime sensitivity

drawdown control

risk budgeting

Portfolio Construction & Optimization

Implementation of practical portfolio engineering frameworks.

Methods:

Softmax weighting

Risk parity / exposure balancing

PCA factor decomposition

Transaction cost modeling

Liquidity and execution filters

Focus:

capital efficiency

stable turnover

realistic execution assumptions

scalable deployment

Recent Development Focus
Walk-Forward Genetic Algorithm Factor Mining Platform

Recent work centers on building an industry-grade automated alpha discovery engine designed for robust out-of-sample deployment.

Framework highlights:

Rolling walk-forward training schedule (multi-year lookback)

Strict holdout evaluation

Time-ordered train/validation splits with purge gaps

LASSO pre-selection of candidate terminals

Genetic Programming / GA symbolic factor generation

Complexity penalties to avoid overfitting

Barra-style neutralization

Newey-West t-stat inference on daily IC

Daily rolling backtests with transaction costs

Purpose:

Transform factor discovery from manual experimentation into a repeatable, statistically disciplined research pipeline.

This project reflects how I approach systematic research at scale:
automation, reproducibility, and institutional standards.

Technical Stack
Programming

Python
NumPy · Pandas · Numba · scikit-learn · statsmodels · matplotlib

Quant Infrastructure

Bloomberg · SQL · data pipelines · large-scale backtesting systems

Methods

Time-series modeling · cross-sectional econometrics · machine learning · stochastic simulation · optimization

What This Portfolio Demonstrates

This site is not a collection of academic notebooks.

It demonstrates:

how I structure quantitative research

how I validate hypotheses rigorously

how I control overfitting

how I model execution reality

how I prepare strategies for live trading environments

The goal is to communicate both technical depth and professional rigor.

Contact

For collaboration or opportunities in quantitative research, systematic trading, or risk analytics:

Email
jinjia.peng1122@gmail.com

GitHub
https://github.com/jppeng-123

LinkedIn
https://www.linkedin.com/in/jinjiapeng/
