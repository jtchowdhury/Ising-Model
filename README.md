# Monte Carlo Methods in Statistical Mechanics and Quantum Field Theory

## Overview
This summer, my work sat at the intersection of **statistical mechanics**, **computational physics**, and **quantum field theory (QFT)**. I simulated various forms of **random walks** and **lattice models**, including the **Ising model** and **percolation systems**.  
Please check the final write-up for detailed analysis. The contents of the Jupyter Notebooks are as follows:

## Demonstration of Monte Carlo Methods
- Estimation of $\pi$ — `Estimation_of_Pi.ipynb`
- Test of Python's random number generator — `RNG_test.ipynb`

## Random Walk
Simulated multiple variations of random walks:
- Basic Random Walk — `Random_walk.ipynb`
- Loops in Random Walk — `Loops.ipynb`
- Non-reversal Walk — `Variations_of_random_walk.ipynb`
- Self-avoiding Walk — `Variations_of_random_walk.ipynb`

## Lattice Percolation
Simulated a 2D square lattice — `Percolation.ipynb`:
- Studied percolation probability and phase transition at the critical occupation probability
- Analyzed distribution of cluster size and number
- Investigated anomalous diffusion

## Metropolis Algorithm
Implemented for the Ising model — `Ising_model_metropolis.ipynb`:
- Implemented and analyzed the **Metropolis algorithm**
- Computed:
  - Thermalization period
  - Auto-correlation period
  - Energy
  - Magnetization
  - Binder's Cumulant
  - Cluster Count
  - Susceptibility
  - Specific heat
  - 2-point correlation functions
- Performed **finite-size scaling** to extrapolate results to the infinite-lattice limit

## Worm Algorithm 
Developed and applied from theoretical principles — `Worm_algorithm.ipynb`:
- Applied it to the same systems as the Metropolis algorithm
- Verified matching results with the Metropolis approach
- Demonstrated **accuracy** and **reliability** through cross-validation

## Connection to Lattice Quantum Field Theory
While the Ising model is a **classical statistical physics system**, the computational techniques and algorithms developed are closely related to those used in **lattice QFT**.  
In lattice QFT:
- Many problems require evaluating **infinite-dimensional integrals** over all possible field configurations — the **path integral**
- These integrals are generally impossible to solve exactly, but **lattice discretization** of space-time makes them numerically tractable

By validating algorithms on simpler, well-understood systems like the Ising model, we are testing computational strategies that can later be applied to simulate the universe at its most fundamental level — including scenarios in **quantum gravity**.
