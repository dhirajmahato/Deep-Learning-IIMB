## Neural network
### Components
1. Neuron
2. Activation Function
3. Layers
4. Architecture
5. Optimizer
6. hyperparameter


<img width="775" alt="Screenshot 2025-05-19 at 8 55 14 AM" src="https://github.com/user-attachments/assets/d4d1a474-f174-4967-b3f9-e6bb7a5bc91b" />
<img width="1376" alt="Screenshot 2025-05-22 at 11 16 09 AM" src="https://github.com/user-attachments/assets/619dd390-2152-4bed-b4f7-7955a5569f4c" />


## Perceptron networks
A Perceptron network is a basic type of artificial neural network with a single layer of perceptrons, each functioning as a binary classifier. It is designed for binary classification tasks and uses the Perceptron learning rule to adjust weights during training. This rule updates weights based on the difference between the predicted and actual outputs, improving the network’s accuracy over time. While simple, the Perceptron network has limitations, such as its inability to solve non-linearly separable problems. Nevertheless, it lays the groundwork for more complex neural network architectures, such as multi-layer perceptrons, which address more intricate classification challenges.

<img width="1221" alt="Screenshot 2025-05-20 at 9 26 51 AM" src="https://github.com/user-attachments/assets/3c9fc0aa-4b7e-4b68-8fc9-69224b30914d" />

## Multi-Layer Perceptron networks
Multi-Layer Perceptron (MLP) networks, which include hidden layers, overcome the limitations of single-layer Perceptrons by enabling non-linear transformations. This allows MLPs to model complex logic functions effectively. An MLP is an artificial neural network with multiple layers that can learn and represent non-linear relationships, capturing intricate patterns. To improve predictions, MLP networks use back-propagation and gradient descent to adjust weights. This makes them well-suited for tasks like classification and regression, where capturing complex patterns and relationships is crucial.

## gradient descent algorithm
gradient descent optimizes models by iteratively updating parameters to reduce the cost function, ultimately improving accuracy and predictions.
<img width="1273" alt="Screenshot 2025-05-20 at 9 36 59 AM" src="https://github.com/user-attachments/assets/7c533316-766e-44c7-b96b-92a4a721377f" />
<img width="1297" alt="Screenshot 2025-05-22 at 11 21 40 AM" src="https://github.com/user-attachments/assets/b3a6061d-2367-4afa-a6e5-0674cd698ce9" />



## Activation Function 
src: [here](https://youtu.be/GbZBVMuBhOM)

It brings nonlinerilty for the output layer.
1. sigmod function
2. tanh(x)
3. ReLU = MAX(0,x)
4. Softmax

## back-propagation algorithm
## Hyperparameter
Key hyperparameters:
1. the number of hidden layers, depends 
2. the number of neurons per layer,
3. learning rate, 
4. activation functions,
5. batch size, 
6. regularization parameters,
7. dropout rate, and
8. the optimization algorithm,
9. no of iterations.
