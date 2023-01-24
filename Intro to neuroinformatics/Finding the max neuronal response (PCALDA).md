```toc
```
Now we want to repeatedly sample the responses to a variety of stimuli so that we can characterize what feature combination triggers a spike or a behavior.

$$
P(response | stimulus) = P(response | s1, s2, s3,..., sn )
$$

![[Pasted image 20230122115217.png]]
We sample the stimuli signal and plot the intensity of the neuronal response of each feature on it's respective axis. This will help us characterize what feature combination triggers a spike or a behavior. We do this repeatedly. (so each point is the response of the neuron to each feature)
![[Pasted image 20230122122152.png]]
Either we know the type of stimuli presented, either we don't. This will define the type of approach we use next.
![[Pasted image 20230122122227.png]]

## Finding the single neuron response vector
![[Pasted image 20230122122945.png|500]]
### Linear Discriminant Analysis
We find the vector (**Neuronal response vector**) that discriminates the best both groups.
![[Pasted image 20230122123021.png|500]]
Next, we project every stimuli onto this vector
![[Pasted image 20230122123232.png|600]]

## Finding the IO function for a single neuron
![[Pasted image 20230122123351.png]]

### Using Bayes rule
![[Pasted image 20230122123814.png]]
In our case:
$$
P(\text{spike}|s_{1})=\frac{P(s_{1}|\text{spike})P(\text{spike})}{P(s_{1})}
$$

![[Pasted image 20230122124011.png]]
![[Pasted image 20230122124033.png|500]]

## Population distance metrics
Information depends on two factors: 
- Distance between two different feature/population responses (when similar: not much information encoded) 
- Variance: becomes very hard with big variance => more overlap, when small easier to decode
![[Pasted image 20230122124122.png|500]]
![[Pasted image 20230122124140.png]]
![[Pasted image 20230122124759.png]]

![[Pasted image 20230122124828.png]]

![[Pasted image 20230122124835.png]]
![[Pasted image 20230122124903.png]]
a)4 
b)4
![[Pasted image 20230122125150.png]]
c)4


