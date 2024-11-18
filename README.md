This file contains 3 main parts:
- TradingStrategy Class
- Backtester Class
- StrategyOptimizer Class

  TradingStrategy Class:
  This is the place where the trading strategies logic is determined and plotted. This is crucial for signal generation on a certain dataset.

  Backtester Class:
  Here the results of the signal generation are determined, statistics such as Annual Return Sharpe Ratio and the Win Rate of the strategy. Also the return distribution of the trades and the portfolio value is shown.

  StrategyOptimizer Class:
  As an algorithm has parameters, this class optimizes these parameters to maximize returns. It optimizes through an evolution algorithm similar to biological evolution principles (mutation, selection, crossover).
