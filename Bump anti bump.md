 
**Input:** $\Delta V$
**Output:** $I_{1}$, $I_{2}$ and $I_{out}$
**Settings:** $V_{b}$
**Notes:** $I_{1}+I_{2}$ form the antibump output with the same dynamic range.

Intuitively, we can understand the operation of this circuit as follows: The three currents must sum to the bias current $I_{b}$; hence, the voltage $V_{c}$ follows the higher of $V_{1}$ or $V_{2}$. The series-connected transistors M1 and M2 form the core of the same analog current correlator that is used in the current-correlator.When $\Delta V=0$ current flows through all three legs of the circuit. When $|\Delta V|$ increases the common node voltage $Vc$ follows the higher between V1 and V2, shutting off $Iout$ (The transistor connected to the lowest V1 V2 suhts off). 
![[Pasted image 20230201135222.png]]

![[Pasted image 20230201150251.png]]
