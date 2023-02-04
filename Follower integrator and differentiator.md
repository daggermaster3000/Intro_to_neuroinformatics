**Integrators** are a class of low pass circuits that filter out the high frequency components of the signal (often noise). **Differentiators** filter out the low frequency components of the input signal and respond well to its changes. Both are used to implement adaptation in neuromorphic systems. Adaptation is ubiquitous in neural systems and allows a system to optimize its dynamic range against the characteristics of the prevailing input signal.

## Integrators
![[Pasted image 20230203191648.png]]
The classic follower integrator above, once made, cannot change its time constant. The transconductance amplifier below has an adjustable time constant (by setting $V_{b}$). 
![[Pasted image 20230203191206.png]]
It is made up of a unity gain follower and a capacitor on the output node. From KCL we get:
![[Pasted image 20230203192027.png]]

In small signal regime the amplifier operates in it's linear range. So we get:
![[Pasted image 20230203192813.png]]

## Differentiators

