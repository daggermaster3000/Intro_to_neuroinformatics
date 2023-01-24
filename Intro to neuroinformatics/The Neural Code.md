```toc
```

## Overview
In the brain there is a lot of encoding/ decoding happening between the different brain areas before behavior is generated

The problem of neural coding is to elucidate “the **representation** and **transformation** of information in the nervous system”.

### The coding metaphor
![[Pasted image 20230121154041.png]]

Considering three elements:
- **Correspondance**: The technical sense of a code is a ==correspondance between two domains== (fex: visual signals and spike trains). We call this relation a code to mean that spike trains specify the visual signals, as in a cipher: one can theoretically reconstruct the original message (visual signals) from the encoded message (spike trains) with some accuracy, a process called **decoding**

- **Representation:** Not all cases of correlations in nature are considered instances of coding. (ex: does rain encode atmospheric pressure? probably not)

- **Causality:** We would not say that visual signals encoderetinal spike trains, even though this would comply with the technical sense. This is because the communication metaphor implicitly assumes a causal relation between the original message and the encoded message. Her spike trains result from visual signals by a causal process (transduction)

#### Encoding
**How does a stimulus cause a pattern of responses?**
We build a approximate mechanistic model of the world (We learn to represent all the stimuli out there internally in a matter that is useful for us)
$$
P(\mathrm{Response}|\text{stimulus})\to \text{Encoding}
$$
#### Decoding 
**What do the responses tell us about the stimulus?**
How can we reconstruct the stimulus
$$
P(\mathrm{stimulus}|\text{Response})\to \text{Encoding}
$$
#### Finding the stimulus-response realtion
![[Pasted image 20230121155901.png|400]]

- [[Encoding motor output in primates]]
- [[Recording Neuronal Responses in Cat VI]]
- [[Edge Filters in Primate Visual Cortex]]
- [[Encoding complex Stimuli in Primate V4]]
- [[Encoding Visual Stimuli in the Human Brain (area MTL)]]
- [[Encoding Spatial Information in Rat Hippocampus.]]

### Representation and transmission of information
The Paramecium is a “Swimming neuron”. It has the task to follow a certain concentration gradient. It has ciliae on the outside (they move constantly, uncoordinated). It has a mechanism how it encodes this concentration gradient, so that it triggers a spike on the membrane => depending on where it spikes on the membrane, it synchronizes the ciliae on the membrane in a different way so that it moves towards the concentration gradient.

## Temporal and rate coding
![[Pasted image 20230121172958.png]]
### Rate
![[Pasted image 20230121173021.png]]
<u>Rate coding:</u> refers to information being carried by the firing rate. (important for plasticity)

### Temporal 
![[Pasted image 20230121173034.png]]
Different ideas:
- (i) much of the information may be transmitted by a neuron during certain small intervals of time
- (ii) synchronous, or quasi-synchronous, firing of neurons within and across ensembles may carry important information
- (iii) the precise timing, or pattern, or spikes may carry information

<u>Phase coding:</u> For every spike you can look where does it spike in the phase of the oscillation

<u>Synchrony coding:</u> How much are spikes synchronized

<u>Time to first spike coding:</u> How much time does it take for the first spike to fire after the stimulus


### Temporal vs rate
**Rate coding example:**
![[Pasted image 20230121173918.png]]
**Temporal rate hybrid example:**
![[Pasted image 20230121174053.png]]

- [[Phase (mostly) coding in hippocampus]]
- [[Sound Localization by measuring the Interaural Time Difference (ITD)]]
- [[How to investigate the Stimulus Encoding of a Neuron]]
- [[Grid cells]]
