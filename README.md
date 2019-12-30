# PCBS_NeuralNetworks

The aim of this project will be to code a variety of neural network algorithms and architectures from scratch - instead of using a predefined library - in order to gain a comprehensive understanding of what is happening 'under the hood'.

Firstly, I will create a simple multilayer perceptron capable of solving a basic non-linearly separable classification problem, the XOR problem. Since there will be only 1 hidden layer, I will code the weights, biases and errors for each layer explicitly, to get an expanded overview of the algorithm's functioning. I will also create visualisations of the separation we are trying to achieve and of the reduction in error over time.

Next, I will move onto a larger classification problem, using a toy dataset with more training data but still two output categories. For this architecture I code each step as universal functions to allow hyperparameters such as the number of hidden layers to be modified freely. I will use for-loops to compress the computational steps into shorter lines of code, and begin to streamline the process a little. Here I will be able to explore the effect of modifying different hyperparameters on the accuracy and rate of convergence of the network. 

Finally, I will use a real dataset with seven training variables and three output categories, classifying species of wheat seed (https://raw.githubusercontent.com/jbrownlee/Datasets/master/wheat-seeds.csv). Here I will try to make my  code implementation even more flexible and generalisable, to allow it to be used on any dataset with any number of variables and output categories. I will code a pipeline to split the dataset into epochs and train using online stochastic gradient descent to achieve a reasonable training time for the network. (Possibility to also try object-oriented approach ?)


