Based on the 3 layer retina circuit. Ganglion cell - bipolar cell - rod/cone
![[Pasted image 20230206132638.png]]

## source follower receptor
![[Pasted image 20230206132954.png]]
![[Pasted image 20230206133113.png|600]]

## Transimpedance photoreceptor
- Photodiode has a large capacitance so a small photocurrent takes a long time to change $Vs$
- High gain ffedback loop clamps $Vs$ and speeds up the response by increasing $g_{s}$ of M1
![[Pasted image 20230206133459.png]]
## Miller effect

In electronics, the Miller effect accounts for the increase in the equivalent input capacitance of an inverting voltage amplifier due to amplification of the effect of capacitance between the input and output terminals
(Parasitic gate to drain capacitance of M2 , in our case)

The solution is a cascode (added M4)

![[Pasted image 20230206133935.png]]