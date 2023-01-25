## Summary

**Input:** $\Delta V =V_{1}-V_{2}$
**Output:** $I1$ and $I_{2}$
**Settings:** $V_{b}$ for $I_{b}$

This circuit is similar to the source followe, only the biais current is shared between $M_{1}$ and $M_{2}$. If all MOSFETs are operated below threshold and in saturation and we assume that and have the same subthreshold slope factor $\kappa$.
![[Differenial pair 2023-01-25 11.03.54.excalidraw.svg]]
%%[[Differenial pair 2023-01-25 11.03.54.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Differenial pair 2023-01-25 11.03.54.excalidraw.dark.svg|dark exported image]]%%
The dependance of $I_{1}$ and $I_{2}$ can be seen in the next graph, where the curves have a sigmoidal shape. For small $\Delta V$ the behaviour is linear, and for large $\Delta V$ there is saturation at $I_{b}$.


## Uses
Compressive non-linearities are very useful for implementation of different functions (ex: [[neural networks]]). The output currents depend only on the difference of the input voltages: The circuit has a small [[common-mode]] sensitivity. Given that voltages are [[differential-mode]] rather than absolute quantities such a property is very useful.