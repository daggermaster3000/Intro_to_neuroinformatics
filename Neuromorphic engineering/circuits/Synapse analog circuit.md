For implementing slow neuronal dynamics.

## Neural network models

![[Synapse analog circuit 2023-02-05 12.23.54.excalidraw.svg]]
%%[[Synapse analog circuit 2023-02-05 12.23.54.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Synapse analog circuit 2023-02-05 12.23.54.excalidraw.dark.svg|dark exported image]]%%

The analog of a synapse in VLSI is that of a multiplier, the [[Gilbert multiplier]]

## Pulse based neural network synapses
![[Pasted image 20230205123516.png]]

In a pulse based network, the weighted contribution of a synapse can be implemented using a single transistor.
- Pfet for excitatory synapse
- Nfet for inhibitory synapse
- The weight can be set by changing $Wi$ the biais voltage or $\Delta t$.

## Exponentially decaying integrator circuit
![[Synapse analog circuit 2023-02-05 12.43.15.excalidraw.svg]]
%%[[Synapse analog circuit 2023-02-05 12.43.15.excalidraw.md|🖋 Edit in Excalidraw]], and the [[Synapse analog circuit 2023-02-05 12.43.15.excalidraw.dark.svg|dark exported image]]%%


## The diff. pair integrator circuit

![[Pasted image 20230125152906.png]]