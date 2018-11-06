# the-learning-map-of-nerual-network-1

### (1) Neural networks: Definitions, motivation, properties



1. Neural networks: Definitions and motivation
<br> Neural: Of, or related to nerves, neurons.
<br> Neuron: A highly-specialized cell that can transmit and receive information through electrical/chemical
signaling. The fundamental building block of the brain.
<br> Nerve: A bundle of several neurons (more precisely, bundle of axons of several neurons).
<br> Network: A set of nodes and the connections between them.

2. Purposes
<br> Neural networks can be used for a variety of purposes, e.g. classification (identifying the label/class of
an input among a given set of labels/classes), clustering (finding different classes among unlabeled data),
prediction (estimating the future values of a process given past values), strategic decision making, so on.
But in general, mathematically, we have an input, the network, and an output...

3. Some properties of artificial neural networks:
<br> • Non-linearity: The relationship between the input and the output of the network is not a linear
relationship.
<br> • Learning.
<br> – Supervised learning: Learning with a teacher. Involves modification of the parameters of the
network through a set of training samples, with each sample consisting of an input pattern and
associated desired response.
<br> – Unsupervised learning.
<br> • Adaptivity: Adaptation of the free parameters to the changes in the environment.
<br> • Evidential Response: The network can also provide a confidence level to its decision regarding the
input pattern.
<br> • Fault tolerance: When you get hit in the head, many of your neurons die, but you may still continue
your daily routine. On the other hand, kill a transistor in a CPU, and the entire CPU is dead too. Thus,
in principle, a neural network exhibits a graceful degradation in performance rather than catastrophic
failure.
<br> • VLSI implementability. Massively parallel nature of neural networks makes it a successful candidate
for VLSI implementations.
<br> • Neurobiological analogy: Neurobiologists look to (artificial) neural networks as a research tool for the
interpretation of neurobiological phenomena. On the other hand, engineers look to neurobiology for
new ideas to solve problems more complex than those based on conventional hardwired design.

_____

### (2) The perceptron and its training
1. Rosenblatt’s percepton. (supervised learning)
2. Logical NOT/ Logical AND/  Logical OR/ Any logical product term
3. Learning Algorithm for the Perceptron
******
### (3) Introduction to Multilayer networks
Example, XOR cannot be done via a single layer (by one perceptron), but we showed a 2-layer network that can do XOR.

### (4) Learning
1. In general, learning is a systematic method to change/update the weights so that the network can accomplish the desired task after a certain number of learning steps.
2. There are basically three different types of learning: 
* _Supervised learning_: For each pattern (member of the training set), we know what the correct output
should be, and we update the weights accordingly.
* _Unsupervised learning_: We do not have any correct output information. The learning algorithm finds
(by itself) similarities between different training samples, and classifies them accordingly (usually this
classification is called “clustering” when talking about unsupervised learning). In certain contexts, the
process is also referred to as self-organization.
* _Reinforcement learning_: We may think of y1, y2, . . . (the outputs) as the actions we choose (e.g. moves
of a chess game). Each action/output will incur a different reward (some outputs may be good/some
may be bad, chess piece taken good, queen lost bad), and a new different observation of the environment (the new chess board configuration after the opponent also makes his move - note that this may thus
be random). Depending on the rewards and the new observation, we update the weights.
3. In terms of how we update the weights, there are basically two different types:
* _Stepwise learning_: One input is given, output is observed and the weights are updated. Then, for the
next input, the last updated weights are used (as in the description above or the perceptron training
algorithm). In this case, there is no need to store the weight increments. This is also called on-line
learning.
* _Batch learning_: One input is given, necessary weight increments are found, but the weights are not
updated. When the next input is given, previous weights are used, and again the necessary weight
increments are found. This process is repeated till the end of an epoch. At the end of epoch, the
weight increments are added to find the total increment, and added to the weights used within the
epoch. This is sometimes called as off-line learning.

