## Summary
![[Pasted image 20230125140110.png|200]]
**Input:** $\Delta V =V_{1}-V_{2}$
**Output:** $I_{out}=g_{m}(V_{1}-V_{2})$
**Settings:** $V_{b}$ for $I_{b}$
**Notes:** For it to work $M_{3}$ (and all transistors) must be in [[saturation]]. The diff pair must be in subthreshold.
Can be used as a differential voltage to current converter or a voltage amplifier.

![[Transconductance amplifier 2023-01-25 14.02.29.excalidraw.svg]]
%%[[Transconductance amplifier 2023-01-25 14.02.29.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Transconductance amplifier 2023-01-25 14.02.29.excalidraw.dark.svg|dark exported image]]%%

**Current converter**
![[Pasted image 20230202112634.png]]
![[Pasted image 20230202112743.png]]
For small differential voltages (e.g. $|V1 − V2| < 200mV$), the tanh(·) relationship is approximately linear and can be reduced to a linear one:

$I_{\text {out }}=I_b \tanh \left(\frac{\kappa}{2 U_T}\left(V_1-V_2\right)\right)$
$I_{\text {out }} \approx g_m\left(V_1-V_2\right)$
$g_m=\frac{I_b K}{2 U_T}$


![[Transconductance amplifier 2023-01-25 14.23.00.excalidraw.svg|400]]
%%[[Transconductance amplifier 2023-01-25 14.23.00.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Transconductance amplifier 2023-01-25 14.23.00.excalidraw.dark.svg|dark exported image]]%%

$g_{m}$ is the [[transconductance]] of the amplifier (it has the dimensions of a conductance), but the output conductance is:

$g_{d}=-\frac{\delta I_{out}}{\delta V_{out}}=\frac{I_{b}}{V_{E}}$

where $V_{E}$ is the [[early voltage]] of $M_{2}$ and $M_{5}$.



**Voltage amplifier**
- Open circuit voltage gain (increases with the early voltage):
![[Pasted image 20230202113406.png]]
$Vout$ increases with $V_{1}$ and decreases with $V_{2}$ the gate of $M_{1}$ is called **non-inverting** (+) input terminal and the gate of $M_{2}$ is called **inverting** input terminal (-).

Often the amp is used as a comparator: outputs a high voltage if $V_{1}>V_{2}$ and a low voltage if $V_{1}<V_{2}$.

**Output voltage limits**
Since in the open circuit is normally at one of its limits, we will now determine where those limits lie. If $V_{1}$ is larger than $V_{2}$ , $M_{4}$ goes out of saturation.

![[Pasted image 20230201182359.png]]