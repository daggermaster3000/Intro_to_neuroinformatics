Boltzmann Machines were invented in 1985 but not by Boltzmann. The name is given because these units use a Boltzmann distribution in their sampling function. These units are similar to Hopfield Networks, however, they have a **probability of being active**. When updating a unit, we set its value to zero or one probabilistically, following a sampling function. 
Behold the sampling functions:
![[Pasted image 20230126144343.png|300]]
Boltzmann machines do not converge, they do not reach a stable state. It can be seen as a system for sampling. It’s a way to do a random walking in the state space.

We want the units to forget previous states so the sampling is not biased, i.e., not similar to previous ones, thus really ”random”. While this sampling is nice, it is not useful as a memory, i.e., we don’t want to sample things randomly from our memory. We can define a network where the units have a real-valued activity level (ai ∈ [0, 1]), and also we can make time continuous, so ∂ai ∂t = θ(Σ) − ai . Using units like this, we can make a feed-forward network

(impractical for learning)