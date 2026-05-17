# Regime-Based Hedging of the S&P 500 using Gold and U.S. Treasuries
## Objective

This project evaluates whether the optimal hedge for the S&P 500 varies across macroeconomic regimes defined by inflation and growth trends. The goal is to construct a dynamic allocation between equities, gold, and Treasuries that improves downside protection while maintaining competitive long-term returns.

**Key Finding:** The regime-based strategy reduces maximum drawdown from -52.6% (unhedged S&P 500) to -34.3% — an 18 percentage point improvement — while maintaining similar annualised returns (~8.3% net vs 8.8%).

## Research Question

Can a regime-conditioned hedge improve drawdown and risk-adjusted performance relative to both an unhedged equity portfolio and a static diversified allocation?

## Approach

- Define macro regimes using GDP and CPI trend dynamics  
- Construct monthly returns for S&P 500, gold, and a Treasury proxy  
- Use a rolling walk-forward framework with a 60-month lookback  
- Solve a constrained portfolio optimisation problem within each regime  
- Evaluate out-of-sample performance with transaction costs  
