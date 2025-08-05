# Advanced Portfolio Optimization
This project implements an advanced portfolio optimization strategy for a portfolio of six assets. The goal is to maximize expected returns while minimizing risk and accounting for transaction costs when adjusting from a prior allocation.

# Features
✅ Numerical optimization to determine the ideal asset allocation.

✅ Constraints:

Allocation values must be between 0 and 1.

Total allocation must sum to 1.

✅ Transaction cost modeling when shifting from a previous allocation.

✅ Risk-return tradeoff optimization.

✅ Data visualization:

Theoretical expected returns for each asset.

Optimized returns based on the computed allocation.

Final portfolio performance breakdown.

# How It Works
Define asset returns and risks: Model the expected returns and covariances for six different assets.

Set initial allocation: Include an initial allocation vector to account for transaction costs.

Optimize allocation: Use numerical methods to find the best allocation that:

Maximizes expected return.

Minimizes portfolio variance (risk).

Accounts for the cost of changing allocations.

Visualize results: Plot both the theoretical and optimized returns, along with a clear view of the final allocation and performance.

# Output
📊 Asset Allocation Bar Charts: Before and after optimization.

📈 Portfolio Performance Summary: Expected return, risk, and net return after transaction costs.

# Use Cases
Algorithmic trading strategies

Robo-advisory platforms

Personal investment analysis

Educational use in financial engineering or quantitative finance
