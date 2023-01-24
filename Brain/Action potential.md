```toc
```
## Overview
Action potentials are needed to pass information on reliably (since through the passive way it would always decrease over distance). The AP is initiated at the Axon initial segment or axon hillock (= axon right after soma) through a strong local depolarization, then hyperpolarization. This then travels along the axon until it reaches the presynaptic terminals. Once the presynaptic terminal is depolarized there is a cascade of events that can lead the postsynaptic cell to be depolarized.

• Occurs in axons: travels away from soma
• Lasts 1-2 ms
• All-or-none: $I_{e}$ ↑ ⟹ AP occurs sooner, but same shape
• Stimulus intensity encoded as AP rate ($r_{AP}$)
- All or none principle
• Several phases:
![[Action potential 2023-01-20 10.47.41.excalidraw.svg|600]]

Increasing $I_{e}$ will just make the AP occur sooner (bc threshold is reached earlier).

## Hodgkin and Huxley hypothesis
The main idea is that ion channels are responsible for the rising and falling phases. But which for which?
• Rising phase: $g_{Na}$ ↑ or $g_{Ca}$ ↑
• Falling phase: $g_{Ca}$ ↓ or $g_{Na}$ ↓ or $g_{K}$ ↑ or $g_{Cl}$ ↑
To test this, Hodgkin and Huxley used voltage clamp to measure each conductance in a giant squid axon.

### The giant squid axon
The fact that it is really thicc allows fast conduction and is an alternative to myelin (has no myelin). It is needed in an escape system.

### Voltage clamp and space clamp
• A new technique invented by Hodgkin and Huxley
• Fast feedback system to fix V & measure I
• Makes the axon isopotential
• ⟹ same AP mechanism, but not traveling

**Set V measure I**
![[Pasted image 20230120111450.png]]
One wire to inject current and make the axon isopotential and another to measure the voltage.

#### Experiment 1

**Injected currents**
![[Pasted image 20230120112349.png]]
(Here the threshold is not crossed)
$I_{c}^1$ : Depolarize membrane (add+charge inside) (capacitive current it is called)
$I_{L}$: Compensate for leak current (V ≠ Vrest) => because the neuron is trying to go back to resting potential 
$I_{c}^2$ : Repolarize membrane (remove charge added with $I_{c}^1$)

#### Experiment 2
![[Pasted image 20230120112547.png]]
$I_{c}^1$ : As above, but more charge added 
$I_{L}$: Axon wants to depolarize => need to inject negative $I_{e}$ to keep $V = Vset$ ($I1$) 
$I_{c}^2$ : Axon wants to hyperpolarize => need to inject positive $Ie$ to keep $V = Vset$ ($I2$)

**Hypothesis:** 
$I_{1}≈I_{Na}$, $E_{Na}≈ 50 mV$ and $I_{2}≈I_{K}$, $E_{K}≈ -80 mV$ with conductances that are both voltage and time dependent.
Note: no direct comparison of Ie to VAP because here V is clamped!

### Identifying the currents
The approach to do this is to eliminate an Ion from the solution and measure, then check the difference with the previous graph. They did the experiment in $Na+$ free seawater. That eliminates the current of sodium $I_{Na} (for Vset=0)$.
![[Pasted image 20230120114522.png]]
Therefore, $I_{Na}$ is responsible for the depolarization (or at least part of it).
**Note:**
Nowadays we use drugs to block specific channels (ex: TEA for $Na$ and TTX for $K$)

### From current to conductance
Once we obtain the specific currents for the respective ions, we use ohm's law to calculate the conductance (For a $V_{SET}$ and over time).
![[Pasted image 20230120121442.png]]
![[Pasted image 20230120121451.png]]![[Pasted image 20230120121905.png]]
$K^+$ channels open more slowly and **hyperpolarize** the cell and just stay open (no inactivation). The bigger the $V_{SET}$ the faster the opening (for both channels). $Na^+$ channels **depolarize** the cell when opened.

### Towards a mechanistic model
How do we explain the voltage and time dependence of $g_{Na}$ and $g_{K}$ ?

**Two possibilities**
1. Single channels have variable and continous permeabilities
2. Single channels are either open or closed, where $p(open) = f(V)$

Today we know 2 is correct because:
1. [[Patch-clamp]]
2. Inferred by H&H

### Persistent and transient conductances
![[Pasted image 20230120123819.png]]

#### Persistent 
![[Pasted image 20230120123942.png]]

**Time dependency**
![[Pasted image 20230120124055.png]]
![[Pasted image 20230120124105.png]]

##### $K^+$ Conductance
$P_{k} = n^4$
![[Pasted image 20230120124302.png]]
#### Transient
##### $Na^+$ Conductance
![[Pasted image 20230120124436.png]]
![[Pasted image 20230120124446.png]]

#### Overview
Here is a graph of the solutions for the different parameters and a given voltage.
$\tau_{n}(V) \frac{dn(t)}{dt} = n_{\infty}(V)-n(t)$

![[Action potential 2023-01-20 13.41.57.excalidraw.svg|900]]
This model fits well the measured conductances

#### Voltage dependance
Determine $\alpha_{n}(V)$ and $\beta_{n}(V)$ (open and closing rates)
![[Pasted image 20230120140354.png]]
![[Pasted image 20230120140438.png]]
Open -> close may not require the same energy as the inverse

Here we can see the time constants and the opening probabilities of the gates.
![[Pasted image 20230120140416.png]]
- $\tau$ is much smaller for $Na$ than for $K$ meaning $Na$ are quicker to open and dominate in the begining.
- The $m$ and $n$ gates open with depolarization
- The $h$ gate closes with depolarization

## The HH model
![[Pasted image 20230120141800.png]]
### Fitting
![[Pasted image 20230120142026.png]]

### Predictions

#### Potassium channel
They effectively predicted the number of subunits ($k = 4$)

#### Action potential
There is a feedback loop that generates the AP. The AP is not continuously generated because potassium and leak currents compensate sodium currents. As soon as the sodium channels start to dominate over the others the threshold is reached
![[Pasted image 20230120142233.png]]

#### Refractory period
For a few milliseconds just after an action potential has been fired, it may be virtually impossible to initiate another spike. This is called the absolute refractory period. For a longer refractory period interval known as the relative refractory period, lasting up to tens of milliseconds after a spike, it is more difficult to evoke an action potential. Because $g_{Na}$ is still closed and $g_{K}$ is still open
![[Pasted image 20230120142418.png]]

#### Action potential propagation
![[Pasted image 20230120142912.png]]

#### AP collision
![[Pasted image 20230120143004.png]]

![[Pasted image 20230120143020.png]]

## Single neuron computations
![[Pasted image 20230120143107.png]]