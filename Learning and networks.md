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



## Hopfield networks
The Hopfield Network, or Hopfield Model, was proposed by John Hopfield in the early 80s. He was trying to understand what neural networks do. When we look into the brain and how neurons are connected to each other, we do not see always a clear pathway, i.e., it is hard to think about the connections in the brain in terms of input-output. He thought about connecting units to each other in an all-to-all pattern and see what would happen. It is a form of a [[recurrent neural network]]


**Characteristics of hopfield networks**
- Every nodes are interconnected but not to themselves (diagonal of adjacency matrix is $0$)
- Weights are symmetric ($W=W^T$) (due to hebbian synapse strengthening)
- Biais is a unit that is always on
- Some states are stable and some are not. While in an unstable state, updating the network leads to a state change
- A stable state is a local minimum

### Associative memory
We are used to think about computation as a process that receives an input, does something and generates an output. However, this is not what we “see” in the memory process, for instance. It seems our memory works with Pattern Completion, also known as Content Addressable Memory or Associative Memory. This memory has no input-output relation: given any piece of it, we can recover the rest. An example is when certain smell can bring us a memory, even though the smell is only part of the memory. Hopfield Networks can be used to give us insights about how the memory works by having a highly connected network that computes with no input-output, but with states. The network has some dynamics that ¨walk” through a state space, i.e., the space of all the possible states. The Hopfield Network is dynamic and moves from one state to another until it arrives to a stable state (also known as an attractor). Having stable states help the network to recover information giving partial inputs.

- A Hopfield Network is an associative type of memory. Information is stored in the stable states as local minima. 
- It is important that information is distinct. 
- Associative memory has room for error but is still recognizable. Convergence to nearby stable states. 
- If some units are retrievable and all others are set randomly, the correct units will eventually set the wrong units right.


**Dynamics of the model**
- At each step, we chose q unit and update it's output


From:https://github.com/benelot/eth-intro-to-neuroinformatics-summary