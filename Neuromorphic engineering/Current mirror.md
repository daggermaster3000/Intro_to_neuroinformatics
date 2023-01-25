![[Pasted image 20230125104100.png]]
This circuit consists of a diode connected MOSFET that has a common gate node with another MOSFET of the same type. If both MOSFETS have fixed source voltages and are in [[saturation]], they act as current sources.

>They will source the same current if they are the same size and $V_{s_{1}=V_{S_{2}}}$

The input current $I_{in}$ sets $V_{g}$ through the $M_{1}$ diode connection and therefore $I_{out}$.

>The output current can be scaled (linearly to the width to length ratio) by choosing different transistor sizes, or (exponentially) by choosing different source potentials $V_{s_{1}}$ and $V_{s_{2}}$


The dependence of the output on the difference in the source potentials is described by (if $M_{2}$ is in saturation):

$I_{out} = e^{(V_{s_{1}}-V_{s_{2}})/U_{T}}I_{in}$
