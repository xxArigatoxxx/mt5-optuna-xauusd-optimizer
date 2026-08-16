# mt5-optuna-xauusd-optimizer
Optuna-based hyperparameter optimizer for MetaTrader 5 XAUUSD Expert Advisors with automated backtesting, performance evaluation, and best-parameter export.
# MT5 Optuna XAUUSD Optimizer

A Python-based hyperparameter optimization tool for MetaTrader 5 Expert Advisors using Optuna.

## Features

- Automated MT5 Strategy Tester execution
- Optuna TPE hyperparameter optimization
- XAUUSD M15 backtesting
- Net profit and maximum drawdown evaluation
- Profit factor, Sharpe ratio, and win rate tracking
- Minimum trade and win rate constraints
- ML adaptive configuration support
- Export optimized parameters to `.set` files
- Optional automatic application of optimized parameters to the EA source
- Automatic MetaEditor compilation after applying optimized parameters
- Export trial results to CSV and Excel

## Optimized Parameters

The optimizer searches parameters including:

- Maximum spread
- Bollinger Band deviation
- ATR stop-loss multiplier
- ATR take-profit multiplier
- ATR regime ratio
- Minimum trend gap
- Minimum rejection
- Adaptive breakeven
- Adaptive trailing stop

## Requirements

- Python 3
- MetaTrader 5
- Optuna
- Pandas
- A compiled MT5 Expert Advisor
- Windows

Install Python dependencies:

```bash
py -3 -m pip install optuna pandas
