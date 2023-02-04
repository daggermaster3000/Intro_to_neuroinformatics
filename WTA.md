
# Network overview
A winner takes all circuit is a network of competing cells that reports only the response of the cell that has the strongest activation and supresses the response of all the other cells. It essentially implements a $max()$ function. Here we consider a cluster of excitatory neurons that innervate a global feedback inhibitory neuron (Fig.6.5). Implementations: selective attention, visual stereopsis, tracking and head direction detection.  
![[Pasted image 20230204150449.png]]
The transfer function of the inhibitory neuron is: 
![[Pasted image 20230204150626.png]]
Of course all units may have or not a linear threshold and this complicates things. 

# Current mode WTA circuit
![[Pasted image 20230204151741.png]]
**Facts**
current mode means that the voltages "adapt to the current that is flowing"
- continuous time analog circuit
- parralel processing of the inputs
- each cell is infact a [[current conveyer]]
- Can be extended to $n$ cells by connecting others to the $Vc$ node
- Input currents are applied using subthreshold pFETs
- **output:** all the $I_{outs}$ and all the $Vd$.

![[Pasted image 20230204155008.png]]
## Conditions

- $I_{in_{1}} = I_{in_{2}}=I_{in}$


- $I_{in_{1}}\gg I_{in_{2}}$
- 
