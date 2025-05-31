# ASI_Project
Stochastic Gradient Hamiltonian Monte Carlo (SGHMC) – Paper Reproduction

This project aims to explain and reproduce some of the results from the paper "Stochastic Gradient Hamiltonian Monte Carlo". The paper explores the effect of using a noisy estimate of the gradient in Hamiltonian dynamics. To mitigate the impact of this noise, the authors propose adding a friction term to counteract its effects, resulting in the Stochastic Gradient Hamiltonian Monte Carlo (SGHMC) algorithm. The results show that SGHMC is effective in simulated scenarios, producing an algorithm capable of handling noisy gradients while maintaining low computational cost. However, tests on real-world scenarios yield less accurate results, indicating that the algorithm requires careful hyperparameter tuning and training strategy.

