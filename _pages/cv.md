---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Ph.D. in Management, Computational Social Science, **Zhejiang University**, 2023–present (expected Jun 2028).  
  Research interests: financial time-series modeling, deep learning forecasting, multi-agent quantitative trading systems, and interpretable financial AI.

* B.Eng. in Automation, Control Science and Engineering, **Harbin Institute of Technology**, 2019–2023.  
  Honors Bachelor Degree, HIT Elite College; First-Class Scholarship; National Second Prize, China Undergraduate Mathematical Contest in Modeling.

Publication
======

* *Exchange Rate Forecasting with Multi-scale Residual LSTM and Dual-task Learning*.  
  **Expert Systems with Applications**, 2026. SCI Q1 / Top Journal.  
  - Proposed a multi-scale residual LSTM with dual-task learning framework for exchange-rate forecasting and extreme-movement detection.  
  - Integrated macroeconomic variables and SHAP-based explainability to improve both predictive performance and interpretability.  
  - Evaluated the model on CNY, JPY, KRW, EUR, and GBP; achieved ROC-AUC = 0.8516–0.9221 for extreme-movement classification on volatile currencies.

Experience
======

* **Hangzhou Nizhiyou Information Technology Co., Ltd.** — Quantitative Strategy Research & System Development, *Dec 2025–May 2026*  
  - Developed a deep-learning-based research framework for CTA and futures strategies, covering market data processing, feature engineering, model training, signal generation, and backtesting evaluation.  
  - Built an automated grid-trading system with configurable strategy parameters, market data ingestion, automatic order execution, position management, take-profit/stop-loss logic, and risk controls.  
  - Incorporated futures-specific constraints into backtesting, including margin requirements, commissions, slippage, contract multipliers, and minimum tick sizes.

* **Shibei Investment Co., Ltd.** — Quantitative Strategy Research Intern, Deep Learning, *Sep 2024–Dec 2024*  
  - Conducted research on equity return prediction and quantitative factor modeling, with experiments on multi-factor inputs, deep learning architectures, and training schemes.  
  - Built a factor feature-engineering and model-evaluation pipeline to compare the impact of different factor combinations and learning algorithms on return prediction, risk exposure, and portfolio performance.

Skills
======

* **Quantitative Research:** CTA strategies, futures backtesting, financial time-series forecasting, factor modeling, grid trading, portfolio risk control, slippage and transaction-cost modeling.  
* **Programming & Engineering:** Python, PyTorch, NumPy, pandas, scikit-learn, SQL, C/C++, Shell, Git, Linux, LaTeX.  
* **AI & Agents:** LSTM, TCN, Transformer, multi-task learning, reinforcement learning, multi-agent systems, LLM agents, Agent Runtime, SHAP explainability.  
* **Tools & Workflow:** Git, Linux, LaTeX, Markdown, data preprocessing pipelines, backtesting frameworks, and event-driven system design.

Selected Projects
======

* **Multi-Agent Quantitative Trading Model System** — Zhejiang University  
  - Designed a multi-agent trading system that decomposes the trading workflow into market perception, strategy routing, strategy execution, risk approval, simulated execution, and feedback learning agents.  
  - Built a lightweight Agent Runtime supporting agent registration, topic-based scheduling, unified message structures, execution logs, and trace replay.  
  - Encapsulated trading strategies as Capsule Agents and used a Strategy Routing Agent to dynamically select strategies based on market states, strategy scores, and exploration weights.

* **Multi-Agent Arbitrage Model for Polymarket Prediction Markets** — Zhejiang University  
  - Designed a multi-agent quantitative architecture for Polymarket prediction markets, covering event discovery, order-book perception, probability estimation, strategy routing, risk approval, and simulated execution.  
  - Constructed a Probability State representation including market-implied probability, internal fair probability, edge, confidence, and time-to-resolution to identify mispricing opportunities.  
  - Designed strategy capsules such as Binary Parity, Multi-outcome Consistency, and Probability Value, with liquidity, rule-uncertainty, and event-correlation risk controls.

* **Multi-scale Residual LSTM for Exchange Rate Forecasting** — Zhejiang University  
  - Developed a multi-scale residual LSTM framework to capture both short-term fluctuations and long-term trends in exchange-rate time series.  
  - Formulated volatile-currency forecasting as a dual-task learning problem, jointly modeling return regression and extreme-movement classification.  
  - Applied SHAP analysis to quantify the contribution of macroeconomic variables and improve the interpretability of financial forecasting models.

Awards & Honors
======

* National Second Prize, China Undergraduate Mathematical Contest in Modeling. (2021)  
* Honors Bachelor Degree, HIT Elite College. (2023)  
* First-Class Scholarship, HIT Elite College. (2023)