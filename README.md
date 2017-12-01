# Udemy-DeepLearning

Download Anaconda Navigator
Primary IDE will be spyder within the Anaconda suite

Section 1
The Neuron
In a real neuron, there are three parts:
- Dendrites (Receiver)
- Neuron
- Axon (Transmitter)
Neurons connect dendrites to axons to transmit information. (In real life, they don't actually touch). The connection is called the 'Synapse'. The connections between neurons are going to be called synapses.

The neuron in deep learning will have several input values, and have an output value. Input values/variables are independent from each other, which come from single variables. They need to be standardize, which means to have a mean of 0 and a variance of 1 (Gaussian distribution). Sometimes, the input layer should be normalized instead, depending on the scenario. Subtract minimum variable and divide by the maximum minus minimum (range) to get values between 0 and 1. This way, the input values are going to be close to each other. Read "Efficient Backprop" - Yann LeCun.

The output value can be:
- Continuous (price)
- Binary (yes/no)
- Categorical (In this case, there will be several output variables representing the different categories).

Input values (single observation) -> Neuron -> Output value (single observation).

Synapses between input values and neurons will be assigned weights. This is how neural networks learn. They are the things that get adjusted in the process of learning. This is where gradient decent and back propagation are in play. Signals go into the neuron, and a few things happen:
- All the values passed on from input are summed.
- Then it applies an activation function, which is assigned to the specific neuron, not the layer.
- Then the neuron passes on that value, or decides to not pass on the value.
- This process continues for thousands of times.

The Activation Function
How do Neural Networks Work (example)
How do Neural Networks learn?
Gradient Descent
Stochastic Gradient Descent
Backpropagation
