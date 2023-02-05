**Integrators** are a class of low pass circuits that filter out the high frequency components of the signal (often noise). **Differentiators** filter out the low frequency components of the input signal and respond well to its changes. Both are used to implement adaptation in neuromorphic systems. Adaptation is ubiquitous in neural systems and allows a system to optimize its dynamic range against the characteristics of the prevailing input signal.

## Integrators (low pass filters)
We can see below that for a short time and high frequencies, we get an integral like behaviour to a step response, but for long times, it just follows the input.
![[Pasted image 20230204125443.png|400]]
![[Pasted image 20230204125640.png]]
![[Pasted image 20230204125709.png]]
![[Pasted image 20230203191648.png]]
The classic follower integrator above, once made, cannot change its time constant. The transconductance amplifier below has an adjustable time constant (by setting $V_{b}$). 
![[Pasted image 20230203191206.png]]
It is made up of a unity gain follower and a capacitor on the output node. From KCL we get:
![[Pasted image 20230203192027.png]]

In small signal regime the amplifier operates in it's linear range. So we get:
![[Pasted image 20230203192813.png]]
Often analyzed using [[Heaviside]]
Small signal we see an exponential response (or a bigger one):
![[Follower integrator and differentiator 2023-02-04 13.22.25.excalidraw.svg]]
%%[[Follower integrator and differentiator 2023-02-04 13.22.25.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Follower integrator and differentiator 2023-02-04 13.22.25.excalidraw.dark.svg|dark exported image]]%%

Examples from the lab :
![[Pasted image 20230204133437.png]]
![[Pasted image 20230204133505.png]]


## Differentiators (high pass filters)
It acts as a differentiator for long times and low frequencies, for short times it just follows the input.

![[Pasted image 20230204125410.png]]

## Bode plots
After analyzing in the s pane with Heaviside stuff, we can plot the response vs the frequencies:
![[Pasted image 20230204130408.png]]
And we can see the filtering behaviour