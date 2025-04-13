RSI-Based Trading Strategy on the “Magnificent 7” Stocks
This project implements a custom backtesting engine to evaluate a Relative Strength Index (RSI)-based trading strategy on the “Magnificent 7” stocks: MSFT, AAPL, NVDA, AMZN, GOOG, META, and TSLA from IPO through 2023.

🧠 Strategy Highlights
Signal Logic: End-of-day RSI signals with next-day execution

Allocation Method: Equal-weighted with max 30% stock exposure

Execution Constraints: Includes slippage, commissions, and minimum trade size

Rebalancing: Dynamic portfolio rebalancing and position sizing

🔍 Results
The strategy outperformed the S&P 500 over the full backtest period and remained profitable across multiple robustness checks.

🚀 Enhancements
Volatility targeting using EWMA-adjusted leverage

Multi-factor blending for improved signal quality

Overfitting risk assessment with walk-forward and hold-out testing

📂 Tech Stack
Python, Pandas, NumPy, Matplotlib

Custom-built backtest loop with extendable logic
