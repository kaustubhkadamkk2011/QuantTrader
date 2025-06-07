# QuantTrader

A modular, ML-powered quantitative trading bot for Indian equities (NSE), featuring ensemble strategies, risk management, and both backtesting and live trading support.

## Tech Stack

- Python 3.9+
- backtrader
- ta (pure Python technical analysis library)
- nsepy
- smartapi-python (Angel One)
- xgboost
- python-telegram-bot

## Project Structure

- `core/`        – Core logic and utilities
- `strategies/`  – Individual trading strategy modules
- `ml/`          – Machine learning models and scripts
- `backtest/`    – Backtesting and simulation scripts
- `execution/`   – Live/paper trading, broker integration
- `reporting/`   – Performance reports, logs, analytics
- `data/`        – Data downloaders, storage, and preprocessing
- `logs/`        – Logs and trade audit trails
- `notebooks/`   – Research and experiment notebooks

## How to Run

1. Install dependencies:
   pip install -r requirements.txt
2. Run main script:
   python main.py

3. For notebooks, open and run via Jupyter or Colab.

## License

[MIT](LICENSE)

