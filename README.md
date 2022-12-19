# Phy_571_project

# Final description

Main file we use is N_spins. It consists of the three sections. First one solves the ground state of the N-spin system. Second section computes the spin correlation function. The third section implements the stochastic energy and attempts to solve the system using it.


# Drafts

N_spins works well, but the results were not compared to the theoretical prediction

Plan:
1. Calculate by hand 2 spin system and compare with the results of the simulation
2. Make a class that generates Hamiltonian for the N-spin system and compare with the results

Sub-plan:
1:
- Exact solution
- Solve with netket
- Visualization

# N_spins

Input is a hamiltonian (input is a wave funciton and output a wave function after the application of the hamiltonian), and number of spins in the chain.

Searches for the wavefunction that gives the lowest energy

# 2 Spins

Complte file with computation of energy for system of two spins: exact solution, solution using gradient descent method and usinf stochastic approach.
The spin correelation for the system is also computed to test if the algorithmic solution meets the physical expectations.
Computation of correlation between the distribution of accepted spins and the corresponding weight |Ψ_M|^2 for 2 spins is included.
