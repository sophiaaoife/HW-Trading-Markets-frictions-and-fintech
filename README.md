# HW-Trading-Markets-frictions-and-fintech

## Asg 1
write a simple back-testing algorithm

## Asg 2
Q1: Simulate Bid-ask spread dynamics
Q2: analysis the trading spread and volume, both daily and intraday

## Asg 3
* Calculate **order imbalance OFI**
  * Order flow imbalance represents the changes in supply and demand. 
  * Best bid or size at the best bid increase -> increase in demand.
  * Best bid or size at the best bid decreases -> decrease in demand.
  * Best ask decreases or size at the best ask increases -> increase in supply.
  * Best ask increases or size at the best ask decreases -> decrease in supply.
  * $$e_n = I_{B_n \geq B_{n-1}} q_n - I_{B_n \leq B_{n-1}} q_{n-1} - I_{A_n \leq A_{n-1}} q_n + I_{A_n \geq A_{n-1}} q_{n-1} $$
* Aggregate OFI to second level (take summation)
* Using OFI to generate trading signal: first do train/test split by selecting the first 70% of the data
* achieve 23% return in 6 years

## Asg 4
* Calculate Kyle’s lambda (market impact)

## Presentation
Volatility Dispersion, buy the volatility by buying straddle

