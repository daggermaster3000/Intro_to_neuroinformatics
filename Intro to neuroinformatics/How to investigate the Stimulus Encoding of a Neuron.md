```toc
```

## Overview
We want to know: How is the stimulus s(t) transformed into the neuron firing rate r(t)? Then we know how the information is encoded.
![[Pasted image 20230121174617.png]]
We can attempt this f.e. by measuring the cat visual cortex in vivo while showing stimuli. But there are many factors that influence how the neuron fires beside the stimulus:

## Main factors
Factors that influence the Neuron firing rate: 
- Stimulus s(t) 
- Noise (e.g. synaptic noise) 
- Experimental Confounds 
- Biophysical Properties of the neuron 
- Neuronal Activation function 
- Stimuli are high-dimensional in space and time and complex (we don’t know where exactly the cat looks) 
- Recurrent/ Network Effects (brain is in a different state when already seen the stimulus)
![[Pasted image 20230121174852.png]]

## Relations
The simplest relation between $r(t)$ and $s(t)$ is:
$$
r(t) = f(s(t))  \space \space \space[f(s(t-\tau))]
$$
$f$ can be any type of function

## The neuron as temporal filter
![[Pasted image 20230121175550.png|400]]
![[Pasted image 20230121175652.png|600]]

#### Running avg filter
![[Pasted image 20230121175755.png]]

#### Leaky AVG filter
![[Pasted image 20230121180022.png]]

## Linear spatial filtering
Retina Ganglion Cells respond to a filter. If a stimulus has exactly that profile (innen hell& aussen dunkel), the neuron fires at its maximal intensity. For every pixel we take the value of the pixel and multiply it with the value of the filter (i.e. ganglion cell: everywhere zero, except in middle very high and in circle around very negative)
![[Pasted image 20230121180344.png]]

![[Pasted image 20230121180119.png]]

![[Pasted image 20230121180505.png]]

![[Pasted image 20230121180542.png]]

#### Example
![[Pasted image 20230121180608.png]]

### Combining space and time
You integrate over space and time => in brain there are both
![[Pasted image 20230121180648.png]]

## Non linear spatial filtering
![[Pasted image 20230121180833.png]]
$g()$ is non linear, $s()$ is temporal filter, $f()$ is spatial filter
## Quiz
![[Pasted image 20230121181039.png]]


## Taking into account spatio-temporal filters
![[Pasted image 20230122114337.png]]
Data is being compressed from High-Dimensional Representation to Neuronal Firing “Low 
![[Pasted image 20230122114354.png|500]]
Dimensionality” => Understanding this process how the data is compressed into these neural networks is key 

There are two ways of thinking about it:
![[Pasted image 20230122114541.png]]
At the **neuronal level** or at the **population level**.

- **population coding** : information available from ensemble that goes beyond simple summation of individual signals
- [[Measuring Population Activity in vivo]]
- [[Finding the max neuronal response (PCALDA)]]
