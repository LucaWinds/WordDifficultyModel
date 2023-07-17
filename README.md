## Word Difficulty Estimation Model

This model utilizes Word2Vec and a Multilayer Perceptron (MLP) to build a regression model for measuring the difficulty of given words. It was trained in the Colab environment.

### Word2Vec

Word2Vec is an embedding technique that transforms words into vectors. It allows us to represent the meaning and relationships of words numerically. The Word2Vec model learns distributed representations of words, capturing the contextual information of surrounding words to generate word vectors. This enables similar words to be closer together in the vector space.

### Multilayer Perceptron (MLP)

The Multilayer Perceptron is an artificial neural network with multiple hidden layers. Each hidden layer consists of multiple neurons, which learn non-linear relationships in the input data using activation functions and weights. In the case of this regression model, the output is directly predicted from the MLP's output layer without an activation function.

### Word Difficulty Estimation

The regression model utilizes the Word2Vec vectors as input. The vectors represent the features of given words. The MLP then performs regression prediction based on these features. The model was trained in the Colab environment, taking advantage of its resources and facilitating fast model training using GPUs or TPUs.

This model can be used to estimate the difficulty of given words in text data. It has potential applications in various fields.
