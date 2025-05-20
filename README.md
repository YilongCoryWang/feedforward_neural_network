# Simple 2-Layer Neural Network from Scratch (NumPy)

This is a basic example of implementing a 2-layer neural network using only NumPy. It demonstrates how to train the network by performing forward propagation, manual backpropagation (gradient computation), and parameter updates to fit a nonlinear target function.

**❗Important: The core idea is adjusting the values of parameters to make Loss Function (Mean Squared Error (MSE)) minimal. If the derivative is positive, meaning the parameter value making the loss function getting larger, then reduce the parameter value. On the other hand, if derivative is negative, meaning the parameter value making the loss function getting smaller, then increase the parameter value to make loss function even smaller.**

**Why using derivatives? Think of every parameter has contribution to loss function. Minimising each parameter's contribution will eventually make the loss function value minimal.**

## 🧠 Network Architecture

A feedforward neural network with one hidden layer:

x ──► [Linear: a0 + a1x] ──► [Activation] ──► [Linear: b0 + b1y] ──► [Activation] ──► z

- **Input**: Scalar input `x`
- **Hidden Layer**: Linear transformation + activation
- **Output Layer**: Linear transformation + activation
- **Loss Function**: Mean Squared Error (MSE)

---

## 🔧 Features

- Supports activation function: `relu`
- Manual backpropagation with explicit gradient formulas
- Batch training with multiple epochs
- Mean Squared Error loss computation
- `matplotlib` for visualizing training loss

---

## 🧪 Example Configuration

```python
inputs  = np.array([0.7853, 1.57])
targets = np.array([0.707, 1.0])
beta    = 0.1           # Learning rate
epochs  = 50            # Number of training epochs
```
