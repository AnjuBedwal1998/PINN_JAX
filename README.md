# Solving the 1D Burgers' Equation Using Physics-Informed Neural Networks (PINNs)

## Governing Equation

We consider the 1D Burgers' equation:

$$
\frac{\partial u}{\partial t} + u \frac{\partial u}{\partial x} = \nu \frac{\partial^2 u}{\partial x^2}, \quad x \in [-1, 1], \quad t \in [0, 1]
$$

with viscosity:

$$
\nu = \frac{0.01}{\pi}
$$
# Boundary Conditions

$$
    u(x, 0) = -\sin(\pi x), \quad x\in[-1,1]
$$

$$
    u(-1, t) = 0, \quad u(1, t) = 0 \quad \text{for all } t \in [0, 1]
$$
