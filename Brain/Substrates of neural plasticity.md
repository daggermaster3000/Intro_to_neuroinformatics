```toc
```

# At the brain level
![[Pasted image 20230123154157.png]]

## The hippocampus as a model to study learning and memory
![[Pasted image 20230123162600.png]]
The Hippocampus si much larger in mice than in humans. The main structures and pathways however are preserved

### Henry Gustave Molaison (H.M.)
His Amygdala, hippocampal gyrus and anterior two thirds of the hippocampus were removed after having many dangerous seizures. He then suffered a Severe anterograde amnesia. Even though he had normal STM, and normal LTM prior to surgery, he could not transfer from STM to LTM, therefore he could not consolidate new declarative knowledge. He was still capable of acquiring implicit knowledge. They concluded that the Hippocampus is not a permanent storage area for explicit knowledge. The HC is involved in consolidation, a longerterm process taking months to years. Consolidation is understood to involve biological changes taking place in those other areas of cortex, once this has fully taken place, the hippocampus is not required for retrieval
![[Pasted image 20230123162754.png]]

# At the circuit/neuron levels
![[Pasted image 20230123162953.png]]

## McCulloch & Pitts neuron (perceptron)
It is very well known that the most fundamental unit of deep neural networks is called an _artificial neuron/perceptron_. But the very first step towards the _perceptron_ we use today was taken in 1943 by McCulloch and Pitts, by mimicking the functionality of a biological neuron. 
- It implements a linear descision boundary (hyperplane)
- The weights and biaises definfe the boundary
- Can be trained on labeled datasets

he difference between the McCulloch& Pitts Neuron and the Perceptron is that in the McCulloch& Pitts Neuron the Inputs can only be 0 or 1 and in the Perceptron they can be anything.

![[Pasted image 20230123163043.png|400]]
The neuron just sums the inputs and activates or not based on a threshold. 
![[Pasted image 20230123163555.png|400]]
We can then implement decision boundaries
<u>Example:</u>
![[Pasted image 20230123163806.png|500]]
But only linear classification can be performed (xor is unsolvable)
**Unsolvable:**
![[Pasted image 20230123164104.png]]
### Perceptron learning algorithm
![[Pasted image 20230123163904.png|400]]
