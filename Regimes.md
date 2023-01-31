We first consider current as a function of gate to sourcwe voltage $V_{gs}$.


# Subthreshold Region
Small voltage are reduced so low power consumption. 

Increasing the gate voltage **increases the positive charge on the gate.** This charge **repels the holes in the substrate** and leaves behind negative ions that balance out the gate charge. The MOSFET operates in the **sub-threshold regime** when the **positive charge on the gate is almost balanced by the negatively-charged depletion region underneath the gate**. There is also a very thin layer of electrons beneath the gate (the inversion
layer) but it is negligible in this regime. 

![[Pasted image 20230131105852.png|500]]

In these diagrams, the axis for the electron energy is directed upwards, while the positive voltage axis is downwards. That is, the quasi-Fermi level of the region that has a higher applied voltage (like the drain of the transistor) is lower than the quasi-Fermi level of the source region. Because the barrier at the drain is higher than that at the source, the electron concentration at the drain end of the channel is lower than at the source end. The **concentration gradient** leads to the diffusion of electrons from the **source** to the **drain**. The electrons that diffuse to the drain end of the channel are swept into the drain by the electric field in the depletion region around the drain. The electrons in the channel form an inversion layer. As the gate voltage increases, the depletion region also increases so that the negative charge in this region balances the increased positive charge on the gate. The surface potential relative to the bulk also increases because of the wider deple-
tion region.

Doing the math for carrier densities and surface potential leads to the following equation:

$I =I_{0}e^{\kappa V_{g}/U_{T}}(e^{-V_{s}/U_{T}}-e^{-V_{d}/U_{T}})$

that can be separated into $I_{f}$ and $I_{r}$:

$I=I_{f}-I_{r}$

where:

- $I_{f}=I_{0}e^{(\kappa V_{g}-V_{s})/U_{T}}$
- $I_{r}=I_{0}e^{(\kappa V_{g}-V_{d})/U_{T}}$

The forward component depends only on $Vgs$, while the reverse depends only on $Vgd$. 

## Regions of operation
We have different regions of operation depending on $Vds$.

### Triode/linear
![[Pasted image 20230131112047.png]]
The current depends on $Vds$. This region describes the operation of the transistor for small $Vds$. 

### Saturation
The current is independant of $Vds$.
