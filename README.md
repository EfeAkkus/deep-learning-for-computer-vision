# CS231n Implementations

This repository contains my implementations and notes while studying the CS231n course.

---

## Topics

### Lecture 1: Image Classification

- k-Nearest Neighbor (kNN)
- Distance metrics (L1, L2)
- Hyperparameter tuning
- Validation and Cross-validation

---

### Lecture 2: Linear Classification

- Linear classifier
- Score function
- Bias trick
- Multiclass SVM loss (hinge loss)
- Softmax classifier
- Cross-entropy loss
- Regularization (L2)

---

### Lecture 3: Optimization (SGD)

- Loss optimization
- Gradient Descent
- Numerical gradient
- Analytic gradient
- Gradient check
- Learning rate (step size)
- Stochastic Gradient Descent (SGD)
- Mini-batch Gradient Descent

---

### Lecture 4: Backpropagation

- Chain rule interpretation
- Real-valued circuits
- Patterns in gradient flow

### Lecture 5: Neural Networks Part 1

- Model of a biological neuron
- Computational model of a neuron
- Activation functions
- Neural network architectures
- Forward pass computation
- Setting number of layers and hidden units
- Representational power
- Regularization and overfitting

### Lecture 6: Neural Networks Part 2

- preprocessing
- weight initialization
-  batch normalization
- regularization (L2/dropout)
- loss functions

### Lecture 7: Neural Networks Part 3

- gradient checks,
- sanity checks
- babysitting the learning process
- momentum (+nesterov), second-order methods
- Adagrad/RMSprop
- hyperparameter optimization
- model ensembles 

---

## Structure

- `01_knn/` → Lecture 1
- `02_linear_classification/` → Lecture 2
- `03_optimization/` → Lecture 3
- `04_backpropagation/` → Lecture 4
- `05_neural_networks1/` → Lecture 5
- `06_neural_networks2/` → Lecture 6
- `07_neural_networks3/` → Lecture 7
- `datasets/` → local datasets (not tracked by git)

---

## Notes

Datasets are not included. Please download CIFAR-10 manually.