# Neural computation cost

We have a general idea regarding resource-constrained control which includes neural computation cost in control theory. 
The easiest example is to include neural computation cost in utility function as a cost term in the frame of reinforcement learning.
There are a lot of researches that includes behavior action cost in reinforcement learning framework such that 
the optimal action is determined in thea way jointly to maximize the reward and to minimize the action cost. 


We hypothesize that when the brain makes a decision, 
it comes up with the action not only that maximizes the long-term cumulative reward
but it also minimizes neural computation cost in order to increase energy efficiency in brain. 
When we say the neural computation cost, there are multiple approaches to consider it:

1) **physical energy consumption**, e.g., the number of spikes in the population of neurons

2) **conceptual distance**, e.g., behavior habit requires less amount of brain energy to come up with your decision. 
(Minhae's question: Can we connect this to predictive coding?)
- [Anderson, John R. "Is human cognition adaptive?." Behavioral and Brain Sciences 14.3 (1991): 471-485.](http://act-r.psy.cmu.edu/wordpress/wp-content/uploads/2013/09/Anderson91.pdf)
- Tom Griffths (Princeton Univ, Psychology Dep.): https://psych.princeton.edu/person/tom-griffiths
    - [Lieder, Falk, and Thomas L. Griffiths. "Resource-rational analysis: understanding human cognition as the optimal use of limited computational resources." Behavioral and Brain Sciences (2019): 1-85.](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/resourcerational-analysis-understanding-human-cognition-as-the-optimal-use-of-limited-computational-resources/586866D9AD1D1EA7A1EECE217D392F4A)
- Mehdi Keramati (City Univ. of London, Psychology Dep.): https://www.city.ac.uk/people/academics/mehdi-keramati#profile=publications
    - [Adaptive integration of habits into depth limited planning defines a habitual goal–directed spectrum
Keramati, Mehdi, et al. "Adaptive integration of habits into depth-limited planning defines a habitual-goal–directed spectrum." Proceedings of the National Academy of Sciences 113.45 (2016): 12868-12873.](https://www.pnas.org/content/113/45/12868)
3) **the depth of thinking**, e.g., how many rollouts do you compute in Monte Carlos Planning

I've been talking about this topic with many computational neuroscientists and there are a variety of views for it:

1) **energy-efficient hardware for deep neural network**: 
if the machine learning algorithm considers physical energy consumptions, then it becomes critical when you build a hardware that performs the algorithm.
2) **regularization term to explain decisions from animals**:
The animal's decision is not always the optimal in terms of control model and optimization theory. 
In such case, a few researchers include regularization term to claim the animal's decision was the optimal and
explain the regularization term as neural computation cost. 



 ### Further references
[Lloyd, Kevin, and Peter Dayan. "Interrupting behaviour: Minimizing decision costs via temporal commitment and low-level interrupts." PLoS computational biology 14.1 (2018): e1005916.](https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1005916&type=printable)
 
 