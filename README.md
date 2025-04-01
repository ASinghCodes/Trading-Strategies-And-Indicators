# Theoretically Optimal Strategy & Technical Indicators

## Project Overview  
This project explores the performance boundaries of trading strategies through two components: (1) building a **Theoretically Optimal Strategy (TOS)** assuming perfect foresight, and (2) analyzing five widely-used **technical indicators** to understand their predictive utility. The work offers both a benchmark for maximum potential returns and a foundation for feature engineering in strategy development.

**Languages/Tools Used:** Python, Pandas, NumPy, Matplotlib  
**Key Concepts:** Theoretical Upper Bound, Market Simulation, Technical Indicators, Trading Signals, Quantitative Analysis

---

## Project Objectives
- Simulate a **Theoretically Optimal Strategy** to serve as an upper bound for portfolio performance  
- Evaluate strategy performance vs. a buy-and-hold **benchmark** using JPM stock (2008–2009)  
- Implement five technical indicators for future signal generation:
  - Bollinger Bands
  - Relative Strength Index (RSI)
  - Exponential Moving Average (EMA)
  - Momentum
  - MACD
- Visualize each indicator alongside price history to demonstrate trends and signals

---

## Part 1: Theoretically Optimal Strategy (TOS)
- Assumes perfect foresight with legal trades of ±1000 shares (max position: ±1000)
- No commissions or market impact modeled
- `testPolicy()` generates trade signals for optimal entry and exit across the date range
- Uses a revised market simulator to track portfolio value

**Performance Metrics Tracked:**
- Cumulative Return
- Average Daily Return
- Standard Deviation of Daily Returns
- Sharpe Ratio

**Benchmark vs. Optimal Comparison:**
- Chart comparing benchmark (buy-and-hold) vs. TOS portfolio (both normalized)
- Table comparing performance metrics side-by-side (6 decimal precision)

---

## Part 2: Technical Indicators
For each indicator:
- Computed values across the 2008–2009 date range using JPM stock
- Visualized alongside price data with labeled, well-annotated charts
- Charts include:
  - Price vs. Bollinger Bands
  - Price vs. RSI threshold regions
  - EMA trends over time
  - Momentum line comparisons
  - MACD line & signal crossovers

---

## Value & Learning Outcomes
- Gained insight into the **theoretical limits of strategy performance**
- Learned how to model and interpret **real-world trading indicators**
- Practiced working with **portfolio simulation frameworks**
- Developed visual storytelling skills for financial analytics
- Prepared foundational components for future strategy learning and testing

---

## Repository Access  
Due to academic policy, the full implementation—including simulation logic, indicator functions, plots, and strategy outputs—is stored in a private GitHub repository. **Access available upon request.**
