# Financial Engineering in Python

A collection of four individual computational finance studies exploring derivatives pricing, no-arbitrage valuation, volatility, hedging, and stochastic simulation. The notebooks combine mathematical reasoning with Python-based numerical analysis.

## Projects

| Notebook | Topics |
| --- | --- |
| [01 · Forwards, Futures & No-Arbitrage Valuation](01_forwards_and_futures.ipynb) | Replicating portfolios, foreign-exchange forwards, mark-to-market valuation, futures pricing, and arbitrage strategies. |
| [02 · Option Arbitrage & Binomial Trees](02_options_and_binomial_trees.ipynb) | Option-price bounds, convexity, put–call parity, binomial valuation, hedging, and American exercise. |
| [03 · Volatility, Hedging & Structured Products](03_volatility_and_hedging.ipynb) | Historical and implied volatility, FX option valuation, delta hedging, structured payoff replication, and barrier options. |
| [04 · Monte Carlo Pricing & Interest Rate Swaps](04_monte_carlo_and_swaps.ipynb) | Simulation of vanilla and barrier options, antithetic variates, comparison with analytical prices, swap valuation, and Ito’s lemma. |

## Methods and concepts

Across the collection, I apply **no-arbitrage and replication arguments**, **Black–Scholes–Merton and binomial models**, **numerical methods**, and **Monte Carlo simulation with variance reduction**. I also examine hedging strategies, interest-rate products, and the connection between model assumptions and derivative prices.

## Context

These are individually completed studies developed during a Financial Engineering course. I have organized them by topic to make the mathematical derivations, implementations, and financial interpretations easy to explore.

*Some calculations in notebooks 03 and 04 reference a course-provided `bsm.py` helper module. That instructor-authored module is not included in this repository.*
