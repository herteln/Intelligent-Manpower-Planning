# Probabilistic Graphical Models

Probabilistic Graphical Models (PGMs) are used to represent uncertainty and dependencies between planning variables.

## Bayesian Networks

Bayesian Networks represent directed probabilistic dependencies.

Possible variables include:

- incident volume,
- incident severity,
- employee availability,
- skill coverage,
- system complexity,
- resolution time,
- workload,
- SLA risk.

They can support scenario questions such as:

> Given higher-than-normal incident volume and reduced skill coverage, what is the probability of an SLA risk?

## Markov Networks

Markov Networks represent undirected dependencies and can be useful where relationships matter but a clear causal direction is not required.

## Role in the System

Forecasting predicts expected demand. PGMs add probability, uncertainty and scenario reasoning.
