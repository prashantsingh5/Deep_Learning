# gradient descent, loss function, activation

Gradient Descent:

Gradient descent is an optimization algorithm used to minimize (or maximize) a function iteratively. In the context of machine learning, it's commonly used to update the parameters (weights and biases) of a model to minimize the loss function. The basic idea is to move in the direction of steepest descent (negative gradient) of the function to reach a local minimum.

Loss Function:

A loss function, also known as a cost function or objective function, quantifies the difference between the predicted values of a model and the actual target values. It serves as a measure of how well the model is performing. The goal during training is to minimize this loss function.
Common loss functions include:
1. Mean Squared Error (MSE): Used for regression tasks.
2. Binary Cross-Entropy: Used for binary classification tasks.
3. Categorical Cross-Entropy: Used for multi-class classification tasks.

Activation Function:

Activation functions are applied to the output of a neuron in a neural network. They introduce non-linearity into the network, enabling it to learn complex relationships in the data. Activation functions determine whether a neuron "fires" or not based on its input.
Common activation functions include:
1. Sigmoid: Maps input to a range between 0 and 1. It's often used in the output layer for binary classification.
2. ReLU (Rectified Linear Unit): Outputs the input if it's positive, and zero otherwise. It's widely used in hidden layers due to its effectiveness in training deep networks.
3. Tanh (Hyperbolic Tangent): Similar to the sigmoid, but maps input to a range between -1 and 1.
4. Softmax: Used in the output layer for multi-class classification, it converts raw scores into probability distributions.
The choice of activation function depends on the network architecture, the nature of the problem, and the potential vanishing/exploding gradient problem.
