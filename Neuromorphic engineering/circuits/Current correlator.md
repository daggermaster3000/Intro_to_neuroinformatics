
**Input:** $I1$ and $I_{2}$
**Output:** Correlation between $I1$ and $I_{2}$
**Settings:** 
**Notes:** For it to work all must be in [[Regimes#Subthreshold Regime]]. $M_{1}$ is in ohmic region, $M_{2}$ is in saturation. $V_{s}$ is = 0V
![[Current correlator 2023-02-01 10.58.39.excalidraw.svg]]
%%[[Current correlator 2023-02-01 10.58.39.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Current correlator 2023-02-01 10.58.39.excalidraw.dark.svg|dark exported image]]%%

The current correlator measures the correlation between unidirectional input currents.

Mead recognized that in **subthreshold** operation, the current-correlator circuit in Fig. 6.12 computes a measure of the correlation between its two input currents. 



![[Pasted image 20230201141739.png]]

$I_{out} = \frac{I_{1}I_{2}}{(I_{1}+I_{2})}$
(exprimer $e^{Vs}$ pour trouver)

The n-input current correlator computes the parallel combination of the
input currents. The maximum number of inputs can be large, because the
only requirement for correct circuit operation is that the top transistor in the
correlator be saturated. However, the output current scales as $\frac{1}{n}$.

![[Pasted image 20230201135058.png|400]]
![[Pasted image 20230201135105.png|300]]
**Strength ratio:**
(the scaling factor)
![[Pasted image 20230201110626.png|300]]



