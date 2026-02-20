# Sequential Inference for Hidden Markov Models

Master's thesis submitted in partial fulfillment of the requirements for the degree of Master of Science in Statistics and Analytics at the University of Arkansas (December 2018).

## Abstract

In many applications data are collected sequentially in time with very short time intervals between observations. If one is interested in using new observations as they arrive in time then non-sequential Bayesian inference methods, such as Markov Chain Monte Carlo (MCMC) sampling, can be too slow. Increasingly, state space models are being used to model nonlinear and non-Gaussian systems. The structure of state space models allows for sequential Bayesian inference so that an approximation to the posterior distribution of interest can be updated as new observations arrive. In special cases, the exact posterior distribution can be updated through conjugate Bayesian inference. However, for the general state space model this is not possible. In quantitative finance hidden Markov models have been used to analyze and forecast percent log returns of an asset or a group of assets. In this thesis the Liu and West (2001) auxiliary particle filter is applied to sequentially update the posterior distribution of a hidden Markov model with unknown state and observation distribution parameters.

## Contents

- [Full Thesis (PDF)](Sequential%20Inference%20for%20Hidden%20Markov%20Models.pdf)

### Chapters

1. **Introduction**
2. **General State Space Models** -- state estimation framework
3. **Sequential Monte Carlo Methods** -- importance sampling, bootstrap filter, auxiliary particle filter, auxiliary particle filter with unknown parameters
4. **Application** -- HMM for S&P 500 daily returns with simulated and real data examples, forecasting and forecast evaluation
5. **Conclusion**

## Citation

```bibtex
@mastersthesis{ellis2018sequential,
    author = {Ellis, Michael},
    title  = {Sequential Inference for Hidden Markov Models},
    school = {University of Arkansas},
    year   = {2018},
    type   = {Master's Thesis},
    url    = {https://scholarworks.uark.edu/etd/2963}
}
```

## Committee

- Giovanni Petris, Ph.D. (Thesis Director)
- John Tipton, Ph.D.
- Jyotishka Datta, Ph.D.

## References

- Liu, J., & West, M. (2001). Combined parameter and state estimation in simulation-based filtering. In *Sequential Monte Carlo Methods in Practice* (pp. 197-223). Springer.
- Petris, G., Petrone, S., & Campagnoli, P. (2009). *Dynamic Linear Models with R*. Springer.
