# Monte-Carlo-Simulations-using-Antithetic-Variates

Monte Carlo Simulations (MCS) are a powerful class of computational algorithms that rely on repeated random sampling to obtain numerical results. They are widely used across fields such as finance, physics, engineering, statistics, and machine learning to model systems with uncertainty or complexity that are difficult to solve analytically. 

**Core Idea**:

Monte Carlo Simulation uses random inputs to simulate a process or system many times, and then analyzes the output to estimate quantities like probabilities, means, variances, or confidence intervals.

Basic Steps:

1. Define a domain of possible inputs.

2. Generate random inputs from that domain.

3. Perform deterministic computation using those inputs.

4. Aggregate the results (e.g., compute average or probability).

**Problems Faced in Monte Carlo Simulations:**

1. Slow convergence: Error decreases as N to power of negative half, where N is number of independent random simulations.

2. High variance: Estimates can be noisy without variance reduction techniques.

3. Can be computationally expensive.

4. Difficult to sample from complex distributions without advanced methods.


**Variance Reduction:**

1. Antithetic variates: Use negatively correlated pairs of samples.

2. Control variates: Use known expectations to reduce variance.

3. Stratified sampling: Divide space into strata and sample from each.



