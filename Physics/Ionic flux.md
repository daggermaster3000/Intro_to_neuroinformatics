## Intuition 
Most resting channels are only permeable to $K^+$. The efflux of $K^+$ from the cell (following the gradient of concentration) gives rise to an electrical potential difference. The greater the flow, the grater the potential (because more charge is separated). As $K^+$ is positive, the negative potential inside the cell opposes further efflux. 
 
 Therefore, the ions are subject to 2 forces.
- **chemical driving force** (function of gradient of concentration)
- **electrical driving force** (function of the electric potential difference accross the membrane)

Once $K^+$ diffusion has proceeded to a certain point, both of the forces balance out and the $flux$ of $K^+$ is the same in both directions. We have reached equilibrium potential.

## Calculating flux
We will now quantify the flux of an ion through a cell membrane that is only permeable to it (at equilibrium $\text{Flux}_{out \rightarrow in} = \text{Flux}_{in \rightarrow out}$ ).

### Out In
Positive charge will just get sucked in
$$\text{Flux}_{out \rightarrow in} = \gamma [K^+]_{out}$$
### In Out
We have to add a term that represents the fraction of particles that have enough kinetic energy to make through the barrier.
$$\text{Flux}_{in \rightarrow out} = \gamma [K^+]_{in} \space p(E_{kinetic}>|qV_{eq}|)$$
where,
- $\gamma = \text{number/area of channels/ fraction of channels getting to the entrance}$
- $q = 1.60 e^{-19}$
- $E_{kinetic}$ is the thermal motion

#### The Boltzmann factor
$$p(E_{kinetic}>|qV_{eq}|) = e^{\frac{qV_{eq}}{k_B}T} = e^{\frac{-E}{k_B}T}$$
- $k_B = 1.38 \space e^-23 JK^{-1}$
![[Pasted image 20230118142606.png|400]]
