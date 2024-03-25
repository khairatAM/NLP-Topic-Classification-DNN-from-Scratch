The goal of this project is to develop a Feedforward neural network for topic classification.

For that purpose, we will implement text processing methods for transforming raw text data into input vectors for the network. And a Feedforward network consisting of:

- One-hot input layer mapping words into an Embedding weight matrix
- One hidden layer computing the mean embedding vector of all words in input followed by a ReLU activation function
- Output layer with a softmax activation.
- The Stochastic Gradient Descent (SGD) algorithm with back-propagation to learn the weights of the Neural network. The algorithm should:
  - Minimise the Categorical Cross-entropy loss function
  - Perform a Forward pass to compute intermediate outputs
  - Perform a Backward pass to compute gradients and update all sets of weights
  - Implement and use Dropout after each hidden layer for regularisation
