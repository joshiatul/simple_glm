# simple_glm
Simple glm library with the following objectives in mind:

1) Support for weighted poisson regression (along with linear / logistic case)
	(sklearn and statmodels do not support weighted poisson regression case)

2) Ability to pass custom prior means and variances for regularization
	(sklearn, vw do not support turning off regularization for intercept)

3) For now simple normal equations method is implemented (via QR decomposition), in future it can be extended for more memory efficient methods

# References:
Gellman et al., Bayesian Data Analysis Second Edition, Feb-2009, (Chapman & Hall/CRC Texts in Statistical Science)(Chapter 16 - Generalized Linear Models)

# Usage:
Examples in tests.py
(work in process)