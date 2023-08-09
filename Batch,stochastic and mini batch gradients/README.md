# Deep_Learning
Batch Gradient Descent, Stochastic Gradient Descent, and Mini-Batch Gradient Descent are three variations of the gradient descent optimization algorithm used to train machine learning models, particularly in the context of deep learning. They differ in how they use training data and update model parameters during each iteration of the optimization process. Here's a breakdown of the differences:

Batch Gradient Descent (BGD):

1. In Batch Gradient Descent, the entire training dataset is used to compute the gradient of the cost function with respect to the model parameters (weights and biases) in a single iteration.
2. The gradients are averaged over all the training examples, which can result in a stable and consistent convergence.
3. However, using the entire dataset for each iteration can be computationally expensive and memory-intensive, especially for large datasets.

Stochastic Gradient Descent (SGD):

1. In Stochastic Gradient Descent, only one randomly selected training example is used to compute the gradient in each iteration.
2. The gradient is updated more frequently, leading to potentially faster convergence and escaping local minima. It can also handle large datasets more efficiently.
3. However, the stochastic nature of updates can lead to a noisy convergence process, and the algorithm may not converge to the global minimum.

Mini-Batch Gradient Descent:

1. Mini-Batch Gradient Descent combines the benefits of both BGD and SGD by using a small subset (mini-batch) of the training data in each iteration.
2. The dataset is divided into mini-batches, and the gradient is computed for each mini-batch. The model parameters are updated after processing each mini-batch.
3. This approach offers a compromise between the efficiency of BGD and the faster convergence of SGD. It can utilize parallel processing and hardware acceleration effectively.
4. The mini-batch size is a hyperparameter that can be tuned. Common choices include powers of 2 like 32, 64, or 128.
