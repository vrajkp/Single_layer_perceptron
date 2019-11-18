# **Single Layer Perceptron Network using Python**    

**Perceptron:**

![Perceptron Network](https://www.mathworks.com/help/deeplearning/ug/percept_perneur.gif)

**How Perceptron Model Works?**

- Perceptron Network is an artificial neuron with "hardlim" as a transfer function. It is mainly used as a binary classifier.
Here, our goal is to classify the input into the binary classifier and for that network has to "LEARN" how to do that. "LEARN" means the model has to be trained to do so. 

- For training, the network is provided with a bunch of inputs with already known outputs. As result is already known, the output of a network is compared with the already known results and with the help of the "Perceptron Learning Rules" model get trained. 

There are 2 functions in the perceptron network:
1. Summation function
2. The transfer function (Hardlim in our case)

A bunch of inputs is provided to the network. Each neuron in the network has a weight associated with it. At the beginning
Perceptron is a dense layer. This means Every input will pass through each neuron(Summation Function which will be pass through activation function) and will classify.

**a = hadlim(WX + b)**

Here, 
- 'a' is an output for the activation function which is a class for the input. 
- 'W' is a weight matrix

**6 Methods**

1) _initialize_weights(self):

- This method initializes weights according to the input. 
