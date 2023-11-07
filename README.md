# Monte Carlo Simulation

## Portfolio Construction
The analysis focuses on a portfolio consisting of six stocks (AAPL, CRM, AMZN, MSFT, NFLX, JPM) and two ETFs (SOXX, XBI) over a ten-year period from April 1, 2010, to April 1, 2020.

## MCS Model
Monte Carlo Simulation is a computational technique that uses random sampling to model and analyze complex systems. In finance, it's commonly employed to assess the range of possible outcomes for an investment or portfolio. By running multiple simulations with randomly generated inputs, it provides insights into the potential future performance and associated risks. Monte Carlo simulations help decision-makers make informed choices by considering a spectrum of possible scenarios rather than relying on a single deterministic forecast.

![Total Portfolio Values Simulations](https://github.com/suti333/Monte-Carlo-Simulation/assets/97738816/3b80a4d0-482b-4bc9-99d0-e8af585a1ab7)

## Optimization Methods
Three optimization methods were applied to find optimal portfolio allocations:
1. Max Sharpe Ratio: Maximizing the Sharpe Ratio.
   Max SR achieved: 0.9975596205837038
2. Min Volatility: Minimizing portfolio volatility.
   Min Volatility achieved: 0.21481393866564125
3. Max Return: Maximizing total portfolio return.
   Max Return achieved: 0.2695788040465871 

## All Portfolio Combinations
![MCS](https://github.com/suti333/Monte-Carlo-Simulation/assets/97738816/94a8e6ea-3fc0-421d-a238-d8217b878205)

## Mathematical Optimization Algorithm
Optimal weights can be mathematically determined using optimization functions. By utilizing the built-in optimization algorithm in the SciPy library, we create an optimizer that seeks to minimize the negative Sharpe Ratio, effectively maximizing the Sharpe Ratio, thus helping in calculating the optimal allocation of weights for our portfolio.
Max Sharpe Ratio achieved: 1.0314830757146503

## Efficient Frontier
The efficient frontier comprises optimal portfolios that provide the maximum expected return for a specified level of risk or the minimum risk for a given expected return. Portfolios below the efficient frontier are suboptimal, offering insufficient return for the associated risk. Similarly, portfolios to the right of the efficient frontier are suboptimal as they entail higher risk for a given rate of return.

![MCS_EF](https://github.com/suti333/Monte-Carlo-Simulation/assets/97738816/69960126-2343-428a-8fea-c0c93c242390)


