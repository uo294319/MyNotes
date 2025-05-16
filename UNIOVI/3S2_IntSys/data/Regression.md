# Linear Regression
---
[Go Back](UNIOVI/3S2_IntSys/README.md)

---
## Definition

> **Linear regression** is a supervised machine learning algorithm that models the linear relationship between a dependent variable (target or output) and one or more independent variables (features or inputs).

## How?

1. Given a set of features $x_1$, $x_2$, ... $x_d$
2. Try to find a set of parameters (called weights) $\theta_0$, $\theta_1$, ... $\theta_d$ 
3. So we can predict the target $h_\theta(x)$

$$h_\theta(x) = \theta_0 + \theta_1 x_1 + ... + \theta_d x_d$$

For simplicity we consider $x_0 = 1$ (intercept term):

$$h(x) = \sum_{i=0}^d \theta_i x_i$$

Or in a vectorial way: $h(x) = \theta^Tx$
