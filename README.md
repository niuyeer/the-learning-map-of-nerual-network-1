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

### (2) The perceptron and its training
1. Rosenblatt’s percepton. (supervised learning)
2. Logical NOT/ Logical AND/  Logical OR/ Any logical product term
3. Learning Algorithm for the Perceptron

### (3) Introduction to Multilayer networks
<br> Example, XOR cannot be done via a single layer (by one perceptron), but we showed a 2-layer network that can do XOR.

### (4) Learning
1. In general, learning is a systematic method to change/update the weights so that the network can accomplish the desired task after a certain number of learning steps.
2. * There are basically three different types of learning: *
<br> 1. Supervised learning: For each pattern (member of the training set), we know what the correct output
should be, and we update the weights accordingly.
<br> 2. Unsupervised learning: We do not have any correct output information. The learning algorithm finds
(by itself) similarities between different training samples, and classifies them accordingly (usually this
classification is called “clustering” when talking about unsupervised learning). In certain contexts, the
process is also referred to as self-organization.


