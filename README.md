# RSI-Based Trading Strategy on the “Magnificent 7” Stocks

A custom Python backtesting engine for an RSI-based trading strategy on the “Magnificent 7” stocks, featuring dynamic rebalancing, realistic execution constraints, and alpha-enhancing extensions like volatility targeting and multi-factor blending.

## 🧠 Strategy Highlights

- **Signal Logic:** End-of-day RSI signals with next-day execution
- **Allocation Method:** Equal-weighted with max 30% stock exposure
- **Execution Constraints:** Includes slippage, commissions, and minimum trade size
- **Rebalancing:** Dynamic portfolio rebalancing and position sizing

## 🔍 Results

The strategy **outperformed the S&P 500** over the full backtest period and remained profitable across multiple robustness checks.

## 🚀 Enhancements

- Volatility targeting using EWMA-adjusted leverage
- Multi-factor blending for improved signal quality
- Overfitting risk assessment with walk-forward and hold-out testing

## 📂 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib

---

> *For academic or research use. Not financial advice.*
