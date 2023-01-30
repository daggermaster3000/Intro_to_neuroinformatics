Metal oxide semi-conductors use insulated gates to controlo barrier energies at PN surface junctions at source and drain. 

## Electron transport

### Drift 
An electric field causes carriers to drift

$J_{drift} = qn\nu = qn\mu(\zeta)$

where:

- $J_{drift}$ is the current flux
- $qn$ is the charge density ($q$ is the elementary charge)
- $\nu$ is the velocity
- $\mu(\zeta)$ is the mobility function of the electric field

**Illustration of the concept:**

![[Pasted image 20230130153230.png|300]]
### Diffusion

A density gradient causes carriers to diffuse. (When to doped types are put in contact for example)

$J_{diff} = -Dq\nabla n$

where:

- $D$ is the diffusion constant
- $\nabla n$ is the spatial gradient of charge density


Drift and diffusion are related by the **Einstein Relation**:

$D=\frac{kT}{q}\mu$

It expresses the connection between the diffusion constant $D$ which determines the forward and reverse currents, the mobility constant $\mu$ which determines the conductance of the resistor  and the [[thermal voltage]] $\frac{kT}{q}$.
At $T=0$ , well... $D=0$ and there are no internal diffusion currents.

### Thermal equilibrium

In thermal equilibrium (no external voltage applied), diffusion and drift currents are balanced ($J_{n}=J_{p}=0$)($J_{n}=J_{n,drift}+J_{ndrift}$ and so on for hole doped).


## P-N Junction
What happens at a junction between P and N (physical contact)?

![[Pasted image 20230130154919.png|500]]

- The diffusion processes give rise to:
	- A net **electron** flow from the **n-type** region to the **p-type** region.
	- A net **hole** flow from **p-type** region to **n-type** region.
- This results in a diffusion current desity $J_{diff}=J_{n,diff}+J_{p,diff}$ from the **p-type** to the **n-type** 
- The diffusing minority carriers recombine with majority carriers in the vicinity of the junction $\rightarrow$ this region is devoid of mobile charge carriers. ($np\ll n_{i}^2$) The **Depletion region**. 
- On the **n-type** side of the junction, the donor electrons are absent and the donor atoms have a surplus proton. (+) charged side
-  On the **p-type** side of the junction, the acceptor holes are filled by the donor atom's electrons and the acceptor atoms have a surplus electron. (-) charged side
- An electric field builds up in the **depletion region** that points from **n** to **p**.
- The electric field generates electron and hole drift currents from **n** to **p**.  

![[Pasted image 20230130161600.png]]

**Electrostatic Potential: potential energy of positive charge** (electron is the mirror image)

### Band structure
![[Pasted image 20230130161824.png|500]]
![[Pasted image 20230130161852.png|500]]

### I-V Characteristics
![[Pasted image 20230130161935.png|400]]
