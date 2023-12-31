# Title
Training Neural Networks using Backpropagation

# Description
Neural networks, which form the bedrock of deep learning, are trained using the backpropagation algorithm. The algorithm finds the optimal weights and biases for the various neurons forming the network to best approximate the relationship between the predictor and target variables.

The goal of this project is to implement the following using only low-level libraries:
1. A logistic regression model using gradient descent
2. A shallow neural network using backpropagation
3. A deep neural network using backpropagation
4. Optimisation algorithms for training deep neural networks

# Contents
The code files include 4 Jupyter notebooks, one for each objective.

# Results
Similar values of the logistic regression parameters in sections 2 & 3 of 'Logistic Regression Gradient Descent.ipynb' indicate that the custom gradient descent implementation is correct.

Similar values of the neural network loss function in sections 2 & 3 for the same number of iterations in 'Training a Shallow Neural Network.ipynb' and 'Training a Deep Neural Network.ipynb' indicate that the custom gradient descent implementations are correct.

The charts of cost functions versus the number of iterations in 'Optimisation Algorithms.ipynb' show that the Adam optimisation algorithm is the quickest, followed by RMSprop, gradient descent with momentum and mini-batch gradient descent. Each of these algorithms is dramatically faster than batch gradient descent.