# HyperParameter Tuning (Bayesian search)
 The Bayesian search methods collect the results of past iterations to decide which regions are the most promising in the hyperparameter space to test continuation.

With the Bayesian search, the space is explored with the help of a substitute model, which offers an estimation of the bondage of any combination of hyperparameters. As a rule, more iterations are performed, the algorithm updates the substitute model, and the predictions improve each time.

Today we make use of Python library called Optuna. Optuna has a clean API that abstracts away all the fine details behind TPE and other Bayesian search methods. It's a perfect plug-and-play library that we can start using without a deep understanding of the math behind Bayesian methods.
