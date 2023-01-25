Neuromporphic circuits make use of analog subthreshold electronic circuits. The perfect emulation of the biophysics of proteic channels.

## Why transistors?
By varying the gate voltage we are able to control the amount of current flowing through the transistor (in an exponential manner).
![[Pasted image 20230124182757.png|200]]
The transistor can operate in two regimes. [[Subthreshold]] and [[above threshold]]. 
![[Pasted image 20230124182337.png|400]]
Here we can see that the curve is similar to an IV curve from a channel.
	![[Pasted image 20230124182525.png|400]]

## N-FETs

### Subthreshold
![[Pasted image 20230124182638.png|300]]
Where the bulk, $V_{b}$ is connected to $GND$. The current flows from drain to source (think about electron source) and depends on:

$\begin{align}I_{ds} = I_{0}e^{\kappa V_{g}/U_{T}}(e^{-V_{s}/U_{T}}-e^{-V_{d}/U_{T}})\end{align}$

which is equivalent to:

$\begin{align}I_{ds} = I_{0}e^{\kappa V_{g}/U_{T}-V_{s}/U_{T}}-I_{0}e^{\kappa V_{d}/U_{T}-V_{s}/U_{T}}\\= I_{f}-I_{r}\end{align}$

If $V_{ds} > 4 U_{T}$ the $I_{R}$ term becomes negligible and we operate in the saturation regime and the equation simplifies to

$\begin{align}I_{ds} = I_{0}e^{\kappa V_{g}/U_{T}-V_{s}/U_{T}}\end{align}$

**Variables**
- $I_{0}$ current-scaling parameter. 
- κ subthreshold slope factor $\kappa = \frac{C_{OX}}{C_{OX}+C_{dep}}$. 
- $U_{T}$ the thermal voltage. 
- $Vg$ the gate voltage, 
- $Vs$ the source voltage, 
- $Vd$ the drain voltage

In subthreshold, for a constant $I$, a $ΔV$ change in the source voltage means that the gate voltage has to increase by $𝜅ΔV$ and not just $ΔV$.

#### Current characterisation
Given a ready made transistor, we can influence $I$ with $V_{gs}$ and $V_{ds}$ 
![[Pasted image 20230124185133.png|400]]
![[Pasted image 20230124185149.png|400]]

We can view this in three dimensions to get a better grasp of it.
![[Pasted image 20230124185324.png|400]]

## P-FETs
![[Pasted image 20230124182935.png|300]]
Where the bulk,  $V_{b}$ is connected to $V_{dd}$ 
![[Pasted image 20230124184929.png|400]]

## Operating regimes
![[Pasted image 20230125101507.png|400]]

### Subthreshold
#### Linear or ohmic or triode


#### Saturation
$V_{ds}>4U_{T}(100mV)$
![[Pasted image 20230125114742.png|350]]
As increases beyond , the concentration of electrons at the drain end
of the channel can be neglected with respect to the concentration at the source
end because of the larger barrier height as shown in Fig. 3.5(c). Any electrons
in the channel that diffuse close to the drain are immediately swept into the
drain by the electric field in this region. Because the diffusion current is no
longer dependent on the electron concentration at the drain, the current in
the transistor depends only on and is approximately equal to.

This region of operation is called the saturation region. As seen in Fig. 3.7, the
current is approximately constant in this region. Figure 3.8 shows a family
of curves measured from the same nFET in the subthreshold region with gate
voltages ranging from $0.3 V$ to $0.7 V$. 

In these curves, the transition point fromthe linear region to the saturation region occurs around $V_{ds}=100 mV$ and is independent of the gate voltage.

## Superthreshold
![[Pasted image 20230125115340.png]]
The equations change a bit, but luckily we dont work much in this regime
### Saturation

### Triode


## The circuits
- [[Current source]]
- [[Current mirror]]
- [[Differenial pair]]
- [[Transconductance amplifier]]
- [[Spike generating mechanism]]
- [[Conductance based neuron]]
- [[Integrate and fire neuron]]
- [[Current mode DPI]]
- [[Synapse analog circuit]]