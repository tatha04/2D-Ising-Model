# 2D-Ising-Model
The notebook simulates a 2D Ising Model with nearest neighbor interactions. A system of L x L square lattice with periodic boundary conditions is quenched using the Metrolpolis Algorithm.
The following is a snapshots taken at different temperatures of the lattice configurations of a $ 40 \times 40 $ lattice with nearest neighbor ferromagnetic interactions.

![Snapshots](https://github.com/tatha04/2D-Ising-Model/blob/master/Lattice_config.png)

Observables such as the magnetization, magnetic susceptibility, energy and specific heat are also calculated at each temperature step.
The Magnetization is zero at high temperatures (disordered phase), wheras it gradually increases (or decreases) to $+1$ ($-1$) below the critical temperature $T_c \approx 2.4$ ($k_B =1, J=1$ ).
The specific heat and heat capacity exhibits a peak at the critical temperature.

![Snapshots](https://github.com/tatha04/2D-Ising-Model/blob/master/Observables.png)
