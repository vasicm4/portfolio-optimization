# GAPortfolioOptimization

GAPortfolioOptimization is a financial engineering tool built in C++ that leverages Genetic Algorithms and parallelism to solve the complex challenge of asset allocation. By simulating the process of natural selection, this tool evolves a population of portfolios to maximize the Sharpe Ratio, effectively balancing risk-adjusted returns.

## Why use a Genetic Algorithm?
Traditional optimization (like Mean-Variance Optimization) can get stuck in "local optima" or fail when faced with complex constraints. This tool uses evolutionary heuristics—Crossover, Mutation, and Selection—to navigate the search space and find the most efficient allocation of assets.

The primary objective is to maximize the Sharpe Ratio ($S$), defined as:$$S = \frac{R_p - R_f}{\sigma_p}$$
Where:$R_p$: Expected portfolio return
$R_f$: Risk-free rate of return
$\sigma_p$: Standard deviation of portfolio excess return (volatility)
