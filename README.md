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
- 'X' is a input to the network
- 'b' is a Bias to the network

**CODE:**

**7 Methods**

1) _initialize_weights(self):
2) initialize_all_weights_to_zeros
3) Prdict
4) print_weights
5) train
6) calculate_percent_error
7) Main (Contains Driver code to understand the program)

Click here to see the full coe:
https://github.com/vrajkp/Single_layer_perceptron/blob/master/perceptron.py
