When we look inside the brain, we see a bunch of neurons and a mess of connectivities. It’s really hard to identify the connections among neurons, and with this information to understand how the brain works. We don’t learn how the brain works by studying neurons, the same way that just by studying transistors we do not know how a computer works. We know the brain does processing but we don’t know how it works. The bottleneck to understand brain is probably that we do not have the right abstractions to understand it.  [[Substrates of neural plasticity#McCulloch & Pitts neuron (perceptron)]] developed a computational model of a biological neuron in 1943. The McCullochPitts neural model is also known as linear threshold unit/gate. It models a neuron with a set of inputs and one output.

## Perceptron learning algorithm
This algorithm is called a learning algorithm because we use it to define the weights of the neurons. This learning is just a definition of parameters, and can be seen as an optimization, where we have some guess and we want to improve it.

**Supervised error correcting**

```python
#set of inputs from a truth table fex
x = ["input_sets",[[1,0],[0,1],[1,1]]]
desired = ("desired outputs",[1,1,1])
w = "weights.random"
a = "learning rate"
while !convergence:
	#we iterate over every input (in every set then move to the next)
	for i in inputs:
		if output != desired:
			if x==1 and w.x < 0:
				w = w+x*a
			if x==0 and w.x >= 0:
				w = w-x*a
	
```
These single units can separate two classes if they are linearly separable (i.e., if a solution exists). The Perceptron Learning Algortithm must converge, i.e., it will update the weights a finite number of times.

**Proof it converges:**
TODO...



## [[Hopfield networks]]

## [[Feed forward networks]]

## [[Boltzmann machines]]
