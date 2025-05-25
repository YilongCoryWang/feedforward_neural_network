# Feedforward Neural Network with PyTorch

This repository provides hands-on examples of building and training feedforward neural networks using PyTorch. It includes two Jupyter notebooks that demonstrate the implementation and training of neural networks on synthetic datasets.

## Contents

- **`1. simple_feedforward_nn.ipynb`**: Introduces the basics of constructing a simple feedforward neural network using PyTorch. It covers:

  - Defining the network architecture
  - Forward propagation
  - Loss computation
  - Backpropagation and parameter updates
  - Training on a synthetic dataset

- **`2. feedforward_nn_with_validation.ipynb`**: Expands upon the first notebook by incorporating:
  - Validation dataset evaluation
  - Tracking training and validation loss over epochs
  - Plotting loss curves for performance visualization
  - Implementing early stopping criteria

## Getting Started

### Prerequisites

- Python 3.7 or higher
- PyTorch
- Jupyter Notebook
- NumPy
- Matplotlib

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/YilongCoryWang/feedforward_neural_network.git
   cd feedforward_neural_network
   ```

2. **Install the required packages:**

   It's recommended to use a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

   Note: If requirements.txt is not provided, manually install the necessary packages:

   ```bash
   pip install torch torchvision matplotlib numpy jupyter
   ```

   Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Navigate to the cloned repository folder and open the desired notebook.

## Usage

1. **Run the notebook cells sequentially:**

   Each notebook is structured to guide you through the process of building and training a feedforward neural network. Execute each cell in order to follow along with the implementation and observe the results.

2. **Modify parameters as needed:**

   Feel free to adjust hyperparameters such as learning rate, number of epochs, and network architecture to experiment with the model's performance.
