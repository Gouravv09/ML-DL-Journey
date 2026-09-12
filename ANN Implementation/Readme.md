# 🧠 ANN Implementation

In this folder, I learned the fundamentals of **Deep Learning and Artificial Neural Networks (ANNs)** and implemented the concepts practically.

## 📚 Concepts Learned

- What is Deep Learning
- Perceptron
- Artificial Neural Network (ANN)
- Neurons, Weights & Bias
- Input, Hidden & Output Layers
- Forward Propagation
- Backward Propagation
- Chain Rule & Derivatives
- Weight Updates
- Gradient Descent
- Batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent

## ⚡ Activation Functions

- Linear
- Sigmoid
- Tanh
- ReLU
- Leaky ReLU
- PReLU
- Swish

Also studied their formulas, use cases, advantages, limitations, and the **vanishing gradient problem**. :contentReference[oaicite:0]{index=0}

## 📉 Loss Functions

### Regression
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Huber Loss
- MSLE

### Classification
- Binary Cross Entropy
- Categorical Cross Entropy

Learned how loss functions measure prediction error and how they guide the optimization process. :contentReference[oaicite:1]{index=1}

## ⚙️ Optimizers

- Gradient Descent
- SGD
- Momentum
- AdaGrad
- Adam

Studied how optimizers use gradients to update weights and minimize the loss function. :contentReference[oaicite:2]{index=2}

## 🧮 Mathematical Concepts

- Weighted Sum
- Activation equations
- Loss calculations
- Derivatives
- Partial derivatives
- Chain Rule
- Gradient calculation
- Weight update formulation

### Core Training Flow

```text
Input
  ↓
Forward Propagation
  ↓
Prediction
  ↓
Loss Calculation
  ↓
Backpropagation
  ↓
Gradient Calculation
  ↓
Optimizer
  ↓
Weight Update
  ↓
Repeat
