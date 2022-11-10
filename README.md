# Phy_571_project

File two spins works more or less fine for real coefficients
File two spins complex w works well when coefficients are real and produces weird results when the weights are complex


Plan:
1. Solve ground state for 2 spins
2. Solve ground state for N spins
3. So far scipy.optimize.minimize, use more efficient method

Sub-plan:
1:
- Solve for real network weights
- Solve for complex network weights
- Exact solution
- Solve with netket
- Visualization

Done so far:
- Two_qubits works only for the real weights with scipy


Problems to be solved:
Check if everywhere down spins is -1 and not zero
Not working for complex valued weights
Check if energy is good, complex conjugate was wrong, energy is still complex valued
Make sure everything is an array and not a tupple
