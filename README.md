# Wave_semiLagrangian_semiImplicit
Solving wave propagation in 3D

The aim of this code is to simulate the propagation of a wave on the surface of water within a two-dimensional domain. The wave's behavior is governed by the wave equation (see pdf file), and the code employs numerical methods (1/2 Lagrangian + 1/2 Implicit) to solve this equation and visualize the resulting wave pattern.

Specifically, the code aims to:

1. Define the initial conditions of the wave, typically represented as a Gaussian pulse.
2. Implement numerical methods, including a semi-Lagrangian backward advection scheme and a semi-implicit method, to solve the wave equation efficiently.
3. Perform the simulation over a specified time period, updating the wave's state at each time step.
4. Visualize the evolving wave pattern in a 3D plot, showing the displacement of the water surface over time.

In summary, the code facilitates the study of wave propagation phenomena, providing insights into how waves behave and interact within a defined physical domain. This could be useful for various applications, such as understanding ocean dynamics, modeling fluid flows, or simulating wave phenomena in engineering contexts.
