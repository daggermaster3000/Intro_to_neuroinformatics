
## Above threshold saturation
When deriving the I–V characteristics of the nFET we assumed that the current is constant in the saturation regime. This assumption is not sufficient, particularly for **short-length** MOSFETs. The drain voltage can modulate the channel current even in saturation. In the **above-threshold saturation regime**, the effective length of the transistor,$L_{eff}$ , decreases when $V_{d}$ increases because the pinchoff region extends further along the channel away from the drain. We describe as the difference between the drawn channel length,$L_{eff}$ , and the size of the pinchoff region. Hence, the transistor current increases with $V_{d}$.

![[Pasted image 20230130092359.png|400]]


The Early voltage is defined as the **absolute value of the voltage at which the slope intersects the voltage axis on this curve**.
![[Pasted image 20230130092520.png|400]]


**Formula:**

$V_{e}=-L_{eff} \frac{\delta V_{ds}}{\delta L_{eff}}$.

$Ve$ is named after Jim Early who first analyzed this effect in BJTs.

## Subthreshold
This effect also occurs in subthreshold (because of the finite slope of the I-V curve)

![[Pasted image 20230125114742.png|500]]
In the subthreshold domain, the saturation current,$I_{sat}$ , which is given by:

$I=I_{sat}+g_{ds}V_{ds}=I_{sat}\left( 1+ \frac{V_{ds}}{V_{e}} \right)$

accounting for the early effect.


## Realtion to [[conductance]]

$g_{ds} = \frac{I}{V_{e}}$

