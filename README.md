# Introduction
The aim of this lab is to familiarize with the construction of a Multilayer Perceptron (MLP) – a feedforward neural network. The exercises are not solely aimed at achieving good results in simple predictive problems but primarily at visualizing the network's structure and parameter changes during the learning process. The series of labs on MLP will conclude with the preparation of a report, which should include observations on the behavior of the network learning process based on various hyperparameter settings.

Given that various elements will be modified and their impacts observed, the use of ready-made libraries implementing neural networks is not allowed. Only libraries performing matrix operations, such as numpy, can be used for implementation.

## Topics for Each Lab Session
### NN1: Basic Implementation (Week 1, 2 points)
Implement an MLP network with adjustable parameters: number of layers, number of neurons in each layer, and connection weights including biases.
Use a sigmoid activation function for hidden layers and allow linear function at the output.
Perform regression tasks on provided datasets: square-simple, steps-large.
Experiment with different network architectures:
Single hidden layer, 5 neurons.
Single hidden layer, 10 neurons.
Two hidden layers, 5 neurons each.
### NN2: Backpropagation Implementation (Week 2-3, 4 points)
Implement backpropagation for neural network training.
Visualize weight values during iterations and diagnose learning issues if present.
Implement batch and online (single-sample) updates.
Test on datasets: square-simple, steps-small, multimodal-large.
### NN3: Momentum and Gradient Normalization (Week 4, 2 points)
Implement two enhancements for gradient descent: momentum and RMSProp.
Compare convergence speed for both variants.
Test on datasets: square-large, steps-large, multimodal-large.
### NN4: Classification Task (Week 5, 2 points)
Implement softmax function for output layer.
Evaluate performance on classification tasks using F-measure.
Test on datasets: rings3-regular, easy, xor3.
### NN5: Activation Function Exploration (Week 6, 2 points)
Extend implementation to support various activation functions: sigmoid, linear, tanh, ReLU.
Compare learning speed and network effectiveness for different activation functions.
Preliminary tests on multimodal-large dataset for regression.
Further evaluation on steps-large (regression) and rings5-regular, rings3-regular (classification) datasets with the best-performing configurations.
Conclusion

The conclusion of all these topics is included in the paper: NN_Jeczeń_Magdalena.pdf.





