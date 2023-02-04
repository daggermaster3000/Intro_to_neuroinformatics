
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

**Explanation:**
- Transistors M1 and M2 discharge nodes $V_{d}$ and implement inhibitory feedback.
- M3 and M4 charge $Vc$ and implement excitatory feedforward. 
- The circuit selects the largest input current $Iin$ because the cell in question provides $I_{out} \approx I_{b}$ and suppresses all other output voltages and currents. Also it its $Vd$ determines $Vc$  



![[Pasted image 20230204155008.png]]
## Conditions

- $I_{in_{1}} = I_{in_{2}}=I_{in}$
This means the current flowing through both transistors is equal (because m1 and m2 are both tied to $Vc$) and so their drain voltage smust take the same value. So output transistors M3 and M4 will have the same $Vgs$. ($=V_{d}-V_{c}$). 
For n cells: each $Iout=\frac{I_{b}}{n}$

- $I_{in_{1}}\gg I_{in_{2}}$

![[WTA 2023-02-04 16.00.01.excalidraw.svg]]
%%[[WTA 2023-02-04 16.00.01.excalidraw.md|🖋 Edit in Excalidraw]], and the [[WTA 2023-02-04 16.00.01.excalidraw.dark.svg|dark exported image]]%%