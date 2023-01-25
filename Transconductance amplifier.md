## Summary
![[Pasted image 20230125140110.png|200]]
**Input:** $\Delta V =V_{1}-V_{2}$
**Output:** $I_{out}$
**Settings:** $V_{b}$ for $I_{b}$
**Notes:** For it to work $M_{3}$ must be in [[saturation]]

![[Transconductance amplifier 2023-01-25 14.02.29.excalidraw.svg]]
%%[[Transconductance amplifier 2023-01-25 14.02.29.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Transconductance amplifier 2023-01-25 14.02.29.excalidraw.dark.svg|dark exported image]]%%

For small differential voltages (e.g. $|V1 − V2| < 200mV$), the tanh(·) relationship is approximately linear and can be reduced to a linear one:
$$
\begin{equation}
\begin{gathered}
I_{\text {out }}=I_b \tanh \left(\frac{\kappa}{2 U_T}\left(V_1-V_2\right)\right) \\
I_{\text {out }} \approx g_m\left(V_1-V_2\right) \\
g_m=\frac{I_b K}{2 U_T}
\end{gathered}
\end{equation}
$$

![[Transconductance amplifier 2023-01-25 14.23.00.excalidraw.svg|400]]
%%[[Transconductance amplifier 2023-01-25 14.23.00.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Transconductance amplifier 2023-01-25 14.23.00.excalidraw.dark.svg|dark exported image]]%%

$g_{m}$ is the [[transconductance]] of the amplifier (it has the dimensions of a conductance), but the outpu 