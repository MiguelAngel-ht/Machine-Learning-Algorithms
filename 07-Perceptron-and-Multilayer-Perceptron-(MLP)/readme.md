# Simple Perceptron and MultiLayer Perceptron

## What is a Perceptron?

A perceptron is a type of artificial neuron or node used in supervised learning of binary classifiers. The perceptron makes decisions by weighing input signals, summing them, and then passing them through a type of step function known as an activation function. It's a foundational element of neural networks and serves as a stepping stone to more complex network architectures, such as MLP.

## What is MLP?

Multi-Layer Perceptron (MLP) is a class of feedforward artificial neural network. Unlike the simple perceptron, which can only classify linearly separable sets of vectors, MLP can represent a much broader range of decision boundaries thanks to its hidden layers and non-linear activation functions. MLP consists of at least three layers of nodes — an input layer, a hidden layer, and an output layer.

## What are the Differences?
* **Complexity:** A perceptron is a single-layer structure, while MLP has multiple layers, making MLP more capable of handling complex data patterns.
* **Decision Boundaries:** Perceptrons can only model linear decision boundaries, while MLPs can model non-linear decision boundaries, thanks to their non-linear activation functions.
* **Training Algorithm:** Perceptrons are trained using the Perceptron learning rule, while MLPs are trained using more sophisticated algorithms like backpropagation.

## Applications IRL of Perceptron and MLP
Perceptron
Pattern Recognition: It can be used in simple tasks of pattern recognition.
Linearly Separable Problems: Ideal for problems where a clear linear decision boundary exists.
MLP
Image Recognition: With multiple layers, MLPs are powerful enough to be used in image recognition tasks, including handwriting recognition and facial recognition.
Speech Recognition: MLPs have found applications in complex tasks like identifying patterns in speech.
Classification Problems: They are used in various classification tasks where non-linear decision boundaries are required.
When is it Better to Use One Over the Other?

## Use Perceptron When:
You have a linearly separable problem.
The simplicity and interpretability are essential.
You need a basic binary classifier.

## Use MLP When:
The data is non-linearly separable.
The problem complexity requires a more sophisticated model.
You need to capture intricate patterns in the data, and model interpretability is not a primary concern.
