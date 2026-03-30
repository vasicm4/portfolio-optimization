# GAPortfolioOptimization

GAPortfolioOptimization is a financial engineering tool built in C++ that leverages Genetic Algorithms and parallelism to solve the complex challenge of asset allocation. By simulating the process of natural selection, this tool evolves a population of portfolios to maximize the Sharpe Ratio, effectively balancing risk-adjusted returns.

## Why use a Genetic Algorithm?
Traditional optimization (like Mean-Variance Optimization) can get stuck in "local optima" or fail when faced with complex constraints. This tool uses evolutionary heuristics—Crossover, Mutation, and Selection—to navigate the search space and find the most efficient allocation of assets.

## Key features
Sharpe Ratio Maximization: Optimizes for the highest expected return per unit of volatility.
Evolutionary Engine: Uses custom selection and mutation logic to prevent premature convergence.
Dynamic Constraints: Easily handle "long-only" constraints or specific sector weightings.
Visualization: Generates the Efficient Frontier to visualize the tradeoff between risk and return.
