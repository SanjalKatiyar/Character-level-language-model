# Character-level-language-model
"dinos.txt" is a list of various dinosaur names thus working as a dataset in this implementation of sequence modeling.
To create new dinosaur names, a character level language model is build. 
An algorithm will learn the different name patterns and randomly generate new names, each line of the dataset(one name) is used as one training example. 
To generate new text we sample a sequence of characters according to a sequence of probability distributions output of the RNN.
Optimization algorithm used to build the character-level language model for text generation is stochastic gradient descent.
