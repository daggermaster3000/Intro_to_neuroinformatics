We understand more or less how individual neurons/units process information but not really how the whole information is processed.

## Neural encoding of information
Humans are capable to learn things that we were not evolved for, for instance, to fly a drone. This is an inspiration for us. It seems to exist a general solution for solving problems: the brain. 

Neurons respond to combinations of properties, features, aspects of the situation, etc. Neurons are tuned to a set of values for the parameters they care about. For example, a neuron can be “tuned” to a moving bar at a certain angle in its perceptive field. It also responds to a certain velocity, position $(x,y)$, bar width, etc. Neuronal response is called firing rate $r(t)$. Although neurons are tuned, they aren’t super picky about the exact values. And, experimentally, neurons do not code a single atribute but a combination of them.

### Population code 
Information is encoded by a group (population) of neurons. A group includes all neurons in that area. The values are encoded by the pattern of activity. This code of information by population is our understanding of how neurons represent information, but this is not how we do it, typically, in an engineering process. Given a parameter, and looking at the neurons tuned to some value of this parameter, we can define tunning curves. 
![[Pasted image 20230126150221.png|600]]
In Figure 45a, we see in the x axis the parameter we are evaluating, and in the y axis, the activity of one single neuron (firing response). Doing this process to many neurons, we can sort 69 them regarding to the parameter we are looking for. In Figure 45b all neurons were ordered accordingly to the response to a specific parameters. The read out of information given a population code is an easy way to figure out what the population is doing, it is robust to noise, however, requires a lot of units.


![[Pasted image 20230126150510.png|600]]
Consider now an example were we want to correlate the angle of the eye (E), the position of an object on retina (R) and the head-centered direction (A), as showed in Figure 46a. This is an example of processing that is not feed-forward. 

How can a relation like $A = E + R$ be represented? 

Say R, A and E are encoded by population codes, i.e., by population of units, each tuned to a particular value of that variable. Considering these three variables, we can use units that are tuned to combinations of A, E and R. The set of (A, E, R) triples that satisfy the relation will be active. This can be seen in Figure 46b: when certain neuron fires for a parameter in R, another one can fire for a parameter in E and this can result in the firing of neurons in E, after learning. Given any two information in this relation, the third one can be recovered. There is no obligatory order. R, A and E have the following relations: 
- $R = A − E$
- $A = E + R$
- $E = A − R$

## Function approximation
The brain must recover the third variable from the two noisy others. 
**example:** Locating a sound source

## Cue integration
Big noise in all inputs, the brain must refine the estimates of all the inputs. -> attractor network is useful for this. Given the noisy 