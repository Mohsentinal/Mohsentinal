# Mohsen Moghaddam

Computer Engineering student in Istanbul, focused on systematic trading, market-data infrastructure, and quant developer tooling.

I build trading research and data infrastructure projects around exchange data, order books, backtesting, validation, monitoring, and execution-aware analysis. My main private project is **FinSentinal**, a MetaTrader 5 systematic trading system developed over 13+ months. My public repositories show the engineering layers behind that work: async data ingestion, C++ order-book replay, microstructure features, leakage-aware validation, and backtest/live consistency auditing.

Currently finishing my B.Sc. in Computer Engineering with a 3.71 GPA and looking for junior quant developer / systematic trading engineering roles in Europe.

---

## Selected Quant Engineering Projects

### exchange-data-ops-lab
Async Python market-data engineering project for exchange-level research infrastructure.

Built a pipeline with Binance public WebSocket ingestion, deterministic offline simulation, SQLite market-event storage, microstructure feature generation, data-quality checks, Prometheus/Grafana-ready metrics, bootstrap confidence intervals, and PnL attribution.

**Signals:** Python, asyncio, exchange APIs, SQL, market data, monitoring, statistical edge validation  
**Repo:** https://github.com/Mohsentinal/exchange-data-ops-lab

---

### lob-replay-engine
C++20 limit-order-book replay engine for deterministic L2 market-data reconstruction.

Includes fixed-point price handling, bid/ask book reconstruction, invariant checks, CSV summary/snapshot exports, deterministic checksum, CMake build, unit tests, GitHub Actions CI, and throughput benchmarking above 1.6M events/sec on local test data.

**Signals:** C++, CMake, order books, market microstructure, systems engineering, benchmarking  
**Repo:** https://github.com/Mohsentinal/lob-replay-engine

---

### alpha-exec-stack
End-to-end microstructure research pipeline on Binance BTCUSDT.

Covers WebSocket ingestion, 200ms feature engineering, GBM labels, maker/taker evaluation, execution-aware costs, and reproducible research outputs.

**Signals:** Python, Polars, market microstructure, feature engineering, execution-aware evaluation  
**Repo:** https://github.com/Mohsentinal/alpha-exec-stack

---

### wfv-toolkit
Walk-forward validation toolkit with purge/embargo support for time-series machine learning.

Built because standard cross-validation can leak information in financial datasets. Includes leakage-aware split utilities and validation helpers.

**Signals:** time-series validation, leakage control, financial ML methodology  
**Install:** `pip install wfvkit`  
**Repo:** https://github.com/Mohsentinal/wfv-toolkit

---

### consistency-auditor
CLI tool for auditing backtest vs live trading trade-list consistency.

Compares CSV trade logs, detects drift, slippage, execution mismatches, and consistency issues before they compound.

**Signals:** trading-system auditing, backtest/live parity, CLI tooling, reports  
**Repo:** https://github.com/Mohsentinal/consistency-auditor

---

## Main Technical Areas

**Languages:** Python, C++, SQL  
**Trading / Quant:** market data, order books, microstructure, backtesting, walk-forward validation, execution metrics, risk controls  
**Data / Infrastructure:** asyncio, WebSockets, SQLite, Prometheus-style metrics, Grafana-ready dashboards, CSV/Parquet workflows  
**Engineering:** Git, GitHub Actions, CI, CMake, Docker, Makefile, testing, reproducible releases  
**Python stack:** pandas, NumPy, Polars, scikit-learn, MetaTrader5, ccxt  

---

## Current Focus

I am building toward junior quant developer and systematic trading engineering roles by strengthening public proof in:

- exchange-level market-data ingestion
- order-book and microstructure systems
- SQL/time-series data workflows
- statistical edge validation
- monitoring and data-quality checks
- reproducible CI/release workflows

---

## Contact

LinkedIn: https://www.linkedin.com/in/mohsentinal  
Website: https://finsentinal.com  
Email: mohsentinal@gmail.com
