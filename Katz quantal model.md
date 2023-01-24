**Synaptic transmission is stochastic: each successful event is the product of a unit event**

```toc
```
Much of the evidence leading to the present understanding of chemical synaptic transmission was obtained from experiments examining the release of ACh at neuromuscular junctions. These synapses between spinal motor neurons and skeletal muscle cells are simple, large, and peripherally located, making them particularly amenable to experimental analysis. Such synapses occur at specializations called end plates because of the saucer-like appearance of the site on the muscle fiber where the presynaptic axon elaborates its terminals (Figure 5.6A). Most of the pioneering work on neuromuscular transmission was performed by Bernard Katz and his collaborators at University College London during the 1950s and 1960s, and Katz has been widely recognized for his remarkable contributions to understanding synaptic transmission. Though he worked primarily on the frog neuromuscular junction, numerous subsequent experiments have confirmed the applicability of his observations to transmission at chemical synapses throughout the nervous system. When an intracellular microelectrode is used to record the membrane potential of a muscle cell, an action potential in the presynaptic motor neuron can be seen to elicit a transient depolarization of the postsynaptic muscle fiber. This change in membrane potential, called an end plate potential (EPP), is normally large enough to bring the membrane potential of the muscle cell well above the threshold for producing a postsynaptic action potential (Figure 5.6B). The postsynaptic action potential triggered by the EPP causes the muscle fiber to contract. Unlike the case for electrical synapses, there is a pronounced delay between the time that the presynaptic motor neuron is stimulated and when the EPP occurs in the postsynaptic muscle cell. Such a delay is characteristic of all chemical synapses. One of Katz’s seminal findings, in studies carried out with Paul Fatt in 1951, was that spontaneous changes in muscle cell membrane potential occur even in the absence of stimulation of the presynaptic motor neuron (Figure 5.6C). These changes have the same shape as EPPs but are much smaller![[Pasted image 20230120172616.png]]
The idea that EPPs represent the simultaneous release of many MEPP-like units can be tested statistically. A method of statistical analysis based on the independent occurrence of unitary events (called Poisson statistics) predicts what the distribution of EPP amplitudes would look like during a large number of trials of motor neuron stimulation, under the assumption that EPPs are built up from unitary events like MEPPs (see Figure 5.7B).

## Model
The discovery of the quantal release of packets of neurotransmitter immediately raised the question of how such quanta are formed and discharged into the synaptic cleft. Electron microscopy revealed, the presence of synaptic vesicles. Putting these two discoveries together, Katz and others proposed that synaptic vesicles loaded with transmitter are the source of the quanta. 

Approximately 10,000 molecules of neurotransmitter are contained in a single vesicle. This number corresponds quite nicely to the amount of ACh that must be applied to a neuromuscular junction to mimic a MEPP, providing further support for the idea that quanta arise from discharge of the contents of single synaptic vesicles.
1 EPP is made up of multiple MEPPs.

In short, a presynaptic action potential causes a postsynaptic EPP because it synchronizes the release of many transmitter quanta.

- One packet of neurotransmitter $= 1$ quantum 
- AP transiently increases in the probability of releasing $Nx$ quanta 
- Several quanta are available to be released 
- Each quantum gives approximately the same postsynaptic response called the “**Quantal Amplitude**” 
- Each vesicle contains the same amount of NT
- The average number of quanta released: $m=np$
	- $n =$ the number of quanta available for release 
	- $p =$ their average release probability 
=> this model is still being used
- Probability of $x$ units successfully contributing is given by the binomial distribution:
$$
P(\text{success} = x) = (\begin{matrix}
n \\
p
\end{matrix})p^x(1-p)^{n-x}
$$


## Failure analysis
Failure analysis reveals that neurons release many quanta of neurotransmitter when stimulated, that all contribute to the response
![[Pasted image 20230120173527.png]]![[Pasted image 20230120173539.png]]

## Random

### CNS synapses and quanta

**Modulating $Ca^{2+}$ concentration does not affect the minimal response in the CNS**
This is because if 1 vesicle is released in either condition, it will still have the same effect as 1 vesicle (as only zero or onevesicle is released in theory).

**Synapses in the CNS with multiple release sites can change release probability and thus the amplitude of the response**
More vesicles -> more NT -> more response (graded quantal levels)

**At the NMJ a single nerve can elicit a postsynaptic AP given multiquantal release, while at the CNS synapse (with low numbers of release sites) multiple synapses must cooperate, forces a network.**

### CNS synapses and miniature release

- Miniature release is produced in the absence of action potential stimulation.
- It is thought to reflect the release of a single vesicle.
- Can be stimulated by calcium entry but may not be required for release
- Commonly studied to gain insight into changes in receptors or release probability during synaptic plasticity experiments, although can be difficult to interpret.