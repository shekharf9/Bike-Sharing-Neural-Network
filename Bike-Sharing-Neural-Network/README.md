The project contains python code build on the jupyter notebook.

#Dependencies

The dependencies for the project are mentioned in the requirements.txt file.

In Linux(Ubuntu) install the dependencies in a seperate environment using the command:
     $ pip install -r requirements.txt


#Neural Network

In this project, a neural network is used to predict daily bike rental ridership.

#Checking out the data

This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. 

#Time to build the network

The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is f(x)=x. A function that takes the input signal and generates an output signal, but takes into account the threshold, is called an activation function. We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer. This process is called forward propagation.

We use the weights to propagate signals forward from the input to the output layers in a neural network. We use the weights to also propagate error backwards from the output back into the network to update our weights. This is called backpropagation.



