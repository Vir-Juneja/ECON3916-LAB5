# Monte Carlo Engine -- Probability & Simulation

## Objective

I used Monte Carlo simulations to explore probability, test statistical concepts, and measure financial risk.

## Methodology

- **Coin Flip Simulation:** I simulated 10,000 coin flips and plotted the running proportion of heads to observe how the results approach the expected probability over time.
- **Monty Hall Problem:** I simulated 10,000 Monty Hall games to compare the outcomes of switching doors versus staying with the original choice.
- **Disease Screening:** I simulated medical screening tests for 100,000 people using a disease prevalence of 1%, sensitivity of 95%, and specificity of 90%. I calculated the percentage of people who actually had the disease among those who tested positive.
- **Portfolio Risk Analysis:** I used Monte Carlo simulations to calculate Value at Risk (VaR) and Expected Shortfall (ES) for a $1 million portfolio.
- **Monte Carlo Error:** I estimated pi using random sampling and examined how simulation error decreases as the sample size increases, following the theoretical rate of 1/√n.

## Key Findings

- **Coin Flips:** The running proportion of heads moved toward the expected probability as the number of simulations increased, illustrating the Law of Large Numbers.
- **Monty Hall:** Switching doors won [YOUR VALUE] out of 10,000 games, demonstrating the advantage of switching over staying.
- **Disease Screening:** [YOUR VALUE]% of positive test results came from people who actually had the disease. This demonstrated how disease prevalence affects the interpretation of a positive test result, even when sensitivity and specificity are relatively high.
- **Portfolio Risk:**
  - **95% VaR:** $[YOUR VALUE]
  - **95% Expected Shortfall:** $[YOUR VALUE]
  
  I used VaR to estimate the daily loss threshold at the 95% confidence level and Expected Shortfall to measure the average loss on days exceeding that threshold.

- **Monte Carlo Convergence:** I confirmed that estimation error decreased approximately at the rate of 1/√n as the number of simulations increased. This showed why larger simulations generally produce more accurate estimates.

## Conclusion

Through this lab, I learned how Monte Carlo simulation can help explain probability, estimate uncertain outcomes, and measure financial risk. I also saw how increasing the number of simulations improves accuracy and how statistical results depend on underlying assumptions.
